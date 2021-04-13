# gitflow cheatsheet


### make and checkout new feature branch

    git checkout -b "feature/xy"

### checkout for Remote Branches

    git checkout --track origin/xy

### commit changes and push new local branch to remote and set upstream tracking

    git push -u origin feature/xy

### delete feature branch locally and remote

    git branch -d feature/xy
    git push origin -d feature/xy
    
### helpfull links

- [git markdown styleguide](https://guides.github.com/features/mastering-markdown/#examples)
- [git tower tutorial/learn git](https://www.git-tower.com/learn/git/faq/checkout-remote-branch/)
