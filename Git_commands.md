# Git Commands

## Set Username
- Here global specify that this username used for all repos.
- Use local for current repo.
```sh
git config --global user.name "name"
```

## Set User Email
```sh
git config --global user.email "email"
```

## Clone
```sh
git clone link_here
```

## Staged
- To add specific file
```sh
git add file_name
```
- To add all files
```sh
git add .
```

## Commit
```sh
git commit -m "massage_here'
```

## Push 
```sh
git push origin main 
```
## Init
```sh
git init
```

## Add origin(repo)
```sh
git remote add origin link_here
```

## Verify origin
```sh
git remote -v
```

## Check branch
```sh
git branch
```

## Rename branch
```sh
git branch -M name_here
```

## Create branch only
```sh
git branch name_here
```

## Create branch and switch
```sh
git checkout -b name_here
```
```sh
git switch -c name_here
```

## Switch existing branch
```sh
git checkout branch_name
```
```sh
git switch branch_name
```

## See unstaged changes
```sh
git diff
```

## See staged changes
```sh
git diff --staged
```
