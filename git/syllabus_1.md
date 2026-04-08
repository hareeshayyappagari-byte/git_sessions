✅ 10 DAYS GIT LEARNING PLAN (E2E)


after 10 days

You should be able to:

Create repo
Track changes
Commit professionally
Use branches
Merge code
Resolve conflicts
Work with GitHub
Undo mistakes safely
Recover deleted work
Handle real-time team workflow



# 📅 DAY 1 — Git Basics + Setup + First Commit
## Topics
What is Git
Git vs GitHub
Install / check version
Configure username/email/editor
git init
Working directory / staging / local repo
git status
git add
git commit
git log


## Commands
git --version
git config --global user.name "hari"
git config --global user.email "hari@example.com"
git config --global core.editor "nano"
git init
git status
git add .
git commit -m "Initial commit"
git log --oneline



## Practice
Create folder
Create 2 files
Add + commit
Check log



# 📅 DAY 2 — Track Changes Properly
## Topics
git diff
staged vs unstaged changes
git add <file> vs git add .
commit message best practices
modify / stage / commit cycle
partial staging basics


## Commands
git status
git diff
git diff --staged
git add file1.py
git add .
git commit -m "Added login test validation"


## Practice
Modify 2 files
Stage only 1 file
Commit only that file
Check diff before and after





# 📅 DAY 3 — Branching (Core Topic)
## Topics
What is a branch
Why branches are used
main vs feature branch
create branch
switch branch
list branches
delete branch
branch naming best practices


## Commands
git branch
git checkout -b feature/login
git switch -c feature/cart
git switch main
git branch -d feature/login


## Practice
Create 2 branches
Add different files in each branch
Switch between them
Observe file differences



# 📅 DAY 4 — Merge + Merge Conflicts
## Topics
What is merge
Fast-forward merge
3-way merge
merge feature branch into main
merge conflict
resolve conflict manually
mark resolved + commit merge


## Commands
git switch main
git merge feature/login
git status
git add .
git commit -m "Resolved merge conflict"


## Practice
Create same file change in main and feature
Merge
Trigger conflict
Resolve it manually



# 📅 DAY 5 — GitHub / Remote Repository (Very Important)
## Topics
Local repo vs remote repo
GitHub basics
git remote
add remote
verify remote
change remote URL
SSH vs HTTPS
push first time
pull latest changes
upstream tracking


## Commands
git remote -v
git remote add origin git@github.com:username/repo.git
git remote set-url origin git@github.com:username/repo.git
git push -u origin main
git push
git pull origin main


## Practice
Create GitHub repo
Connect local repo
Push code
Pull latest



# 📅 DAY 6 — Clone + Team Workflow + Pull Requests Concept
## Topics
git clone
clone using SSH / HTTPS
working in existing team repo
feature branch workflow
push feature branch
PR concept (GitHub)
code review flow
why not commit directly to main in team projects


## Commands
git clone git@github.com:username/repo.git
git checkout -b feature/signup
git push -u origin feature/signup
git pull origin main


## Practice
Clone repo into new folder
Create feature branch
Add change
Push feature branch



# 📅 DAY 7 — Undo Changes Safely (Must Know)
## Topics
unstage file
discard local changes
restore file
delete tracked file
remove from Git but keep local
rename/move file
amend last commit

## Commands
git restore file.py
git restore --staged file.py
git rm file.py
git rm --cached secrets.txt
git mv old.py new.py
git commit --amend -m "Updated commit message"

## Practice
Stage wrong file → unstage it
Modify file → discard changes
Rename file with git
Amend last commit message



# 📅 DAY 8 — Revert + Reset + Reflog (Critical Topic)
## Topics
git revert (safe undo)
git reset --soft
git reset --mixed
git reset --hard
HEAD / HEAD~1 / commit hash
when to use revert vs reset
git reflog for recovery
recover lost commit after reset


## Commands
git revert --no-edit <commit_id>
git reset --soft HEAD~1
git reset --mixed HEAD~1
git reset --hard HEAD~1
git reflog
git reset --hard <reflog_commit_id>


