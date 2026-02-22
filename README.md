## 1️⃣ Repository Initialization

git init
Initializes a new Git repository.

git clone
Clones an existing repository.


git clone your-repository-url


## 2️⃣ Checking Status & History

git status
Shows current file status.

git log
Shows commit history.


git log
git log --oneline
Compact commit history.

## 3️⃣ Staging & Committing
git add
Adds a specific file.

git add your-file-name

git add .
Adds all modified files.


git commit
Commits stage changes.

git commit -m "your commit message"
## 4️⃣ Branching

Create Branch
git branch your-branch-name

Switch Branch
git checkout your-branch-name

Create & Switch Together
git checkout -b your-new-branch-name

Delete Branch
git branch -d your-branch-name
## 5️⃣ Remote Repository
Connect Remote
git remote add origin your-repository-url

Push Code
git push -u origin main

Pull Code
git pull origin main
## 6️⃣ Merge Branch

git checkout main

git merge your-branch-name
## 7️⃣ Undo Changes
Reset Hard
git reset --hard HEAD


Revert Commit
git revert your-commit-id
## 8️⃣ Stashing

git stash

git stash apply


