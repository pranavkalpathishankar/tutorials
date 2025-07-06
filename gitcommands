# Git Commands Cheat Sheet

## Initialization

* `git init`  
  Initializes a new Git repository in the current directory.

* `git clone <repository-url>`  
  Clones a remote repository to your local machine.

## Configuration

* `git config --global user.name Your Name`  
  Sets your Git username globally.

* `git config --global user.email you@example.com`  
  Sets your Git email globally.

## Basic Snapshotting

* `git status`  
  Shows the working directory status and staged/unstaged changes.

* `git add <file>`  
  Stages changes in a file for the next commit.

* `git add .`  
  Stages **all** changes in the current directory.

* `git commit -m message`  
  Commits staged changes with a message.

* `git commit -am message`  
  Adds and commits tracked files in one step (skips `git add` for tracked files).

## Branching and Merging

* `git branch`  
  Lists all branches in the repository.

* `git branch <branch-name>`  
  Creates a new branch.

* `git checkout <branch-name>`  
  Switches to another branch.

* `git checkout -b <branch-name>`  
  Creates and switches to a new branch.

* `git merge <branch-name>`  
  Merges the specified branch into the current branch.

* `git rebase <branch-name>`  
  Re-applies commits from current branch onto the given branch.

## Remote Repositories

* `git remote add origin <url>`  
  Adds a new remote repository.

* `git remote -v`  
  Shows remote URLs.

* `git push origin <branch>`  
  Pushes your branch to the remote.

* `git push -u origin <branch>`  
  Pushes and sets the upstream for the branch.

* `git pull`  
  Fetches and merges changes from the remote.

* `git fetch`  
  Fetches changes from the remote but does not merge.

## Undoing Changes

* `git reset <file>`  
  Unstages a file (keeps changes in working directory).

* `git checkout -- <file>`  
  Reverts changes in a file (restores from last commit).

* `git reset --hard`  
  Resets the index and working directory. All changes are lost.

## Logs and Diffs

* `git log`  
  Shows commit history.

* `git log --oneline`  
  Shows a summarized commit history.

* `git diff`  
  Shows unstaged changes.

* `git diff --staged`  
  Shows staged changes.

## Stashing

* `git stash`  
  Saves changes in a stack for later.

* `git stash pop`  
  Applies the latest stash and removes it.

* `git stash list`  
  Lists stashed changes.

## Tagging

* `git tag`  
  Lists all tags.

* `git tag <tag-name>`  
  Creates a new tag.

* `git push origin <tag-name>`  
  Pushes a tag to the remote.

## Deleting

* `git branch -d <branch-name>`  
  Deletes a branch (safe).

* `git branch -D <branch-name>`  
  Deletes a branch (force).

* `git rm <file>`  
  Removes a file from the working directory and staging area.

## Misc

* `git help <command>`  
  Shows help for a specific Git command.
