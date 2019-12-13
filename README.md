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

#GIT Y


```shell
git push

git push -u origin feat/mission-page

git checkout -b feat/mission-page__aims
```

#GIT
```shell

1. Checkout bracnh witch was not commit correctly
2. Create/commit branch again with fake change -"comment" 
3. Push
4. Checkout "master"  
5. git merge branch
6. resolve + git add. commit
7. git push

```
#GIT
```shell
git stash
```


#GIT before pull req
```shell
git checkout dev 
git pull
git checkout 'branch to be pull req'
git merge dev
git add .
git commit -m '...'
git push
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



Ako generovat atributy z objectu

Data
```shell
[
 {
   "postcode": "AB1",
   "name": "Aberdeen",
   "ppms": "2408,42",
   "ppsf": "223,75",
   "price_first_buyer": "949,6",
   "ppfp": "17206375",
   "ppb": "122838,75",
   "pppb": "2013,75"
 },
 {
   "postcode": "AB2",
   "name": "Aberdeen",
   "ppms": "2408,42",
   "ppsf": "223,75",
   "price_first_buyer": "949,6",
   "ppfp": "17206375",
   "ppb": "122838,75",
   "pppb": "2013,75"
 },
 {
   "postcode": "AB3",
   "name": "Aberdeen",
   "ppms": "2408,42",
   "ppsf": "223,75",
   "price_first_buyer": "949,6",
   "ppfp": "17206375",
   "ppb": "122838,75",
   "pppb": "2013,75"
 }]
 ```
Import dat

```shell
const data = require('../assets/data/properties.json');
 ```

V render metode 
```shell

let resulttest = [];

 for (var i in data)
    resulttest.push([i, data[i]]);


{resulttest.map((item, i) => item.map((item2, j) =>
 <OutputHouse key={j} x={item2.name} number={item2.ppsf} unit={(this.getUnitCode(this.state.unit))} height={"auto"} width={"90"} ></OutputHouse>

))}
 ```


