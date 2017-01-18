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
