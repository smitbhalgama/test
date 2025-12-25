# =========================
# BASIC SETUP
# =========================
git config --global user.name "Your Name"
git config --global user.email "you@email.com"
git config --list

# =========================
# REPOSITORY
# =========================
git init
git clone <repo_url>

# =========================
# STATUS & INFO
# =========================
git status
git log
git log --oneline
git diff
git diff --staged
git show <commit_id>

# =========================
# ADD & COMMIT
# =========================
git add <file>
git add .
git commit -m "message"
git commit --amend

# =========================
# BRANCHING
# =========================
git branch
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
git switch <branch_name>
git merge <branch_name>
git rebase <branch_name>
git branch -d <branch_name>

# =========================
# REMOTE
# =========================
git remote -v
git remote add origin <repo_url>
git push origin main
git push -u origin main
git pull
git fetch

# =========================
# RESET & UNDO
# =========================
git reset <file>
git reset --soft HEAD~1
git reset --hard
git revert <commit_id>
git checkout -- <file>

# =========================
# FILE OPERATIONS
# =========================
git rm <file>
git mv old_name new_name
git clean -fd
git blame <file>

# =========================
# STASH
# =========================
git stash
git stash list
git stash apply
git stash pop
git stash drop

# =========================
# TAGS
# =========================
git tag
git tag v1.0
git tag -d v1.0
git push origin v1.0

# =========================
# SEARCH & FILTER
# =========================
git grep "text"
git log --grep="text"
git log --author="name"
git log --stat

# =========================
# ADVANCED / RECOVERY
# =========================
git cherry-pick <commit_id>
git reflog
git fsck
git bisect start
git bisect good
git bisect bad
git bisect reset

# =========================
# GIT BASH (LINUX)
# =========================
ls
cd <folder>
pwd
mkdir <folder>
rm -rf <folder>
cp <src> <dest>
mv <old> <new>
touch <file>
clear
