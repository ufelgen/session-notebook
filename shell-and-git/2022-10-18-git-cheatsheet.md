# git cheatsheet

## how to create a branch

To avoid messing up the main branch, always create branches for new

- features
- chores
- (bug-/hot-)fixes

1. `git switch -c <new branch name>`
   to create a new branch off of the main branch named "new branch name"

2. done

## work with branches

`git branch`: show all local branches

`git branch -a`: show all local and remote branches

`git fetch`: connect to GitHub, get updated files

## pull request

upon commited changes in a branch, they can be committed to GitHub.

This shows up on the website in a yellow window.

Here you can create a pull request, review the changes, and approve the pull request.

Choose "squash and merge commits" for a single commit message that accompanies this branch merge

## update the local repository

`git pull`: synchronize local repository with remote repository

`git switch main`: switch back to main branch

`git branch -d <new branch name>`: delete branch called "new branch name"
