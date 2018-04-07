# Git basics commands

## Getting started
Download git-bash by [clicking here](https://git-scm.com/downloads).

#### Setting up your git
You have to set username and email in git, because every commit use this information
```
git config --global user.name "Nishant Patel"
git config --global user.email mpatel@example.com
```

#### Setup your editor
If you don't want to use default editor and what to use atom for that,
you can write following to set editor
```
git config --global core.editor atom
```

#### Initialize repository
`git init`

#### Check status
`git status`

#### Check commit detail logs
`git log`

#### Check commit logs in one line
`git log --oneline`

#### Check the difference after a file modification
`git diff`

#### Adding Multiple files to staging area 
`git add .`

#### Unstage previously staged commits
`git reset HEAD -- .`

#### Perform a commit 
`git commit -m "commit_message"`

#### Create a branch and make a switch to thet branch
`git checkout -b new_branch_name`

#### To get list of all available branch
`git branch`

#### Create a remote repository
`git remote add origin "https://github.com/nishantkp/git-basics"(your-remote-repository)`
`git remote add upstream "https://github.com/cvbutani/git-basics"(pull-remote-repository)`

#### Get the list of all remote repository
`git remote -v` or `git remote`

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
