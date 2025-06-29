# git-practice
# 📘 Git Practice Questions with Answers

Welcome! This document contains all the important **Git questions with simple answers** for practice and interview preparation. Use this to revise or explain Git to beginners.

---

## 📌 Table of Contents

1. [What is Git?](#1-what-is-git)
2. [Difference between Git and GitHub](#2-difference-between-git-and-github)
3. [Initialize a Git repository](#3-initialize-a-git-repository)
4. [Clone a repository](#4-clone-a-repository)
5. [Common Git commands](#5-common-git-commands)
6. [Check Git configuration](#6-check-git-configuration)
7. [Stage and commit changes](#7-stage-and-commit-changes)
8. [Check commit history](#8-check-commit-history)
9. [Undo changes](#9-undo-changes)
10. [Working with branches](#10-working-with-branches)
11. [Merging branches](#11-merging-branches)
12. [Git stash](#12-git-stash)
13. [Rebase vs Merge](#13-rebase-vs-merge)
14. [Pull vs Fetch](#14-pull-vs-fetch)
15. [Resolve merge conflicts](#15-resolve-merge-conflicts)
16. [Push code to GitHub](#16-push-code-to-github)
17. [Fork vs Clone](#17-fork-vs-clone)
18. [Create a Pull Request](#18-create-a-pull-request)
19. [Tags in Git](#19-tags-in-git)
20. [Git workflows](#20-git-workflows)

---

1. What is Git?

Git is a version control system that tracks code changes and allows multiple developers to collaborate on the same project efficiently.

2. What is the difference between Git and GitHub?

Git

GitHub

Local tool

Cloud platform for Git projects

CLI based

Web-based GUI

Free/open-source

Owned by Microsoft

3. How do you initialize a Git repository?

git init

It creates a .git directory that tracks changes in your project.

4. How to clone a GitHub repository?

git clone <repo-url>

Clones a remote repository to your local machine.

5. How do you check the current status of your repository?

git status

It shows modified, added, or untracked files.

6. How do you stage all files for commit?

git add .

Stages all changes in the working directory.

7. How do you commit changes?

git commit -m "your message"

Creates a snapshot of staged changes.

8. How do you check commit history?

git log

Displays a log of all previous commits.

9. How to view commit history in short format?

git log --oneline

Shows condensed commit log.

10. How do you see unstaged changes?

git diff

Shows the difference between working directory and staged changes.

11. How do you remove a file from staging?

git reset HEAD <file>

Unstages the file but keeps the changes.

12. How do you undo changes in a file?

git checkout -- <file>

Reverts changes in the working directory.

13. How do you check Git configuration?

git config --list

Shows user name, email, editor, etc.

14. How to configure user details?

git config --global user.name "Your Name"
git config --global user.email "email@example.com"

Sets global username and email.

15. How to list all branches?

git branch

Shows current and other branches.

16. How to create and switch to a new branch?

git checkout -b new-branch

Creates and switches to new-branch.

17. How to switch to another branch?

git checkout main

Switches to main branch.

18. How to merge branches?

git checkout main
git merge dev

Merges dev into main.

19. What is Git stash?

git stash
git stash pop

Temporarily saves and restores uncommitted changes.

20. What is the difference between merge and rebase?

Merge: Creates a new commit combining branches.

Rebase: Rewrites commit history for a cleaner log.

21. What is the difference between git pull and git fetch?

git fetch: Downloads changes.

git pull: Fetch + merges changes.

22. How do you resolve merge conflicts?

Edit conflicted files manually, then:

git add .
git commit

23. How to push code to GitHub?

git remote add origin <repo-url>
git push -u origin main

Adds remote and pushes code.

24. What is the difference between fork and clone?

Fork: Copy repo to your GitHub.

Clone: Copy repo to your local machine.

25. How to create a Pull Request?

Fork a repo

Clone locally

Create new branch

Push and go to GitHub > New PR

26. How to add tags?

git tag v1.0
git push origin v1.0

Marks a specific commit version.

27. What are common Git workflows?

Workflow

Description

Git Flow

Uses develop, feature, release, etc.

GitHub Flow

Short branches, frequent merges

Trunk-based

Direct commits to main/trunk

28. How do you delete a branch?

git branch -d branch-name

Deletes the specified local branch.

29. How to remove remote branch?

git push origin --delete branch-name

Removes a branch from the remote repository.

30. How to rename a branch?

git branch -m old-name new-name

Renames a local branch.

31. How to see remote URLs?

git remote -v

Lists all remotes and their URLs.

32. How to add a remote repository?

git remote add origin <url>

Adds a new remote.

33. How to remove a remote repository?

git remote remove origin

Removes the specified remote.

34. What does HEAD mean in Git?

HEAD points to the latest commit in the current branch.

35. What is the difference between HEAD and ORIG_HEAD?

HEAD: Current branch position

ORIG_HEAD: Last position before a destructive change

36. How to revert a commit?

git revert <commit-id>

Creates a new commit that undoes the changes.

37. How to hard reset to a previous commit?

git reset --hard <commit-id>

Completely removes history after the specified commit.

38. How to soft reset?

git reset --soft <commit-id>

Moves HEAD but keeps changes staged.

39. How to reset index and working directory?

git reset --mixed <commit-id>

Unstages and keeps changes in working directory.

40. What is .gitignore?

File that tells Git which files/folders to ignore.

