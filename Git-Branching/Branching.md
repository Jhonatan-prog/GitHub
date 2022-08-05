## Git Branching 

![Git Branching](https://www.nobledesktop.com/image/gitresources/git-branches-merge.png "Branching")

#### commands

1. git branch (it shows the branch you have)
2. git checkout + BranchName (This command will allow you to surf on all the braches)
3. git checkout -b + New Brach (create a new brach)
4. git diff + BranchName (shows all the lines that have been shanged)

#### Flowing through branches

if you created a new branch(feature branch) and you save new contend on that branch the changes only will be inside the branch; if you call the main branch you won't see the new content there.

#### Merging two branches

1. git merge + BranchName
2. git push -> (shows what you need to write to push your code)

After all the changed have been saves and committed you must use the next command: git push -y origin + BranchName

3. git pull (This one emerge the feature branch with the main)

#### Removing branches
You don't need to use branches that has been moved to the main

1. git branch -d + BranchName (This will enable you to delete an unnecessary branch)

#### Marge conflicts
