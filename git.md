#Git

##One time setup

git config --global user.name "Jackson Reynolds"
git config --global user.email "jackson.c.reynolds22@gmail.com

#Project Setup
 'git init'
 'touch .gitignore'
 Add '*class to the .gitignore and save it.
 'git add.'
 'git commit -m "Initial Commit"'
## 3 step Repeating Commit Process
1. make changes to code
2. Stage related changes
    * git add
3. commit changes with a message
    * git commit -m "message"

## Commands 

* git status   --> shows what files have been staged or commitment
* ls -a        --> shows hidden directories and files
* add          --> adds a file to the stage
* add .        --> adds most recent file changed if more than one don't work
* rm --cached  --> removes a file from the stage
* git commit -m "Present tense description of what changed"
* git log      --> enter to move down, q to quit(shows history of commits)
* git checkout --> filename   -> discard changes

##Problems
* commit without -m -> Use Esc :Wq to quit Vim
* wrong message --> git commit --amend -m"New Message"
* wrong commit --> git checkout COMMIT_ID

