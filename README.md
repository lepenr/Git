# Git
How to use git in terminal

cheat sheet wnd wf
```shell
https://www.theodinproject.com/courses/web-development-101/lessons/git-basics
https://www.theodinproject.com/courses/web-development-101/lessons/practicing-git-basics
```

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
pull
```shell
git pull origin master
```

New branch, create and checkout in to new brench
```shell
git checkout -b rl
```

Create a new branch:
```shell
git checkout -b feature_branch_name
Edit, add and commit your files.
Push your branch to the remote repository:
git push -u origin feature_branch_name
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

Update NODE, NPM

```shell
1 npm install -g n
2 npm cache clean -f
3 sudo n stable
4 sudo npm update -g
```
