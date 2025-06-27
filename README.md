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

## 1. What is Git?
Git is a **version control system** that tracks changes in code and allows multiple developers to collaborate efficiently.

---

## 2. Difference between Git and GitHub
| Git        | GitHub                        |
|------------|-------------------------------|
| Local tool | Cloud hosting platform for Git |
| CLI based  | Web-based GUI for repositories |
| Free/open-source | Owned by Microsoft         |

---

## 3. Initialize a Git repository
```bash
git init
## 1. What is Git?
Git is a **version control system** that tracks changes in code and allows multiple developers to collaborate efficiently.

---

## 2. Difference between Git and GitHub
| Git        | GitHub                        |
|------------|-------------------------------|
| Local tool | Cloud hosting platform for Git |
| CLI based  | Web-based GUI for repositories |
| Free/open-source | Owned by Microsoft         |

---

## 3. Initialize a Git repository
```bash
git init
Creates a .git folder to start tracking your project.

4. Clone a repository
bash
Copy
Edit
git clone <repo-url>
Downloads the full repository from GitHub to your local machine.

5. Common Git commands
Command	Description
git status	See current changes
git add .	Stage all changes
git commit -m "msg"	Commit changes with message
git log	View commit history
git diff	Show unstaged changes

6. Check Git configuration
bash
Copy
Edit
git config --list
Shows user name, email, and editor settings.

7. Stage and commit changes
bash
Copy
Edit
git add .
git commit -m "Added feature"
Stages all files and commits with a message.

8. Check commit history
bash
Copy
Edit
git log --oneline
Shows a concise list of commits.

9. Undo changes
Unstage file:

bash
Copy
Edit
git reset HEAD <file>
Undo file change:

bash
Copy
Edit
git checkout -- <file>
10. Working with branches
bash
Copy
Edit
git branch           # List branches
git checkout -b dev  # Create + switch to dev branch
git switch main      # Switch to main
11. Merging branches
bash
Copy
Edit
git checkout main
git merge dev
Merges changes from dev into main.

12. Git stash
bash
Copy
Edit
git stash
git stash pop
Temporarily saves uncommitted changes.

13. Rebase vs Merge
git merge: Creates a new commit combining changes.

git rebase: Moves commits on top of another branch for a cleaner history.

14. Pull vs Fetch
git fetch: Downloads changes without applying.

git pull: Fetch + merge into current branch.

15. Resolve merge conflicts
Edit the conflicting file manually, then:

bash
Copy
Edit
git add .
git commit
16. Push code to GitHub
bash
Copy
Edit
git remote add origin <repo-url>
git push -u origin main
17. Fork vs Clone
Fork: Copy of a repo under your GitHub account.

Clone: Downloads a GitHub repo to your local system.

18. Create a Pull Request
Fork a repo

Clone it, create a new branch

Push changes

Click New Pull Request on GitHub

19. Tags in Git
bash
Copy
Edit
git tag v1.0
git push origin v1.0
Marks a specific point in history (e.g., version release).

20. Git Workflows
Workflow	Description
Git Flow	Feature/Develop/Release/Hotfix branches
GitHub Flow	Short-lived branches, frequent merges into main
Trunk-based	Developers commit to main frequently
