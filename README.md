# git-stuff
Useful stuff relating to Git. Here so I can always find it easily and quickly.

## Tokens and password stuff
TODO: Add these details/useful URL


## My aliases
`git config --global alias.unstage 'reset HEAD --'` \
`git config --global alias.unmod 'checkout --'` \
`git config --global alias.last 'log -1 HEAD'` \
`git config --global alias.pub 'push -u origin HEAD'` \
`git config --global alias.setemail 'config user.email jarvisrob@users.noreply.github.com'` \
`git config --global alias.cm 'commit -m'` \
`git config --global alias.co checkout` \
`git config --global alias.cob 'checkout -b'` \
`git config --global alias.aa 'add -A'` \
`git config --global alias.s status` \
`git config --global alias.ss 'status -s'` \
`git config --global alias.dm diff` \
`git config --global alias.ds 'diff --staged'`

## Useful commands

### Getting help
`git help command-want-help-on`

### Configuration after installation
`git config --global user.name "Your Name"` \
`git config --global user.email first.last@url.here` \
`git config --global core.editor "code --wait"`

### Get clone of source code
`git clone https://url.goes.here`

### Changing email to GitHub no-reply
`git config user.email "jarvisrob@users.noreply.github.com"`

### Create and switch to new branch
`git checkout -b new-branch-name`

### Switching branches
`git checkout branch-name`

### Seeing which branch you are on
`git branch`

### Deleting branches
`git branch -d branch-name`

### Checking status of your changes and seeing what has been changed
`git status` \
`git diff` \
`git diff --staged`

### Staging and committing your changes
`git add files.extn` \
`git commit -m "Your commit message"`

### Getting a log of changes, e.g. the last 3 changes
`git log -3`

### Pushing your branch to remote repo (GitHub, VSTS) for the first time
`git push -u origin new-branch-name`

### Pushing and pulling from remote repo (GitHub, VSTS) after that
`git push` \
`git pull`

### Merging master into your current branch
`git merge master`
