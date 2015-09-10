Level 1

a)
git commit
git commit

b)
git branch bugfix
git checkout bugfix

c)
git branch bugfix
git checkout bugfix
git commit
git checkout master
git commit
git merge bugfix

d)
git branch bugfix
git checkout bugfix
git commit
git checkout master
git commit
git checkout bugfix
git rebase master

Level 2 Ramping Up

a)
git checkout C4

b)
git checkout C3

c)
git branch -f bugFix HEAD~2
git branch -f master C6
git checkout HEAD^

d)
git reset local^
git checkout pushed
git revert pushed	

Hooks
Post Commit Script
!#/bin/bash
start "http://www.google.com"
