# Test file in gittest

first change
second change
third change
fourth change
fifth change
sixth change
seventh change

## Learnings

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


