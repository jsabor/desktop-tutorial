Push local file/project into Git
Create new project and initiate it with Git

```javascript
git init my_repo_path
```

Change direct to my_repo_path

```javascript
cd my_repo_path
```

Add gitignore and readme files, sample git ignore here -> https://gist.githubusercontent.com/octocat/9257657/raw/3f9569e65df83a7b328b39a091f0ce9c6efc6429/.gitignore

```javascript
touch .gitignore
touch README.md
```

Add (commit) files

```javascript
git add .gitignore README.md
```

Where is this going to live in github

```javascript
git remote add origin https://github.com/jsabor/this-is-my-repo.git
```

Add all changes

```javascript
git add .
```

Commit to git

```javascript
git commit -m "First commit"
```

Push changes to git

```javascript
git push -u origin main
```
