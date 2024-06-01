# GIT-GITHUB-TUTORIAL

/*Connecting Git*/

git config --global user.name "username"<br>

git config --global user.email "email"<br>
git config --list<br>

/*Clone*/

Clone = Cloning a rep on our local machine<br>
git clone https://github.com/vedantaro/GIT-GITHUB-TUTORIAL.git<br>

/*Status*/

status = display the status of the code<br>
git status<br>

Types of Status<br>
untracked = new files that git doesn't yet track<br>
modified = changes in files
unmodified = unchanged<br>
staged = file is ready to be committed<br>

/*Add*/

add= adds new or changed files in your working directory to the git staging area<br>
git add <-file name-><br>
git add . /*change or add all files*/<br>

/*Commit*/

commit = it is the record of change<br>
git commit -m "some message"<br>

/*PUSH Command*/

push = upload local rep content to remote repo<br>
git push origin main
origin = origin is the name of our remote GitHub
main = main is the branch of our repo<br>

/*Init Command*/

init = used to create a new git repo<br>
git init<br>
git remote add origin <-link-><br>
git remote -v (to verify remote)<br>
git push origin main<br>

/*Branch Commands*/

git branch (to check branch)<br>
git branch -M main (to rename branch)<br>
git checkout <-Branch Name-> (to navigate to another branch)<br>
git checkout -b <-new branch name-> (to create new branch)<br>
git branch -d <-branch name-> (to delete branch)<br>

/*PULL Command*/

git pull origin main = used to fetch and download content from a remote repo to local repo<br>

/*Merging Code*/

git diff <-branch name-> (to compare commits branches, files & more)<br>
git merge <-branch name-> (to merge 2 branches)<br>

/*Resolving Merge Conflicts*/

An event that take place when git is unable to automatically resolve differences in code between two commits<br>

/*UNDO Changes & Restore*/

Case 1: staged changes (git add)<br>
git reset <-file name-><br>
git reset<br>

case 2: committed changes (git commit -m "some message")<br>
git reset HEAD~1<br>

case 3: committed changes (for many commits)<br> 
git reset <-commit hash-><br>
git reset --hard <-commit hash-><br>

git log = use git log to get the hash<br>
git restore <-file name-> = restore the file data<br>

/*CMD commands*/

cd <-folder name-> = change directory<br>
cd .. = goes out of the current directory<br> 
mkdir <-folder name-> = to create a new folder<br>  
ls = Show files in folder<br>
ls -a = show hidden files as well<br>


