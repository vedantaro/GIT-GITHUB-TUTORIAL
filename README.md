# GIT-GITHUB-TUTORIAL

/*Connecting Git*/
git config --global user.name "username"

git config --global user.email "email"
git config --list

/*Clone*/

Clone = Cloning a rep on our local machine
git clone https://github.com/vedantaro/GIT-GITHUB-TUTORIAL.git

/*Status*/

status = display the status of the code
git status

Types of Status
untracked = new files that git doesn't yet track
modified = changes in files
unmodified = unchanged
staged = file is ready to be committed

/*Add*/

add= adds new or changed files in your working directory to the git staging area
git add <-file name->
git add . /*change or add all files*/

/*Commit*/

commit = it is the record of change
git commit -m "some message"

/*PUSH Command*/

push = upload local rep content to remote repo
git push origin main
origin = origin is the name of our remote GitHub
main = main is the branch of our repo

/*CMD commands*/
cd <-folder name-> = change directory
cd .. = goes out of the current directory 
mkdir <-folder name-> = to create a new folder  
ls = Show files in folder
ls -a = show hidden files  as well


