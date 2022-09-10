<h1> Git Instruction</h1>

![Git symbol](git.jpeg)

<h2> Main commands</h2>

## *create Git repository*

    git init
<p>This command creates an empty Git repository - basically a .git directory with subdirectories for objects , refs/heads , refs/tags , and template files.</p>

## *add changes*
    git add
<p>The git add command adds a change in the working directory to the staging area.</p>

## *change repository*
    git commit
<p>save changes to the local repository</p>

    git commit -am
<p>both add changes in the working directory and save changes to the local repository with a comment</p>

## *track of changes*
    git status
<p>to display the current status of the local repository, to check whether there are changes that are in the repo's directory but have not yet been added to the repo's index with git add.</p>

## *open commit history*
    git log
    git log --oneline
<p><strong>git log</strong>: displays all of the commits in a repository's history.<br>
<strong>git log --oneline</strong>: display the output as one commit per line. It also shows the output in brief like the first seven characters of the commit SHA and the commit message.</p>

## *switch between branches*
    git checkout
    git checkout master
<p><strong>git checkout</strong>: to switch between branches in a repository.<br>
<strong>git checkout master</strong>: to refer to the main branch</p> 

## *compare commits*
    git diff
<p>show changes between commits, commit and working tree, etc.</p>

## branching

<p>In Git, a branch is a new/separate version of the main repository.</p>

    git branch
    git branch --list --all
<p>If <strong>--list</strong> is given, or if there are no non-option arguments, existing branches are listed; the current branch will be highlighted in green and marked with an asterisk.</p>

    git branch <branch_name>
<p>to create new branch command</p>

<p>with a <strong>-d</strong> or <strong>-D</strong> option branch will be deleted. You may specify more than one branch for deletion</p>

## *merging*

    git merge <branch_name>

<p>Join two or more development histories together.</br> Incorporates changes from the named commits (since the time their histories diverged from the current branch) into the current branch.</p> 
