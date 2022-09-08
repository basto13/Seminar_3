## test
# **Git Instruction**
## Main commands

## *add changes*
    git add
### The git add command adds a change in the working directory to the staging area.

## *change repository*
    git commit
### save changes to the local repository

    git commit -am
### both add changes in the working directory and save changes to the local repository with a comment

## *track of changes*
    git status
### to display the current status of the local repository, to check whether there are changes that are in the repo's directory but have not yet been added to the repo's index with git add.

## *open commit history*
    git log
    git log --oneline
### git log: displays all of the commits in a repository's history.
### git log --oneline: display the output as one commit per line. It also shows the output in brief like the first seven characters of the commit SHA and the commit message.

## *switch between branches*
    git checkout
    git checkout master
### git checkout: to switch between branches in a repository.
### git checkout master: to refer to the main branch 