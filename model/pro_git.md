# Getting Stared
## Intalling Git
### Installing on Linux
If you're on RHEL for example, you can use `yum`:
```
$ sudo yum install git-all
```

# Git Tools
Now you'll explore a number of very powerful things that Git can do that you may not necessarily use on a day-to-day basis but that you may need at some point.

## Stashing and Cleaning
Often, when your've been working on part of your project, things are in a messy state and you want to switch branches for a bit to work
on something else.

# Stashing Your Work
If you run `git status`, your can see your dirty state:
```
git status
```
Now you want to switch branches, but you don’t want to commit what
you’ve been working on yet; so you’ll stash the changes. 
```
$ git stash
```

To see which stashes you’ve stored, you can
use `git stash list`:
```
$ git stash list
``
To remove it, you can run `git stash drop` with the name of
the stash to remove:
```
$ git stash drop stash@{0}
```
