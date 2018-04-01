# git-stuff
Useful stuff relating to Git. Here so I can always find it easily and quickly.

## Tokens and password stuff



## My aliases



## Useful commands

### Getting help
`git help command-want-help-on`

### Configuration after installation
`git config --global user.name "Your Name"`
`git config --global user.email first.last@readify.net`
`git config --global core.editor "notepad.exe -multiInst -nosession"`

### Get clone of Project Batman source code
`git clone http://url.goes.here`

### Create and switch to new branch
`git checkout -b new-branch-name`

### Switching branches
`git checkout branch-name`

### Seeing which branch you are on
`git branch`

### Deleting branches
`git branch -d branch-name`

### Checking status of your changes and seeing what has been changed
`git status`
`git diff`
`git diff --staged`

### Staging and committing your changes
`git add files.extn`
`git commit -m "Your commit message"`

### Getting a log of changes, e.g. the last 3 changes
`git log -3`

### Pushing your branch to VSTS for the first time
`git push -u origin new-branch-name`

### Pushing and pulling from VSTS after that
`git push`
`git pull`

### Merging master into your current branch
`git merge master`

