merge

git checkout branch name //you want to merge into 
git merge branch name //you want to merge into the other branch
this way the branch will stay as it was (that we merged into the other branch) but the branch we merged into got the history of that branch too

rebase

git checkout branch name //you want to merge into 
git rebase branch name //you want to merge into the other branch
this way the head of both branches will be at the same commit
