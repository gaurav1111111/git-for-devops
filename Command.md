1. Git Configuration
Set your name: git config --global user.name "Your Name"

Set your email: git config --global user.email "youremail@example.com"

Check your configuration: git config --list

2. Repository Initialization
Create a new Git repository: git init

Clone an existing repository: git clone <repository-url>

3. Git Branching
List all branches: git branch

Create a new branch: git branch <branch-name>

Switch to a different branch: git checkout <branch-name>

Create and switch to a new branch: git checkout -b <branch-name>

Delete a branch: git branch -d <branch-name>

4. Git Staging and Committing
Check the status of your files: git status

Add changes to staging: git add <file-name> # For specific files
git add . # For all changes

Commit changes: git commit -m "Commit message"

Amend the previous commit: git commit --amend

5. Viewing Git History
View the commit history: git log

View the commit history in one line: git log --oneline

View the commit history with a graph: git log --graph --oneline

6. Git Remote
Add a remote repository: git remote add origin <repository-url>

View remote repositories: git remote -v

Push changes to the remote repository: git push origin <branch-name>

Pull changes from the remote repository: git pull origin <branch-name>

Fetch updates from the remote repository: git fetch

7. Git Merging
Merge a branch into the current branch: git merge <branch-name>

Resolve merge conflicts:

After resolving conflicts manually, add the resolved files: git add <file-name>
Complete the merge: git commit
8. Git Tagging
Create a tag: git tag <tag-name>

Push tags to the remote repository: git push origin <tag-name>

List all tags: git tag

9. Git Rebase
Rebase your current branch onto another branch: git rebase <branch-name>

Resolve conflicts during rebase:

After resolving conflicts, continue the rebase: git rebase --continue
10. Git Reset
Unstage a file (remove from staging area): git reset <file-name>

Undo the last commit but keep changes in the working directory: git reset --soft HEAD~1

Completely remove the last commit: git reset --hard HEAD~1

11. Git Diff
Show changes between the working directory and staging: git diff

Show changes between staged files and the last commit: git diff --staged

12. Git Clean
Remove untracked files: git clean -f

Remove untracked directories: git clean -fd

13. Git Cherry-pick
Apply a commit from another branch: git cherry-pick <commit-hash>
14. Git Revert
Revert a commit: git revert <commit-hash>
15. Git Stash
Save changes to a temporary stash: git stash

Apply the latest stash: git stash apply

View all stashes: git stash list

Drop a stash: git stash drop <stash-id>

16. Git Checkout
Checkout a specific commit: git checkout <commit-hash>

Checkout a file from a previous commit: git checkout <commit-hash> <file-name>

17. Git Help
Get help with Git commands: git help

Get help for a specific Git command: git help <command>



