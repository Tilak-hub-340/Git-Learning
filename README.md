# Git Day 1

\## What I am learning



Git tracks changes to files and stores them as commits.





Git has three important areas:

Working Directory → Staging Area → Repository

commands are:

notepad Filename (where you want to change)

git add Filename. file type \[.md, .txt , ...]

git commit -m "meaning full message or commit"

git status





**git status** tells me what state my working directory and staging area are in.
That's perfectly valid. git status is an inspection command, so it can be used whenever you want to inspect the repository.



**commit** is a meaning full message you want see as a history it like heading of the file



**WORKFLOW OF GIT**

&#x20;

Edit

&#x20;↓

git status

&#x20;↓

git diff              ← inspect unstaged changes

&#x20;↓

git add

&#x20;↓

git diff --staged     ← inspect staged changes

&#x20;↓

git commit

&#x20;↓

git status             ← verify clean





**Branch ≠ files.**

A branch is a movable pointer to a particular commit/history.



Git history helps track how a project changes over time.

