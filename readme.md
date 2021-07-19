# Git Trial from CMD and GitBash

This repository has been made so all of you can try your hand at using Git Bash and feel more familiar with what you are trying to do in the command line.  
Follow these steps:
- `mkdir test`
- `git config user.name '<your username for github>'`
- `git config user.email '<your email for github>'`
- `git clone '<the repo you wish to pull>'`
- `git add '<name of file you want to make sure git should add to the working repository for push/pull>'`
- `git status`
- `git checkout -b '<new branch name>'`
- `git checkout -b '<new branch name>' '<old branch name>'`
- `git commit -m '<personal commit message>'`
- `git push`

If changes are made between the time you clone the repo and you push, you would want to incorporate those changes as well. To do so,
- `git checkout master` (To shift back operations to the master/main branch of your repo)
- `git fetch`
- `git origin/master`

Other important commands to remember
- `git branch` (To see all branches present)
- `git remote` (To see all current remote repositories) (append a -v to see all associated URLs too)
- `git remote add '<short nickname of remote repo>' '<url of remote>'`
