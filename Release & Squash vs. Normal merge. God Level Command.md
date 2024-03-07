# Release Merge
- Used to merge the release branch to the main branch. The release branch is forked of the dev branch. This branch is merged with main once it is ready to release. release branch can be created as follows: git checkout -b release/version number here.

# Squash Merge
- Squash merge merges branches and condenses(squashes) the commit history of the merged branches.
- This means that when we merge branches, we will not add each commit from the branch(feature) that was being worked on to the main branch. Instead  all the file changes will be added to a single new commit on the main branch.
- The difference between this and a normal merge is that a normal merge will give you a commit history, while squash merge will not.

# git rebase -i
- i stands for interactive probably. Creates a list of the commits to be rebased. Allow the user edit the list before rebasing.
- Rebasing basically combines commits, and changes commit history.
# Fork
- A is a copy of an existing repository where the new owner disconnects the code from previous committers.
- It creates a completely independent copy of a git repository.
