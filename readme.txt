
Basic Git commands

Tell Git who you are:
 	Configure the author name and email address to be used with your commits.
	- git config --global user.name "Sam Smith"
	- git config --global user.email "sam@example.com"

Create a new local repository:
	- git init

Check out a repository:
	Download existing source code from a remote repository:
	- git clone <https://name-of-the-repository-link>

Add files:
	Add one or more files:	
	- git add <filename>
	Add all files:
	- git add .

Status:
	List the files you've changed and those you still need to add or commit:	
	- git status

Commit:
	Commit changes to head (but not yet to the remote repository):
	- git commit -m "Commit message"

Connect to a remote repository:
	If you haven't connected your local repository to a remote server, add the server to be able to push to it:
	- git remote add origin <repository_link>

Push:
	Push the branch to your remote repository, so others can use it:
	- git push origin <branchname>

Branches:
	Create a new branch and switch to it:
	- git checkout -b <branchname>
	
	Switch from one branch to another:	
	- git checkout <branchname>

	List all the branches in your repo, and also tell you what branch you're currently in:	
	- git branch

	Delete the feature branch:	
	- git branch -d <branchname>

Update from the remote repository:
	Fetch and merge changes on the remote server to your working directory:	
	- git pull

	To merge a different branch into your active branch:	
	- git merge <branchname>
	


	