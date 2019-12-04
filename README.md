Command List

Anything surrounded by `[brackets]` should be replaced with your information.

`git pull`: downloads bookmark history and incorporates changes (you need to do this if you make any changes not using CodeAnywhere)

`git branch -a`: list all branches (local and remote)

`git checkout -b [branch-name]`: creates a new branch "branch-name" and switches to that branch

`git checkout [master]`: switches to the specified branch and updates the working directory

`git status`: lists all new or modified files to be committed, as well as telling you what branch you're on

`git add .`: snapshots all files in preparation for versioning

`git commit -m "[descriptive message]"`: records file snapshots permanently in version history with the commit message "descriptive message"

`git push`: uploads all local branch commits to GitHub

 
Workflow

`git checkout -b [branch-name]` create a branch to work on the current assignment

Do the work

`git status` changed files will appear in red

`git add .` prepare files to be committed

`git status` changes files will appear in green

`git commit -m "[commit message]"` commit the changes and prepare them for the server

`git push` send the commit(s) to the server

if there is an error: `git push --set-upstream origin [branch-name]`
