# Practice git

HEAD -> firstbranch : HEAD is a reference to the branch and commit we are looking at right now.


## Commands used
- git init: Create a new git repository
- git status: Compare working directory. staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: commit changes from staging area to current branch
- git commit -m "xxx": Commit changes with a message description
- git config: Set or get configuration
- git log: Show the history ("aka log") of the project commits
- git show <commit_id>: Show a single commit
- git diff: Show the difference between commits, the working directory, and the staging area
- git checkout: Check out a branch (Update HEAD and apply changes to working directory)
- git checkout <branch_name>: Check out (switch to) branch_name. Check out branch (update HEAD and apply changes to working directory)
- git chechout -b <new_branch_name>: Create branch and check it out 
- git branch: List of branches
- git branch -c <branch_name>: Create a branch
- git merge: Merge changes from different branches
- git stash: Stash (save) changes from working directory
- git stash list: List stashes
- git stash pop: Apply stashed changes to working directory

# Other Commands for show, log and diff

- git log <branch_name> or <commit_id> : Show the history of the project commits from that commit or the ref or the branch_name
- git log --all: Show history of the commits of all branches
- git log --author "<author_name>": Show history of commit by the author
- git log --oneline: Show history of commit in one liner (simplified format)
- git log --oneline --graph --all: Show history of all Commit in a graph simplified format
- git diff <commit_id>: Show differences between Working directory and <commit_id>
- git diff --cached: Show the differences between staged files and HEAD
- git log --oneline --all: Show history of all branches in simplified format
- git diff <commit_id>..<commit_id>: show the differences between two commit
- git diff --cached <commit_id>: Show the difference between staged file and a <commit_id>


## Merging

Merging means to bring changes from one branch to another

- a fast-forward merge happens when the target branch was branched from the current one, and there are no new changes to the current branch since then.
- An Automatic merge happens when the two histories have diverged, but git is able to reconcile them into one set of changes. This creates a new commit on the current branch.

# What is Branch?

A branch is a reference (ref) to a commit. When HEAD points to a branch, it means we are on that branch. If we commit while in a branch, the branch is updated to refer to the new commit.

# What is HEAD?

HEAD is a reference to the current branch or sometimes a commit. Commands like <status>, <log>, and <branch> use HEAD. <git checkout> updates HEAD to ref to a different branch.