## Practice
Make 3 commits
Revert 1 commit
Reset last commit (soft)
Recover using reflog


# 📅 DAY 9 — Stash + Cherry-pick + .gitignore + Tags
## Topics
git stash
stash list / apply / pop / drop
switching branch with unfinished work
git cherry-pick
copy commit from one branch to another
.gitignore
ignore __pycache__, .env, logs, venv
create tag
lightweight vs annotated tags
Commands
git stash
git stash list
git stash apply
git stash pop
git cherry-pick <commit_id>
git tag v1.0
git tag -a v1.1 -m "Release v1.1"
git push origin v1.0
Practice
Make uncommitted changes → stash
Switch branch
Apply stash
Cherry-pick one commit from feature branch
Add .gitignore
Good .gitignore for Python QA
__pycache__/
*.pyc
venv/
.env
.idea/
.vscode/
allure-results/
allure-report/
logs/




# 📅 DAY 10 — Rebase + Squash + Real-Time Team Workflow + Interview Prep
## Topics
What is rebase
merge vs rebase
git rebase main
conflict during rebase
continue / abort rebase
interactive rebase
squash commits
clean commit history
release workflow
hotfix workflow
QA automation team workflow
most asked Git interview questions


## Commands
git rebase main
git rebase --continue
git rebase --abort
git rebase -i HEAD~3
Practice
Create 3 small commits
Use interactive rebase
Squash into 1 clean commit
Rebase feature branch on latest main


## ---------------------------------------------------

✅ TOPICS COVERED E2E IN THIS 10-DAY PLAN

This plan covers almost all practical Git topics you need:

Basics
Git intro
GitHub intro
Setup/config
init
status
add
commit
log
diff
Branching
branch
switch/checkout
delete branch
branch workflow
Collaboration
remote
clone
push
pull
upstream
PR concept
team workflow
Merging
merge
merge conflict
conflict resolution
Undo / Recovery
restore
rm
mv
amend
revert
reset (soft/mixed/hard)
reflog
Productivity
stash
cherry-pick
.gitignore
tags
Advanced
rebase
rebase conflict
interactive rebase
squash commits

✅ BEST LEARNING ORDER (DO NOT CHANGE)

Follow exactly this order:

Basics
Changes
Branches
Merge
Remote/GitHub
Clone + PR flow
Undo small changes
Revert/Reset/Reflog
Stash/Cherry-pick/Tags
Rebase + Team workflow

👉 This order is correct for real projects + interviews

✅ DAILY TIME (Exact)

For each day:

45 min → Learn concepts
45 min → Run commands in terminal
30 min → Break things intentionally
30 min → Fix them
30 min → Write notes + commit to GitHub

👉 Total: 2.5 to 3 hours/day

If busy:

Minimum 90 mins/day
✅ BEST PROJECT TO PRACTICE GIT (for you)

Since you are learning Python + QA Automation, use one real project for all 10 days:

Create one repo:
python_git_practice_qa

Inside it:

tests/
utils/
data/
README.md
.gitignore

Practice all Git topics on this single repo.

✅ What you should build while learning

Use small files like:

test_login.py
test_checkout.py
test_api_users.py
utils/helper.py
README.md

This makes Git learning feel real-time, not dummy.

✅ Most Important Commands (must master 100%)

These are your must-master commands:

git init
git status
git add
git commit
git log --oneline
git diff
git branch
git switch
git checkout -b
git merge
git remote -v
git push -u origin main
git pull origin main
git clone
git restore
git rm
git mv
git revert
git reset --soft
git reset --hard
git reflog
git stash
git cherry-pick
git tag
git rebase
git rebase -i
✅ What NOT to skip

If you skip these, you are not Git-ready:

Branching
Merge conflict resolution
Remote (GitHub)
Revert vs Reset
Reflog
Stash
Rebase basics
✅ My recommendation for you (important)

Because you asked exact plan only:

👉 Do not learn randomly from YouTube
👉 Follow this exact 10-day order
👉 Practice every day in terminal
👉 Push daily to GitHub
👉 Break and recover intentionally

That will make you strong in real-time Git
