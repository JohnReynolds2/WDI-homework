// 1. git init
// 2. git add file.txt or git add . (all files)
// 3. git commit -m "description of commit"

// 1. git branch local_branch -> git checkout local_branch -> git merge master.
// 2. git reset directory/file.txt
// 3. git reset HEAD --hard
// 4. It seperates commands from the revisions
// 5. You want to reset files back to a previous commit if you get stuck working on a problem and don't know how to undo it.  Going back to the previous commit will give you a fresh start. 

// 1. git branch new_branch
// 2. git checkout new_branch
// 3. You want to use other branches so you can focus on one part of the project and diversify the work.  The master branch is for the final product and you want to avoid pushing to the master unless you know for sure it is going to be part of the code. 

// 1. An example of when to merge a branch into yours is if you are creating a function that depends on some new, updated information from another person working on the project in another branch.  You will want to merge the branch in to yours so you are working with the most updated information. Some times it is better to submit a pull request because you might have added a block of code you think is great but the other person in the other branch needs to 'OK' it before just blindly merging the 2 branches.
// 2. git push origin master (if you are working in the master branch, if not substitute 'master' with 'other_branch_name')
