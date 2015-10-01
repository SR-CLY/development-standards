# CLY SR Git Standards

Ideally, you shouldnt be using the IDE for anything other than building and exporting the zip. This is mainly because the IDE doesnt work well with multiple collaborators (the whole point of git), meaning there is increased change of merge conflicts when you go to save.

You should be editing the files locally, and then push the changes up to git, which means you will see instantly if there is a conflict. If you pull anything from SR before you push, then it will greater decrease the chances of a merge conflict.


Important commands:
* _git pull origin master_: Pull changes from SR to local
* _git push origin master_: Push your local changes to SR

