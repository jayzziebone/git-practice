#Practice git

##Commands used
- git init: Create a repository
- git status: Compare working directory. staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: commit changes from staging area to current branch
- git commit -m "xxx": Commit changes with a message description
- git config: Set or get configuration
- git log: Show the history of the project commits
- git branch: List of branches
- git chechout -b <new_branch_name>: Create branch and check it out 

# What is Branch?

A branch is a reference (ref) to a commit. When HEAD points to a branch, it means we are on that branch. If we commit while in a branch, the branch is updated to refer to the new commit.

# What is HEAD?

HEAD is a reference to the current branch or sometimes a commit. Commands like <status>, <log>, and <branch> use HEAD. <git checkout> updates HEAD to ref to a different branch.