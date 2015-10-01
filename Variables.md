# CLY SR Variable naming conventions

Variable naming is one of those things that doesn't actually matter to the quality, speed, or efficiency of your code, but if you want there to be a standard, you need to have a naming scheme!

### Classes
Classes start with a capitol, and each word in the classes name is seperated by no space, and again has a capitol at the beginning.
```class MyRandomClass():```

### Variables
Variables should all be lower case, and words seperated by underscores.
``` my_random_variable = 'foobar' ```
Functions should also be defined in this way.

### Constants
Constants should be defined at the top of a file, right below the imports, and should be in block capitols wit underscores seperating words, much like normal variables.
``` MY_RANDOM_CONSTANT = 12 ```

### Imports
Importing external libraries or files should be done in the order 2,3,1. This means that you should be importing the modules for student robotics first, and any other external libraries first. Then importing any libraries you made, usually in the same directory, and then you should import any modules which are built in to python. This convention is a little silly, but it keeps nice clean code where all the imports for the same thing are in the same place.
```
from sr.robot import Robot
import movement, mechanics, vision
from json import loads
```

### Line Length
One common rule is the 80 char line length rule, set out by PEP8. I personally think this is a stupid rule, because you have to adapt your code to make it fit on one line, but some kind of char limit is good, however not a quantified one. Whilst you are writing a line, if it seems too long, either because you are chaining a lot of different operands, or because you are nesting a lot of different functions and logic, break it up. It will make it much easier to understand.

