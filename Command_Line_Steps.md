Set git config user.name and user.email, quoted, in terminal, who is making the changes.

```javascript
git config --global user.name <<"yourGitUserName">>
```

```javascript
git config --global user.email <<"your email">>
```

Clone your repo locally to your preferred directory, like Documents/GitHub/ or desktop, <<>> denote placeholders.

```javascript
cd desktop
```
Cannot use password, generate Personal Access Token as one option in your Developer Settings

```javascript
git clone <<the URL of repo>>
```

Change to directory of cloned repo.

```javascript
cd <<path of clone>>
```

Create Branch.

```javascript
git branch <<my-branch-name>>
```

Check if Branch is added.

```javascript
git branch --all
```

Change Branch to origin settings (more on this later).

```javascript
git push --set-upstream origin my-branch-name
```

Go to Branch.

```javascript
git checkout <<my-branch-name>>
```

Check status of Branch.

```javascript
git status
```

OPTIONAL For testing only, create empty file.

```javascript
touch <<someFile.md>>
```

OPTIONAL Check file created using list command.

```javascript
ls;
```

Edit file in editor like VSC and save changes.

Add file to branch for next commit, moves it to staging, ready for commit.

```javascript
git add <<someFile.md>>
```

OR to add all changed files use the -A flag.

```javascript
git add -A
```

Commit changes to branch and always include a quoted message.

```javascript
git commit -m <<"This is my message headline for my changes">>
```

Push changes for merge.

```javascript
git push
```

For merge, check out to the main branch, always have to be on main branch to checkout.

```javascript
git checkout main
```

Merge your branch.

```javascript
git merge <<my-branch-name>>
```

If your main branch has Pull Request (PR) protection, go to GUI to review. After that (of if no protection is in place), push the merged history to Git.

```javascript
git push
```

Delete your branch locally. After complete, go into GitHub GUI to delete branch.

```javascript
git branch -d <<my-branch-name>>
```
