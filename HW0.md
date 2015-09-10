#Git Basics

###Level 1

####Level 1-1
* git commit
* git commit

####Level 1-2
* git branch bugfix
* git checkout bugfix

####Level 1-3
* git branch bugfix
* git checkout bugfix
* git commit
* git checkout master
* git commit
* git merge bugfix

####Level 1-4
* git branch bugfix
* git checkout bugfix
* git commit
* git checkout master
* git commit
* git checkout bugfix
* git rebase master

###Level 2 Ramping Up

####Level 2-1
* git checkout C4

####Level 2-2
* git checkout C3

####Level 2-3
* git branch -f bugFix HEAD~2
* git branch -f master C6
* git checkout HEAD^

####Level 2-4
* git reset local^
* git checkout pushed
* git revert pushed	

## Hooks
###Post Commit Script
* #!/bin/bash
* start "http://www.google.com"
