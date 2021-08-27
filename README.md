# Git Branching Test

This repo is for testing purpose! 

The goal of this repo is to create a branch which contains different files and directories then in master branch. This can be useful for various reasons, such as publishing a github page for example. 

## Steps
1. Create a master/main branch for the repo `git init`
2. Add any files or directories for master branch 
3. Commit any changes for master branch `git add . && git commit -m "message"`
4. Setup remote and push changes to remote `git push origin master`
5. Create a empty folder under root directory `/folder_name`.
6. Clone the master repo in /folder_name `git clone repo_url .`.
7. Creat a new branch `git checkout -b new-branch && git push origin new-branch`
8. Delete master branch in /folder_name `git branch -d master`
9. Update files and directory only for the special branch and remove others files which are not necessary.
10. Commit changes in /folder_name 
11. Push all changes to remote `git push origin new-branch`;
12. Delete /folder_name

[Reference](https://gist.github.com/chrisjacob/833223)

For simplicity, you can use [gh-pages](https://www.npmjs.com/package/gh-pages) to simplify the process. Underlying, it works all the steps for you in background.
