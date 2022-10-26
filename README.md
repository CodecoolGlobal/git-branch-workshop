# Git Branching Workshop

## Let's get your hands dirty

1. Start by creating a new branch in this repo. 
   * Create the branch on top of `main`.
   * Name the branch using your name and module (example: `zsofi-limbek-pb`)  

2. Create a source code file that prints your name when executed. Commit it and push it.
    
3. Cherry-pick the commit with the alpaca picture from branch `alpaca-pic` to the top of your `firstname-familyname-web` 
 branch and push it.
    
4. Create a new branch according to the following specifications: 
   * Create the branch from your first commit
   * The branch should be named according to this pattern: `git-doc-yourname`
   * Create a file on this branch that explains how to do merge in git. 
   * Then commit the file and push it.
    
5. Modify the file by adding an explanation for rebasing. Commit this change and push it.
    
6. Take a screenshot of the current git tree visual and push it to the `git-doc-yourname` branch.
   * Hint: `git log --all --decorate --oneline --graph`
    
7. Take the commit in the previous point and rebase it on top of your original `firstname-familyname-module` branch 
 (OPTIONAL extra: and squash the two explanation commits together).

8. Merge the 2nd branch (`git-doc-yourname`) into your 1st branch (`firstname-familyname-module`).

9. Create a pull request from your 1st (`firstname-familyname-module`) branch to main.


Credits go to: [Bujdosó Réka](https://github.com/bubumaci/gitws) (@bubumaci)
