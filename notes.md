-------Git configuration-----

git config --global user.name "my name"
git config --global user.email "email"
git config --list

----vs code----

git cone _____//paste the repo link
git add .//
git add filename
git commit -m "message"
git push origin main

----on system----

git init //to initialize a git repo inside a folder
cd ..//to go outside of the current folder
mkdir "repoName"
git init //now make the git repo inside that folder
git add .
git commit -m "message"
got remote add origin __________//add the repo link 
git branch//to check the branch
git branch -M "new name of the branch"
git push -u origin main//by this we are making the shortcut for pushing now we just have to write the git push command on the terminal to push our code on the github

-----------Branch Commands-----------
git branch //to check the present branch
git branch <branch name>//to navigate the branch 
git checkout -b <new branch name>//to create a new branch
git branch -d <branch name>//to delete the current branch
git push origin ___________//write new branch name

----------Merging Code----------

git diff<branch name>(difference is two branches)
git merge <branch name>

-----------Pull requests--------
using github

------pull command--------
git pull origin main
this is used to fetch and download contect from a remote repo and immediately update the local repos to match the content

--------resolving the merge conflicts--------
An event that takes place when a git is unable to automatically resolve the differences in the code btw two commits


