# Git Cheatsheet


+ **fork**

To copy someone's repository to your github. Remote, in github

---
+ **init**

Go to the directory you want to initialize git in and use this command. Local, github not necessary

`git init`

---
+ **clone**

To download a github repository (remote) to your local working directory, e.g:

`git clone <URL>`

---
+ **add**

Prepare file for commit, move from working directory to staging area. Local

`git add "file"`

---
+ **commit**

To move file from staging area to git repo. Still local. Comment must be made, either with nano (no flag needed) or inline:

`git commit -m "comment"` (remember quotes)

If the file is already in git and has only been modified, skip git add and use a and m flag:

`git commit -am "comment"` (remember quotes)

---
+ **pull**

To make sure everything is updated before pushing to github, e.g.

`git pull origin master`

---
+ **push**

To push your changes to the github repository (remote), e.g.

`git push origin master`

---
+ **branch**

To check which branch you're on. To see all branches:

`git branch -a`

To create new branch

`git branch "new branch name"`

To change the name of existing branch:

`git branch -m "current branch name" "new branch name"`

To delete branch:

`git branch -d "branch name"`

---
+ **checkout**

To switch to other branch (check it out):

`git checkout "other branch name"`

To create a new branch and jump to it immediatly, use b flag:

`git checkout -b "new branch name"`

---
+ **log**

To see history of repository, use:

`git log --oneline`

---
+ **diff**

To compare two branches/see changes, use:

`git diff "one branch" "other branch"`

---
+ **merge**

To join together the changes that have been made

`git merge "branch name"`

---


Click [here](https://git-scm.com/docs) for even more information about git commands

---


