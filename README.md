## 1️⃣ Repository Initialization

```bash
git init

git clone <repository-url>
2️⃣ Checking Status & Logs
Bash

git status

git log

git log --oneline
3️⃣ Staging & Committing
Bash

git add <file-name>

git add .

git commit -m "commit message"
4️⃣ Branching
Bash

git branch

git branch <branch-name>

git checkout <branch-name>

git checkout -b <new-branch-name>

git branch -d <branch-name>
5️⃣ Remote Repository
Bash

git remote -v

git remote add origin <repo-url>

git push -u origin main

git pull origin main
6️⃣ Merging & Rebase
Bash

git merge <branch-name>

git rebase <branch-name>
7️⃣ Undo Changes
Bash

git reset --hard HEAD

git revert <commit-id>

git checkout -- <file-name>
8️⃣ Stashing
Bash

git stash

git stash list

git stash apply
9️⃣ Tags
Bash

git tag

git tag <tag-name>

git push origin <tag-name>
🔥 Real DevOps Workflow Example
Bash

git checkout -b feature-login

git add .

git commit -m "Added login feature"

git push origin feature-login
