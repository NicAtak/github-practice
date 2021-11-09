## GIT CHEATSHEET
## Initialize an empty ocal Github repository
git init
## Establish the connection between local and remote GIT repository
git remote add origin <https://github.com/username/repositoryname.git>
## SHow connected repository
git remote show origin
## Disconnect the connection between local and remote GIT repository
git remote remove origin
## Switching between branches
git checkout branch-name
## Creating new branches from current branch
git checkout -b new-branch-name
## List out local branches
git branch
## Checking the status of a currentbranch
git status
## All all uncomitted changes in current directory
git add -A OR git add .
## Committing your local changes 
git commit -m "your message goes here"
## Pushing your committed changes
git push origin branch-name

```
Workflow is ADD, COMMIT and PUSH
```