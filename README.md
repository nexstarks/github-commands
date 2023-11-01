# GitHub Commands and Usage

This README provides a basic overview of commonly used Git and GitHub commands. It's intended for beginners and serves as a quick reference.

## Basic Git Workflow
     
    git config --global user.name "Your Name"
    git config --global user.email "your@email.com"`

### Git Configuration
    git clone <repository-url>

### Clone a Repository:
    git checkout -b <branch-name>

### Create a New Branch:
    git checkout -b <branch-name>

### Add Changes:
    git add <file>

### Commit Changes:
    git commit -m "Your commit message"

### Push Changes to GitHub:
    git push origin <branch-name>

### Merge Branches (on main branch):
    git merge <branch-name>

### Delete a Branch:
    git branch -d <branch-name>

## Working with Remotes

### Add a Remote:
    git remote add <remote-name> <repository-url>

### List Remotes:
    git remote -v

### Remove a Remote:
    git remote remove <remote-name>

## Resolving Conflicts

### View Conflicting Changes:
    git diff

### Add Resolved Changes:
    git add <file>

### Commit Resolved Changes:
    git commit -m "Merge conflict resolution"

For more advanced commands, visit this 
[link](https://git-scm.com/docs/git#_git_commands)



