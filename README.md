# Git
How to use git in terminal

git init
```shell
git init
```

add file to commit
```shell
git add [filename] 
```


add all files in folder for commit
```shell
git add *
```


need to add remote origin
```shell
git remote add [name of origin] [html link to rep]
```

commit
```shell
git commit -a -m "commit message"
git commit -m "commit message"
```

push
```shell
git push [origin name] [branch name]
```

New branch, create and checkout in to new brench
```shell
git checkout -b rl
```

#REACT

create emtpy react app 
```shell
create-react-app 02-react-app
```


If you have any files that are not tracked by Git (e.g. uploaded user content), these files will not be affected.

I think this is the right way:
```shell
git fetch --all
```
Then, you have two options:
```shell
git reset --hard origin/master
```

