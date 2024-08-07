# New Project

This project was created from local system.

Created by Shyam Nakrani.

# Git Basics

git init: Initialize a new Git repository

git add <file>: Stage a file for the next commit

git add .: Stage all changes in the current directory and subdirectories

git commit -m "<message>": Commit changes with a meaningful message
git log: View commit history
git status: Check the status of the repository

# Git Branching

git branch <branch-name>: Create a new branch
git checkout <branch-name>: Switch to a different branch
git checkout -b <branch-name>: Create a new branch and switch to it
git merge <branch-name>: Merge changes from another branch
git branch -d <branch-name>: Delete a branch

# Git Remote

git remote add <name> <url>: Add a remote repository
git fetch <remote>: Fetch changes from a remote repository
git push <remote> <branch>: Push changes to a remote repository
git pull <remote> <branch>: Pull changes from a remote repository
git remote -v: List all remote repositories

# Git Undo

git reset <commit>: Reset the current branch to a specific commit
git reset --hard: Reset the current branch to the last commit and discard all changes
git checkout -- <file>: Discard changes to a file
git revert <commit>: Revert a specific commit
