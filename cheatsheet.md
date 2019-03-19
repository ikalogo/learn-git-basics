# Git Command Cheat Sheet

##### Cloning your remote directory
        git clone <remote directory>

##### Checking that status of your local repository
        git status

##### Pulling down all branches in a remote repo, not just the default branch
        git fetch --all

##### Creating a new branch for you to work on
        git branch <new branch name>

##### See all branches in your remote repository
		git branch -a

##### Moving onto a branch
        git checkout <branch name>

##### Deleting a branch
		git branch -d <branch name>

##### Merging changes from another branch, to your current branch
        git merge <branch you want to merge with your current branch>

##### Creating a branch and moving onto it right after
		git checkout -b <new branch name>

##### Staging changes for commit (at this point git will keep track of changes to this file)
		git add <modified file name>

##### Commit (saving your edits so they are trackable)
		git commit -m "message detailing what sort of changes you've made"

##### Unstaging changes 
		git reset HEAD <modified file name>

##### Updating a branch (it is good practice defore a merge to make sure the branch is up to date with master branch)
		git pull origin master 

##### Pushing changes to the remote repositoty (make sure you have merged the current branch with the updated verison of master)
		git push origin <branch name>

##### Check the credentials on the local machine 
		git config --list

##### Edit your name and email on the credentials file
		git config --global user.name "your name"
		git config --global user.email "your email"

