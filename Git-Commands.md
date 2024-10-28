
# Git Commands Documentation

## Table of Contents
- [Getting Started](#getting-started)
- [Configuration](#configuration)
- [Creating and Cloning Repositories](#creating-and-cloning-repositories)
- [Basic Workflow](#basic-workflow)
- [Branching and Merging](#branching-and-merging)
- [Remote Repositories](#remote-repositories)
- [Undoing Changes](#undoing-changes)
- [Stashing](#stashing)
- [Viewing History](#viewing-history)
- [Tagging](#tagging)

---

## Getting Started

### Initialize a Git repository
```bash
git init
```
Initializes a new Git repository in your project directory.

### Clone a repository
```bash
git clone <repository-url>
```
Clones an existing repository from a remote server to your local machine.

---

## Configuration

### Set user name
```bash
git config --global user.name "Your Name"
```

### Set user email
```bash
git config --global user.email "you@example.com"
```

### List current configuration
```bash
git config --list
```

---

## Creating and Cloning Repositories

### Create a new local repository
```bash
git init
```

### Clone an existing repository
```bash
git clone <repository-url>
```

---

## Basic Workflow

### Check status
```bash
git status
```
Displays the state of the working directory and staging area.

### Stage changes
```bash
git add <file>
git add .
```
Stages changes to a specific file or all files (using `.`) for the next commit.

### Commit changes
```bash
git commit -m "Commit message"
```
Records changes in the repository with a descriptive message.

### Push changes
```bash
git push origin <branch-name>
```
Sends commits from your local branch to the remote repository.

---

## Branching and Merging

### Create a new branch
```bash
git branch <branch-name>
```

### Switch to a branch
```bash
git checkout <branch-name>
```

### Create and switch to a new branch
```bash
git checkout -b <branch-name>
```

### Merge a branch into the current branch
```bash
git merge <branch-name>
```

### Delete a branch
```bash
git branch -d <branch-name>
```

---

## Remote Repositories

### Add a remote repository
```bash
git remote add <remote-name> <repository-url>
```

### View all remotes
```bash
git remote -v
```

### Fetch changes from a remote
```bash
git fetch <remote-name>
```

### Pull changes from a remote
```bash
git pull <remote-name> <branch-name>
```

### Push changes to a remote
```bash
git push <remote-name> <branch-name>
```

---

## Undoing Changes

### Unstage a file
```bash
git reset <file>
```

### Revert a commit
```bash
git revert <commit-hash>
```

### Reset to a specific commit
```bash
git reset --hard <commit-hash>
```

---

## Stashing

### Stash changes
```bash
git stash
```

### Apply stashed changes
```bash
git stash apply
```

### List stashed changes
```bash
git stash list
```

### Drop a stash
```bash
git stash drop <stash-name>
```

---

## Viewing History

### View commit history
```bash
git log
```

### View commit history with changes
```bash
git log -p
```

### View a summarized commit history
```bash
git log --oneline
```

---

## Tagging

### Create a tag
```bash
git tag <tag-name>
```

### List all tags
```bash
git tag
```

### Push a tag to the remote repository
```bash
git push origin <tag-name>
```

---

## Helpful Tips

- Use `git status` often to keep track of your changes.
- Use `git log --graph --oneline --all` for a graphical view of commits.
- Run `git help <command>` for help on specific commands.

---

```

This Markdown file should serve as a quick reference for common Git commands.