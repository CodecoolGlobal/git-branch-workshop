To merge branches locally, use git checkout to switch to the branch you want to merge into. This branch is typically the main branch. Next, use git merge and specify the name of the other branch to bring into this branch.

<h3>How to rebase:</h3>
Go to the branch in need of rebasing.
Enter git fetch origin (This syncs your main branch with the latest changes)
Enter git rebase origin/main (or git rebase origin/master if your main branch is named master )
Fix merge conflicts that arise however you see fit.