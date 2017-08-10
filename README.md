# GitCommands

### Change Directory
* `cd /driveletter/destinationdirectory`

### Setup UserName and User email globally
##### The username and email set up globally will be used for your commits. This helps set up your name/email private. This has no association with actual git username.
* `git config --global user.name` *"Your Name"*
* `git config --global user.email` *"you@example.com"*

### Clone Repository
* `git clone` *gitRepoUrl*`(eg. https://github.com/abhissha/GitCommands.git)`

### Add changes to commit
##### Add all changes to next commit
* `git add -A`

### Commit Changes
##### Commit all changes locally
* `git commit -m ` *"commit message"*

### Push changes to remote branch
* `git push`

### Branches
##### Display all local branches
* `git branch`

##### Remove local branch
* `git branch -d local_branch_name`

### Merge
##### Merge from other local branch
* `git merge local_branch_name`

##### Resolve conflicts(need to have some mergetool installed)
* `git mergetool`
