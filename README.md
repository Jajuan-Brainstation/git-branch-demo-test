# Git Branching Cheatsheet

### Creating a Repo
- Inside of your project folder run `git init`  
- connect it with github

### Daily Work
- `git add .`
- `git commit -m "your message here"`
- `git push -u origin main` (if first commit)

### Checking the status
- git status

## Git Branching

### Create a new branch:
- While on your main Branch Run `git checkout -b <branchname>` to check out a new branch and switch to that branch
- Check to see if you have successfully created the branch and to see if you are currently on that with `git branch` your current branch will have a star(*) next to it
- Run `:q` to exit vim 
- IF: you want to switch back to "main" you can by using `git checkout main`
- After making changes, at anytime you can do the following just like we follow for daily work:
- `git add .`
- `git commit -m "your message here"`
- `git push -u origin <branchname>`
- ***Important** remember that the only on your first push you need to add `git push -u origin <branchname>` each time after you can just Run `git push`

### Merge new branch to master:
After cleaning your work branch, and pushing your changes, you can do the following steps:
1. Run `git checkout main` to switch into your main branch. This is where we want to merge our branch. 
2. Run `git merge <branchname>`
3. Run `git push` to push merged changes to main branch
4. After merging if you want to delete the branch, that you just merged, you can with `git branch -d <branch name>`

