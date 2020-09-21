## Merge
Merging  is Git's way of putting together a united history again. The git merge command allows you to take independent lines of development made by a git branch and merge it into a single branch.

Example:- 
We have a new branch feature that is based off the master branch. We now want to merge this feature branch into master.

Using this command we have a new branch feature that is based off the master branch. We now want to merge this feature branch into master.

```
git merge
```


## Checkout
The git checkout command lets you navigate between the branches created by git branch. 


```
git checkout -b
```

## Push
The git push command allows you to send (or push) the commits from your local branch in your local Git repository to the remote repository.

To be able to push to your remote repository, you must ensure that all your changes to the local repository are committed.

```
git push <repo name> <branch name>
```

## Pull 
If you make a change in a repository, GIT PULL  allows others to view the changes. It is used to acknowledge the change that you've made to the repository that you're working on. 

```
git pull 'remote_name' 'branch_name
```

## Remote Add 
  The git remote add command takes two arguments:
  
  A unique remote name, for example, “remote_repo”
 
 A remote URL, which you can find on the Source sub-tab of your Git repo.


```
Example: 

set a new remote

git remote add “Remote name” git@ “URL”

git remote -v

```

