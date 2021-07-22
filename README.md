# gitflow cheatsheet


### make and checkout new feature branch

    git checkout -b "feature/xy"

### checkout for Remote Branches

    git checkout --track origin/xy

### push and set upstream tracking (-u) for remote (origin)

    git push -u origin feature/xy

### delete local branch 

    git branch -d feature/xy
  
### delete remote branch

    git push origin -d feature/xy
    
### undo last commit locally

    git reset HEAD~1 or git reset head^ 
    
### [get rid off references to remote branches that have already been deleted](https://www.git-tower.com/learn/git/faq/cleanup-remote-branches-with-git-prune/)

    git fetch --prune origin
    
### revert merge commit

    git revert -m 1 <hash-of-merge-commit>
        
    
### helpfull links

- [git markdown styleguide](https://guides.github.com/features/mastering-markdown/#examples)
- [git tower tutorial/learn git](https://www.git-tower.com/learn/git/faq/checkout-remote-branch/)
