# Git branches



## Create a new branch
A new branch can be created in (at least) two ways - either using `branch` or `checkout` command. The former one will also require a second step to check out the new branch.

`git branch <branch_name>`

`git checkout <branch_name>`

or

`git checkout -b <branch_name>`

## Delete a branch
Branches are deleted using command `branch` and argument `-d`. **Please note** that there must not be any uncommited changes!

`git branch -d <branch_name>`

* [Back to start](./README.md)