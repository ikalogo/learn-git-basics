# Git Command Cheat Sheet

##### Cloning your remote directory
		git clone <remote directory>

##### Checking that status of your local repository
		git status

##### Creating a new branch for you to work on
		git branch <new branch name>

##### See all branches in your remote repository
		git branch -a

##### Moving onto a branch
		git checkout <branch name>

##### Deleting a branch
		git branch -d <branch name>

##### Creating a branch and moving onto it right after
		git checkout -b <new branch name>

##### Staging changes for commit (at this point git will keep track of changes to this file)
		git add <modified file name>

##### Commit (saving your edits so they are trackable)
		git commit -m "message detailing what sort of changes you've made"

##### Unstaging file 
		git revert HEAD <modified file name>

##### Updating a branch (it is good practice defore a merge to make sure the branch is up to date with master branch)
		git pull origin master 

##### Merging master branch to a branch so it's up to date in case someone made changes (make sure you have switched to the branch)
		git merge master

##### Pushing changes to the remote repositoty (make sure you have merged the current branch with the updated verison of master)
		git push origin <branch name>

