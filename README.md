# This is a test Let's see if it will work to see if it will work to see if it will work. Change to the line
# This is a second line added after the commit.
# how to make git commit
 1. git add . , where . signifies all. If you want add just one you can just specify that one file
 2. git status -> this checks if the git is staged or not. Git stages the file by git add before commiting.
 3. git commit -m "text here", where -m stands for message.
 4. git log -> you can see all changes.
 5. git log --oneline see each change in one line.
 6. checkout commit, revert commit, reset commit
 - checkout commit: going back in time and seeing history. Not altering anything. Just checkout master to go to current version.
 - revert commit: Undo/delete particular commit. It doesn't delete log but commits one more log with reverted state.
 - Reset commit: Permanently go back in time. But the codes still hangs around in the editor as uncommited code.
                 If you don't want the code to hang around you cand do git reset ... --hard
 - git revert ... , git checkout ... , git reset ..., git reset ... --hard
 7. you can branch out and then merge back into master.
 - git branch **branch name** (creates branch)
 - git checkout -b **branch name** (creates branch and checks out)
 - git branch -a (see all branches)
 - git checkout **branch name** -> (switch branch)
 - git branch -D **exampleBranch** -> (delete branch without merging)
 - git branch -d **exampleBranch** -> (delete branch after merging)
 - git merge **branch name** (first switch to the branch and then merge)

