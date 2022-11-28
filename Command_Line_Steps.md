Set git config user.name and user.email in terminal, who is making the changes
`git config --global user.name "jsabor"`
`git config --global user.email "your email"`

Clone your repo locally to desktop
`cd desktop`
`git clone <<URL of repo>>`

Change directory to clone
`cd <<path of clone>>`

Create Branch
` git branch my-branch-name`

Check if Branch is there
`git branch --all`

Change Branch to origin settings (more on this later)
` git push --set-upstream origin my-branch-name`

Go to Branch
` git checkout my-branch-name`

Check status of Branch
` git status`

For testing create empty file
` touch someFile.md`

Check file created
`ls`

Edit file in editor like VSC and save changes

Add file to branch for next commit
`git add someFile.md`

Commit changes to branch
`git commit -m "This is the heading for my changes"`

Push changes for merge
`git push`
