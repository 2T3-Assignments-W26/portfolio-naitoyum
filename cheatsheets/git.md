# Git Cheat Sheet

### Initialization

#### config location
* git config --system
* git config --global
* git config

#### name/email:
* git config --global user.name "NAME"
* git config --global user.email "EMAIL"

#### Verifying:
* git config --get user.name
* git config --get user.email

#### default branch:
* git config --global init.defaultBranch main

#### code editor:
* git config --global core.editor "code --wait"
* git config --global core.editor "notepad"

### Staging
* git add .

### Committing
* git commit -m "MESSAGE"

### Status
* git status

### Cloning
* git clone "URL copied from GitHub"

### Pushing/Pulling
* git push origin main
* git pull origin main