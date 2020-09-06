#Practice git

##Commands used
- git init: Create a repository
- git status: Compare working directory. staging area, and current branch
- git add: Add changes from working directory to staging area
- git commit: commit changes from staging area to current branch
- git commit -m "xxx": Commit changes with a message description
- git config: Set or get configuration
- git log: Show the history of the project commits
- git show <commit_id>: Show a single commit
- git diff: Show the difference between commits, the working directory, and the staging area
- git checkout: Check out branch (update HEAD and apply changes to working directory)


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
