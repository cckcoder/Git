# Learn Git from CS50

## Commond command for git

- git clone
  - this cmd for clone project from reposityry
- git add <filename>
  - this cmd for tell git these file we need to track or make snapshot.

* git commit -m "message"
  - It tell git to save file or snapshot it can refer back to previous change.
* git status
  - To see how status of file, it mean git has track all file already or not
* git push
  - This cmd to upload local or file you just change it to reposityry.
* git pull
  - this cmd for download latest change from reposityry.
* git log, git reflog
  - see git log
* git reset --hard <commit>
  - This commad for rollback to previous commit
* git branch
  - See list of git branch
* git branch <name>
  - Create new branch from master
* git checkout <branch>
  - switch to other branch

## Remote

- git fetch
  - This cmd will download latest commits from Server(Repository)
  - to local(your compouter), it have name "origin/master" (That mean branch from server)

* git merge origin/master
  - it mean you merge local master branch with latest commits also master

# Forks

- Copy base of original to separate version (for your own)

# Pull Requests

