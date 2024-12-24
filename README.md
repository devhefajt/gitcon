# git
version control system

# git init
Initializes a new Git repository in your project.

# git clone
Copies an existing repository to your local machine.

# git status
Shows the current state of your repository (tracked, untracked, or modified files).

# git add .
Stages changes (new or modified files) for the next commit.

# git commit -m "first commit"
Saves staged changes to the repository with a message.

# git log
Displays the commit history of your repository.

# git branch
Check branch name.

# git branch -M <branch name>
Rename the branch name.

# git checkout <branch name>
Switches to a different branch or restores files.

# git checkout -b <branch name>
To create new branch.

# git checkout -d <branch name>
To delete branch.

# git merge
Combines changes from one branch into the current branch.

# git stash
Temporarily saves uncommitted changes without committing them.

# git stash list
Shows a list of all saved stashes.

# git stash apply
Applies a saved stash to your working directory without removing it from the stash list.

# git remote add
Adds a remote repository to your project.

# git remote remove
Removes a remote repository from your project.

# git push
Uploads local commits to a remote repository.

# git pull
Fetches and merges changes from a remote repository.

# git fetch
Fetches changes from a remote repository without merging them.

# git revert
Creates a new commit that undoes changes from a specific commit.

# git reset --soft
Moves the HEAD to a previous commit but keeps changes staged.

# git reset --mixed
Moves the HEAD to a previous commit and unstages changes (default).

# git reset --hard
Moves the HEAD to a previous commit and discards all changes.

# git restore
Restores specific files to a previous state (alternative to `git checkout` for restoring files).

# git rebase
Moves or combines commits to a new base branch, updating history.

# git rebase -i
Allows you to edit, reorder, squash, or drop commits interactively during a rebase.

# git tag
Creates a tag to mark a specific commit.

# git push origin <tag>
Uploads a specific tag to a remote repository.

# git cherry-pick
Applies changes from a specific commit to the current branch.

# git commit --amend
Edits the most recent commit (message or changes) without creating a new one.

# git config
Sets user information, preferences, or repository-specific settings (e.g., username, email).

# git diff
Shows differences between changes in the working directory, staging area, or commits.

# git filter-branch
Rewrites commit history to modify or remove data in the repository.

# git filter-repo
A faster and safer tool to rewrite Git history (recommended over `git filter-branch`).

# git gc
Cleans up unnecessary files and optimizes the local repository.

# git fsck
Verifies the integrity and validity of the Git repository.

# git bisect
Finds the commit that introduced a bug by performing a binary search through commit history.

# git blame
Shows who made changes to each line in a file, along with the commit details.

# git reflog
Shows a log of all references (e.g., HEAD changes), including commits, checkouts, and resets.

