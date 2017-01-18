#Git Cheatsheet
**Name** Jake Shane
**Date** January 17, 2017

**this sets user name for git**  
git config --global user.name "[name]"

**this sets email for git**  
git config --global user.email "[email address]"

**this lists configured email and username for git**  
git config --list

**This initializes the Git repository so it knows to pay attention to this folder**  
git init

**This will link the local and remote repo**  
git remote add origin [URL of your remote repo]

**this confirms that local and remote are linked -- should see something like Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (fetch)
Origin https://github.com/jojokarlin/Git_DRI_Jan_2017 (push)**  
git remote -v

**this will tell you if changes have been made but not "staged" (i.e. not added) or committed**  
git status

**This stages the file to be tracked, and prepares it to be committed**  
git add "filename" 
git add . 
git add --all

**This commits staged files to git. Remember to add descriptive message about commit**  
git commit -m "[message]"

**This shows what has happened in git session**  
git log

**This pushes commits from local to remote**  
git push origin master

**This is the order to needed to upload modified file**  
1. git add "filename" *or* git add . *or* git add --all  
2. git commit -m "[message]"  
3. git push origin master

**more notes**
git config *tells git who is working*
git init *tells git which repo to monitor*
git add *tells git to track this file*
git commit *tells git to log this version (add -m to include a note about it)*
git push *share this local version with a remote github repo*

**Helpful Commands**

*Here is a list of commands that we used in this workshop to navigate Git and GitHub in your command line:*

cd [name of directory or folder]  *will navigate you into the directory you identified.*

cd ..  *will navigate you up a directory.*

cd -  *goes back to the last directory you were in.*

pwd  *or "print working directory" will tell you where you are if you get a little lost.*

mkdir  *[name] makes a new directory.*

git init  *(initiates git for this directory).*

touch [name].md  *makes a new markdown file, which is plain text, in whatever directory you're in in the command line.*

touch [name].[extension]  *makes the type of file you specify in whatever directory you're in in the command line.*

git status  *checks the status of your commits. Use often!*

git add [filename].[extension]  *stages the file.*

git commit -m "[text]"  *commits the changes, with a note about this commit.*

git push origin master  *pushes commits to the master branch.*

git pull [URL of remote repo]  *updates your local repo with remote changes.*

git clone [URL of remote repo]  *makes a local copy of a remote repo for you to edit.*
