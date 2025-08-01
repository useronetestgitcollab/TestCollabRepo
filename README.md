## Purpose of this repo

Personal training for using Git in a team environment. I am working simultaneously with two Git users sharing the same remote repository, simulating real-life team scenarios in order to strengthen my skills.


### Exercise 1

I will merge the `feature/AddReadmeContent` branch into `main`, resolving the conflicts that will arise when different contents of the `README.md` file are detected.

### Exercise 2

Let's now try to `rebsae` main onto a branch, to add the contents of said branch to main. 
This content comes from the commit made on `feature/AddRebaseReadmeContent`.
This content comes from the commit made on `main`.

### Exercise 3

The same thing, but this time the branch was rebased onto `main` *before* `main` was rebased onto the branch. 
This is the commit from `main`.
This is the commit from `feature/AddRebase2ReadmeContent`.

### Exercise 4

Testing git reset. The next commit is a dummy one, meant to be deleted, both from local and remote.

### Exercise 5

Testing git revert. The next commit is a dummy one, meant to be reverted, the commit after the next one should be simmilar to this one.

### Exercise 6

This is the commit from main. Two commits are about to be cherry-picked on top of this.
This is the first commit that's going to be cherry-picked on master.
This is the second commit that's going to be cherry-picked on master.

### Exercise 7

This is the first commit that's going to get rebased onto master using interactive rebase.

This is the seccond commit, a dummy one that's going to be skipped during the interactive rebase.

This is the third commit that's going to get rebased onto master using interactive rebase. This commit will become the first one after the rebase.

### Exercise 8

Testing git pull. 

This commit will be kept on local for now. 
The other user will make a commit that's going to be pushed to remote.
Once we run git pull we should see the merge action.

This commit will be pushed to remote.
The other user, who has a commit that's not pushed to remote, will run git pull.
We should see a merge happening afterwards.

### Exercise 9

Testing git pull --rebase.

This commit will be kept local for now.
The other user will make a commit that's going to be pushed to remote.
Once we run git pull --rebase we should see the rebase action.

This commit will be pushed to remote.
The other user, who has a commit that's not pushed to remote, will run git pull --rebase.
We should see a rebase happening afterwards.

### Exercise 10

Testing git pull. The exercise goes as follows:
1) This account makes a commit on main, without pushing it to remote.
2) This account makes a commit on a new branch, pushing it to remote.
3) Being checked out on main, we run git pull origin branch.
4) This is the second user, making a new branch called feature/newBranch and making a commit on it. 
5) After getting pushed to remote, we'll run git pull origin feature/newBranch while being checked out on main.

### Exercise 11

Same exercise, but now we run git pull without any arguments.

Same exercise, this is the commit that's being pushed to remote.


