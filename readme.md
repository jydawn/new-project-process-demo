new project process:
1.create a new project

```
mkdir projectname
cd projectname
```

2.init document information
```
npm init -y
```
3.download and install plug-in 
```
npm install express --save
```
4.create .gitignore
```
touch .gitignore
```
5.add no push document to .gitignore
```
echo "node_modules/" >> .gitignore
```
6.create readme.md and describe function
```
touch readme.md
```
7.add the type of js document and excute
```
touch app.js
touch client.js
```
8.add project to git repostories
```
git init
git add .
git status
git commit -m "describe text"
```
9.remote create same project and sync
```
hub create
git remote -v
git push origin master
```
10.remote view
```
hub browse
```