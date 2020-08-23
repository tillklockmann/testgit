# gitflow cheatsheet


### make and checkout new feature branch

    git checkout -b "feature/branch"

### do a commit or two and push new local branch to remote and set tracking

    git commit -am 'automatically "add" changes from all known files'
    git push -u origin feature/xy

### back to master, merge and push to remote

    git checkout master
    git merge feature/xy
    git push

### delete feature branch locally and remote

    git branch -d feature/xy
    git push origin --delete feature/xy

[git markdown styleguide](https://guides.github.com/features/mastering-markdown/#examples)