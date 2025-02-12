In Intellij, i can directly clone project using file < new < project from version control.

I can also use fetch it's in the branch name right next to our project name.

I can see branches and i have two or more branches i can choose in which i want to commit and push.

So, Git PULL is nothing but git fetch + merge request.

Git fetch - fetches the changes into local repository and then you can merge it in main branch by merge.

Git pull - directly makes the changes in the code.
         - make changes and select from where you want to pull.

Real world scenario.
    1. Fetch and merge latest changes.
    2. Make changes in your branch.
    3. Commit the changes.
    4. Push the code to remote.
    5. Create a pull request.
    7. Merge the code once approved.

Revert a commit - basically we can revert back from any code.
                - if we put code in intellij and commit and if we revert it.
                - code vanishes from intellij if we do local commit. 
                - we can check this is git log.
                - History will be maintained in the git log.

Drop a commit - we can also drop a commit.
                - no traces leave. everything will be removed.
                - no history will be maintained.

Undo a commit - Undoing the commit but the file changes will still be seen in intellij.