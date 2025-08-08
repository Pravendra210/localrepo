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