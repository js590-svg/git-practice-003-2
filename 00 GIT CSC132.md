


## What is Git?

Git is a version control software. Git is local to your machine. Github is a remote place for a git repo to live.

## Basic Commands

'git init' - creates the .git folder. it initializes the git repository

To remove an initialized repo, we can run 'rm -rf .igt' (or more safely, place the .git folder in the recycle bin)

'git add.' - stages all the files in the current directory

'git commit -m "some message"' - makes the snapshot/saves the current state pf the project


'git status' - tells us information such as

- the branch we are on

- files that have been staged

- files that have been modified since the last commit

- and more


- git push origin (name of the branch)

- git pull origin (name of the branch)