# Git Commands 



1. Repository Initialization



git init

git clone <repository-url>




2. Checking Status & Logs



git status

git log

git log --oneline




3. Staging & Committing



git add <file-name>

git add .

git commit -m "commit message"




4. Branching



git branch

git branch <branch-name>

git checkout <branch-name>

git checkout -b <new-branch-name>

git branch -d <branch-name>




5. Remote Repository




git remote -v

git remote add origin <repo-url>

git push -u origin main

git pull origin main




6. Merging & Rebase



git merge <branch-name>

git rebase <branch-name>




7. Undo Changes



git reset --hard HEAD

git revert <commit-id>

git checkout -- <file-name>




8. Stashing



git stash

git stash list

git stash apply




9. Tags



git tag

git tag <tag-name>

git push origin <tag-name>




# Real DevOps Workflow Example



git checkout -b feature-login

git add .

git commit -m "Added login feature"

git push origin feature-login
