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

<<<<<<< HEAD
This is the first commit that's going to get rebased onto master using interactive rebase.

This is the seccond commit, a dummy one that's going to be skipped during the interactive rebase.

This is the third commit that's going to get rebased onto master using interactive rebase. This commit will become the first one after the rebase.
=======
This is the first commit that's going to get rebased onto master using interactive rebase.
>>>>>>> 2a64384 (First commit used for rebase -i)
