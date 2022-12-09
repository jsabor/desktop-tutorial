Set git config user.name and user.email in terminal, who is making the changes
```javascript
git config --global user.name "jsabor"
```
```javascript
git config --global user.email "your email"
```
Clone your repo locally to desktop
```javascript
cd desktop
```
```javascript
git clone <<URL of repo>>
```
Change directory to clone
```javascript
cd <<path of clone>>
```
Create Branch
```javascript
git branch my-branch-name
```
Check if Branch is there
```javascript
git branch --all
```
Change Branch to origin settings (more on this later)
```javascript
git push --set-upstream origin my-branch-name
```
Go to Branch
```javascript
git checkout my-branch-name
```
Check status of Branch
```javascript
git status
```
For testing create empty file
```javascript
touch someFile.md
```
Check file created
```javascript
ls
```
Edit file in editor like VSC and save changes

Add file to branch for next commit, moves it to staging, ready for commit
```javascript
git add someFile.md
```
Commit changes to branch
```javascript
git commit -m "This is the heading for my changes"
```
Push changes for merge
```javascript
git push
```
For merge, check out to the master(main) branch, always have to be on main branch to checkout
```javascript
git checkout master
```
Merge your branch
```javascript
git merge myBranchName
```
Push the merged history to Git
```javascript
git push
```
Delete your branch locally 
```javascript
git branch -d myBranchName
```
