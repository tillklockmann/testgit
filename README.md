# testgit
# bugfix

playground for git

[git markdown!](https://guides.github.com/features/mastering-markdown/#examples)

### make a new branch

`git checkout -b "feature/branch"`

### do a commit or two and
### push new local branch to remote and set tracking

`git push -u origin feature/xy`

### back to master, merge and push to remote

    git checkout master
    git merge feature/xy

### delete feature branch locally and remote

    git branch -d feature/xy
    git push origin --delete feature/xy
