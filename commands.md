# Git Commands

## Directory Management
- `mkdir git_for_devops` - Create a new directory for Git projects.
- `cd git_for_devops/` - Change to the newly created directory.
- `ls` - List files and directories.

## Initialize Repository
- `git init` - Initialize a new Git repository.

## File Operations
- `touch nibba.txt nibbi.txt` - Create new files.
- `rm nibba.txt` - Remove a file.
- `rm -r *` - Remove all files in the directory.

## Git Status and Information
- `git status` - Check the status of the repository.
- `git log` - View the commit history.
- `git log --oneline` - View a simplified commit history.

## Staging and Committing Changes
- `git add nibbi.txt` - Stage a file for commit.
- `git add .` - Stage all changes.
- `git commit -m "message"` - Commit staged changes with a message.

## Configuration
- `git config --global user.email "email@example.com"` - Set the global email for commits.
- `git config --global user.name "Your Name"` - Set the global username for commits.

## Branch Management
- `git checkout -b branch_name` - Create and switch to a new branch.
- `git checkout master` - Switch to the master branch.
- `git branch` - List all branches.
- `git branch --oneline` - List branches in a simplified format.

## Restore Changes
- `git restore file.txt` - Restore a file to the last committed state.
- `git rm --cached file.txt` - Remove a file from the staging area but keep it in the working directory.

## Merging and Checkout
- `git checkout branch_name` - Switch to an existing branch.
- `git checkout -b new_branch` - Create a new branch and switch to it.

## Miscellaneous
- `vim file.txt` - Open a file in Vim editor.
- `history` - Display the command history.
