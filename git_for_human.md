# Git 101: Beginner Cheat Sheet

## 1. Basic Terminal Commands (File & Directory Management)
* `pwd`: Print the current working directory path.
* `mkdir <dir_name>`: Create a new directory.
* `rmdir <dir_name>`: Remove an empty directory.
* `ls`: List all files and folders in the current directory.
* `cd <dir_name>`: Change the current directory to a specified path.
* `touch <file_name>`: Create a new empty file.
* `cat <file_name>`: Concatenate and display the content of a file.


## 2. Git Basics & Inspection (Local Workflow)
* `git init`: Initialize a new local Git repository in the current directory.
* `git status`: Show the working tree status and untracked/modified files.
* `git diff`: Compare and show changes between current modifications and the last commit.
* `git add <file_name>`: Move a specific file to the staging area to start tracking.
* `git add .`: Add all modified and new files to the staging area at once.
* `git commit -m "<message>"`: Save a snapshot of staged changes with a descriptive message.
* `git log`: Display the history of all commits made in the repository.

## 3. Undo Changes & Mistakes (Save Your Life)
* `git restore <file_name>`: Discard local changes in a file and restore it to the last commit status.
* `git commit --amend -m "<new_message>"`: Modify and overwrite the comment of the most recent commit.
* `git revert <hash>`: Create a new commit that undoes the changes of a specific past commit.

## 4. Git Branching, Merging & Stashing
* `git branch`: List all local branches and highlight the current branch.
* `git branch <new_branch_name>`: Create a new independent development timeline (branch).
* `git switch <branch_name>`: Switch the current working environment to a specified branch.
* `git checkout <branch_name>`: Standard older command used to switch branches or restore files.
* `git merge <branch_name>`: Combine changes from a specified branch into the current branch.
* `git branch -d <branch_name>`: Delete a specified branch safely after it has been merged.
* `git stash`: Temporarily save and hide uncommitted changes to clean the working directory.
* `git stash pop`: Restore the most recently stashed changes and remove them from the stash list.

## 5. Git Remote & GitHub (Collaboration)
* `git clone <github_url>`: Copy and download an existing remote repository to your local machine.
* `git fetch`: Download updates and branch names from the remote repository without merging.
* `git pull`: Fetch changes from a remote repository and integrate them into your local workspace.
* `git push`: Upload local repository commits to a remote server like GitHub.
* `git remote -v`: List all remote connections and their corresponding URLs.

## 6. Terminal Controls
* `q`: Quit or exit from long display pages like git log or git diff.
* `Ctrl + C`: Abort the current stuck process or cancel the incomplete command.
