# Git basics commands

#### Initialize repository
<br>`git init`

#### Check status
<br>`git status`

#### Check commit detail logs
<br>`git log`

#### Check commit logs in one line
<br>`git log --oneline`

#### Check the difference after a file modification
<br>`git diff`

#### Adding Multiple files to staging area 
<br>`git add .`

#### Unstage previously staged commits
<br>`git reset HEAD -- .`

#### Perform a commit 
<br>`git commit -m "commit_message"`

#### Create a branch and make a switch to thet branch
<br>`git checkout -b new_branch_name`

#### To get list of all available branch
<br>`git branch`

#### Create a remote repository
<br>`git remote add origin "https://github.com/nishantkp/git-basics"(remote-repository)`

#### Get the list of all remote repository
<br>`git remote -v` or `git remote`

#### Send commits to remote repository
```
git push origin master
origin -> remote repository name
master -> local repository branch
```

#### Get commits from remote repository
```
git pull origin master or git fetch origin master
origin -> remote repository name
master -> local repository branch
```
Dont forget to merge after using `git fetch`
