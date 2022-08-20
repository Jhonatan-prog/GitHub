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

After all the changed have been saves and committed you must use the next command: git push -u origin + BranchName

3. git pull + BranchName (This one emerge the feature branch with the main)

#### Removing branches
You don't need to use branches that has been moved to the main

1. git branch -d + BranchName (This will enable you to delete an unnecessary branch)

#### Marge conflicts

**Overwriting:**Two same lines of code in different branches (if this happend you won't be able to swicth between branches)

**to solve the overwriting problem:**
1. git stash (This will send your code to a stash which is temporary)
2. git stash list (it will show you a list with the folders stashed)
3. git stash show (to see details of the stash)

**Retrieving Stashed Changes**
1. git stash apply (This one will bring a copy of you work and at the same time will keep a copy on the stash)
2. git stash pop (This will bring your work to your work-space and will delete the copy of the stash)

**Conflict:**The best way to fix a cnflict which is produce because of trying to merge branches is:
1. Fixing your code
2. Fix it with the terminal

#### Undoing

1. git reset + file name(undone what you did)
2. git reset HEAD(last commit) -> (undon the a commit)
    * HEAD~1 (it means instead of just go to the last commit I want to go back one commit further)
3. git log (shows all the commits you've done)
4. git reset --hard + commit id