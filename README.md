# My Git Project

> Changed code

## starts a new branch
```
git checkout -b name
```

## check current branch
```
git branch 
```

## swaps back to master branch
```
git checkout master
```

## merge branches, swap to branch you want to merge to
```
git merge (branch to merge to branch you are on)
```

## stash things without commiting if not working yet
```
git stash
```

## to check stashed items
```
git stash list
```

## to show files that are changed in stash
```
git stash show
```

## get stashed items back to branch
```
git stash apply
```

## clear stash when finished with it
```
git stash clear
```

## if you have more than one stash, not good to have more than one
```
git stash apply "stash@{1}"
```

## to get information without auto changing your data, best to use with team
```
git fetch
```

## fix conflicting branches
```
git merge origin/main

set a comment explaining the situation

then git push to synce up all data
```

## delete local branch
```
git branch -d (name)
```

## delete pushed branches
```
click on branch, trashcan branch
```

## reverting to previous commit, will not delete uncommited files
```
git checkout .
```
