this is my local repo

Method how repo is push to the git 

1.  git add .
2. git commit -m " comment " 
3. git push origin main   


Absolutely! Here's a comprehensive list of Git branch-related commands to help you manage branches like a pro 🚀

🌱 Branch Management Commands
🔍 View Branches
- List all local branches
git branch
- List all remote branches
git branch -r
- List all branches (local + remote)
git branch -a



🌿 Create & Delete Branches
- Create a new branch
git branch <branch-name>
- Delete a local branch
git branch -d <branch-name>     # Safe delete (only if merged)
git branch -D <branch-name>     # Force delete



🔄 Switch & Rename Branches
- Switch to another branch
git checkout <branch-name>
- or (modern syntax):
git switch <branch-name>
- Create and switch to a new branch
git checkout -b <branch-name>
- or:
git switch -c <branch-name>
- Rename current branch
git branch -m <new-name>
🌐 Remote Branch Operations- Push a new local branch to remote
git push -u origin <branch-name>
- Delete a remote branch
git push origin --delete <branch-name>
🔀 Merge & Rebase- Merge another branch into current
git merge <branch-name>
- Rebase current branch onto another
git rebase <branch-name>
🧹 Clean Up- Prune deleted remote branches
git remote prune origin
📌 Tracking & Info- See which remote branch you're tracking
git branch -vv
- Set upstream branch
git branch --set-upstream-to=origin/<branch-name>
Want a cheat sheet image or a visual diagram of branching workflows next? Or maybe a real-world example using main, dev, and feature branches?




  ALL GIT COMMANDS 





  Absolutely! Here's a comprehensive list of commonly used Git commands, each numbered and explained clearly for easy reference:

🧰 Essential Git Commands with Explanations
- git init
Initializes a new Git repository in your project folder.
- git clone <repository-url>
Creates a local copy of a remote repository.
- git status
Shows the current state of the working directory and staging area.
- git add <file>
Adds a file to the staging area (prepares it for commit).
- git add .
Adds all modified and new files in the current directory to staging.
- git commit -m "message"
Commits staged changes with a descriptive message.
- git commit -a -m "message"
Adds and commits all tracked files in one step.
- git log
Displays the commit history.
- git show <commit-id>
Shows details of a specific commit.
- git diff
Shows changes between working directory and staging area.
- git diff <branch1> <branch2>
Compares differences between two branches.
- git branch
Lists all local branches.
- git branch <branch-name>
Creates a new branch.
- git checkout <branch-name>
Switches to the specified branch.
- git checkout -b <branch-name>
Creates and switches to a new branch.
- git merge <branch-name>
Merges the specified branch into the current branch.
- git pull
Fetches and merges changes from the remote repository.
- git push
Uploads local commits to the remote repository.
- git push -u origin <branch-name>
Pushes a branch and sets it to track the remote branch.
- git remote -v
Shows the remote repositories linked to your local repo.
- git fetch
Downloads changes from the remote repo but doesn’t merge.
- git reset <file>
Unstages a file (removes it from staging area).
- git reset --hard <commit-id>
Resets to a specific commit and discards all changes.
- git rm <file>
Removes a file from the working directory and stages the deletion.
- git stash
Temporarily saves changes that are not ready to commit.
- git stash pop
Restores the most recently stashed changes.
- git tag
Lists all tags in the repository.
- git tag <tag-name>
Creates a new tag for the current commit.
- git config --global user.name "Your Name"
Sets your Git username globally.
- git config --global user.email "you@example.com"
Sets your Git email globally.
- git config --list
Displays all Git configuration settings.
- git clean -f
Removes untracked files from the working directory.
- git archive
Creates a zip or tar archive of files from a repository.
- git blame <file>
Shows who made each change in a file and when.
- git cherry-pick <commit-id>
Applies a specific commit from another branch.
- git revert <commit-id>
Creates a new commit that undoes the changes of a previous commit.

Would you like a printable cheat sheet or a visual diagram of these commands next?
