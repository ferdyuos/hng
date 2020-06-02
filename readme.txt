Git is a version Control system to track change in your source code during software development

GitHub uses "Git" to provide hosting for individuals and companies for software development


"git init" - a git command used to initialize an empty git repository in pwd. Can move to a directory of your choice using cd /path/to/directory

"rm -rf .git" - a git command to delete .git repository

"touch filename - a command to create a file
 cat filename
"    

"git status" - a git comamnd to know which files git knows exist to check which branch you are on. 
		It also shows that unless you use "git add" command nothing would be committed. It also shows if you have committed anyything yet 

What is a commit?
a commit is a record of what files you have changed since the last time yoyu made a commit. Can go to any part of your project if you make a commit

To put files in a commit , a staging environment or formerly index is needed.

To add a file to commit, you need to add the file to a staging enviroment by using "git add filename". It shows files to be committed. To tell git to package into
a commit, use "git commit" command. When committing a file, a commit message is needed to signal the need of that commit. It serves as a comment.
To escape the commit editor press "escape key" and then type ":wq" or use (git commit -m "message here") or (git commit -F "message here") if you want to use the
command lien to add a commit 


"git add filename" - to add the file to a staging enviroment

"git commit" - to commit a file

(git commit -m "message here" OR git commit -F "message here") - to add commit message in command line


Git Branches?
a git branch allwo you to move back and forth betrween states of a project without affecting other parts f that project. When done can mege your changes from your
branch into master branch. On initializing an empty git, automatically you are on the master branch

"git checkout -b <branch name>" - to create a branch and git moves you to that branch

"git checkout <branch name>" - to move between branches

"git branch" - to check branches in project. The one with "*" shows your present working branch

