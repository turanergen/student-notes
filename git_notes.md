# Git Notes

This file contains notes on Git version control.

## Git Basics

Git is a distributed version control system for tracking changes in source code.

### Key Concepts
- **Repository (Repo)**: A project folder tracked by Git
- **Commit**: A snapshot of your code at a specific point in time
- **Branch**: A separate line of development
- **Merge**: Combining changes from different branches

### Basic Git Commands
```bash
# Initialize a repository
git init

# Check status of files
git status

# Add files to staging area
git add filename.txt
git add .  # Add all files

# Commit changes
git commit -m "Your commit message"

# View commit history
git log
git log --oneline
Configuration

# Set your name and email
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

# Check configuration
git config --list