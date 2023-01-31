# Demo

'first commit'
Description: This repo was made following a youtube video. This is an attempt to properly learn how to use GIT.

'second commit'
testing to see changes on how commits works

## Subheader

"third commit"
this was added locally 
    -- meaning on a code editor(VS Code) and not on github
index.html was created. to commit use 'git commit -m "message" '
    -- -m stands for message and commits need message, usually for why changes were made
        also you can add another -m for a description on github
        the following was used: git commit -m "Added index.html & updated README" -m "description"

        4th

## Local Development (Feature 01)
    --checking to see if another branch was made.
1. git line commands
        git checkout -b brachNAME   //Creates a new branch
        git checkout main       // changes back to main branch, can replace main with another branch name 
        git diff branchNAME     //sees the difference between branchs with your main branch
        git merge branchNAME    //merges the branches together
        git branch -d branchNAME //Deletes the branch
        git commit -am "commit name"    // adds and commits only works formodified files

## Undoing
    -- undoing adds and commits

1. git line commands

git reset fileNAME        // resets the staged files (files that were done with git add). you can also just use "git reset " for entire repo
git reset HEAD~1          // HEAD points to the last commit so ~1 point to one futher so it forgets the last commit
git log                 // shows your commits
git reset (commit ##)   // each commit has a unique #, you can rest up to that point, this just stages everything from git, changes will sill be on editior
git reset --hard (commit ##)    // this unstages but also completely removes upto that commit ##
