# Git Commands README

This README provides a quick reference guide for common Git commands to help you manage your version control tasks effectively. Whether you're a beginner or an experienced developer, these commands will assist you in navigating through your Git repositories.

## Table of Contents

- [Getting Started](#getting-started)
- [Basic Commands](#basic-commands)
- [Branching](#branching)
- [Merging](#merging)
- [Collaboration](#collaboration)
- [Undoing Changes](#undoing-changes)
- [Remote Repositories](#remote-repositories)
- [Advanced Topics](#advanced-topics)
- [Troubleshooting](#troubleshooting)

## Getting Started

Before you start using Git commands, make sure you have Git installed on your system. You can download it from [git-scm.com](https://git-scm.com/).

## Basic Commands

- `git init`: Initialize a new Git repository in the current directory.
- `git clone <repository_url>`: Clone a remote repository to your local machine.
- `git add <file>`: Add a file to the staging area.
- `git commit -m "commit message"`: Commit staged changes with a descriptive message.
- `git status`: Display the status of your working directory and staged changes.
- `git log`: View the commit history.
- `git diff`: Show differences between the working directory and the last commit.

## Branching

- `git branch`: List all branches in the repository.
- `git branch <branch_name>`: Create a new branch.
- `git checkout <branch_name>`: Switch to an existing branch.
- `git checkout -b <new_branch_name>`: Create and switch to a new branch.
- `git merge <branch_name>`: Merge changes from the specified branch into the current branch.
- `git rebase <branch_name>`: Reapply commits from one branch on top of another.

## Merging

- `git merge <branch_name>`: Incorporate changes from another branch into the current branch.
- `git merge --no-ff <branch_name>`: Perform a non-fast-forward merge, preserving branch history.
- `git mergetool`: Launch a tool to help resolve merge conflicts.

## Collaboration

- `git remote`: List remote repositories.
- `git remote add <name> <repository_url>`: Add a remote repository.
- `git fetch <remote_name>`: Fetch changes from a remote repository.
- `git pull <remote_name> <branch_name>`: Fetch and merge changes from a remote repository.
- `git push <remote_name> <branch_name>`: Push local commits to a remote repository.
- `git push --tags`: Push tags to a remote repository.

## Undoing Changes

- `git reset <file>`: Unstage changes in a file while preserving the changes.
- `git reset --hard <commit_hash>`: Discard changes and reset to a specific commit.
- `git revert <commit_hash>`: Create a new commit that undoes the changes of a specific commit.

## Remote Repositories

- `git clone <repository_url>`: Clone a remote repository to your local machine.
- `git remote -v`: Display URLs of remote repositories.
- `git push <remote_name> --delete <branch_name>`: Delete a remote branch.

## Advanced Topics

- `git stash`: Temporarily store changes that are not ready to be committed.
- `git cherry-pick <commit_hash>`: Apply the changes of a specific commit to the current branch.
- `git submodule`: Manage Git submodules within your repository.

## Troubleshooting

- `git clean -n`: Preview files that will be removed by `git clean`.
- `git checkout -- <file>`: Discard changes in a specific file.
- `git reset --hard HEAD`: Reset to the last commit, discarding all changes.
- `git log --graph --oneline --all`: Visualize the commit history as a graph.

Remember that this is just a quick reference guide. For more detailed information about each command and its options, you can refer to the official [Git documentation](https://git-scm.com/docs).

Happy coding and version controlling! 🚀👩‍💻👨‍💻
