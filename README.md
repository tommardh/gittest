# Test file in gittest

Update made in mybranch

first change
second change
third change
fourth change
fifth change
sixth change
seventh change
eighth change
ninth change
tenth change

## Learnings

### Create a new branch, push and rebase changes in main branch to new branch

1) Create a new branch

`git branch rebasetest`

2) Switch to new branch

`git checkout rebasetest`

3) Push local changes first time

`git push -u origin rebasetest`

4) Push next time

`git push`

5) Rebase from master (be on new branch)

`git rebase master`

6) Push local updates to remote branch

`git puch --force`

**Note:** Works only if you know that noone else has worked on the branch

Sources:

- https://jeffkreeftmeijer.com/git-rebase/ 
- https://stackoverflow.com/questions/56125354/git-push-after-rebase

### Merge back to master

1) Go back to master branch

`git checkout master`

2) Merge from branch

`git merge mybranch`

### How to move unpushed committed changes on master to a new branch

1) Create new branch with your changes.

`git checkout -b mybranch`

2) Push new branch code on remote server.

`git push origin mybranch`

3) Checkout back to master branch.

`git checkout master`

4) Reset master branch code with remote server and remove local commit.

`git reset --hard origin/master`

Source: https://stackoverflow.com/questions/5066041/moving-committed-but-not-pushed-changes-to-a-new-branch-after-pull


