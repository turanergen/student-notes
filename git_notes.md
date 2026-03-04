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


## Git Workflow

The typical Git workflow involves these steps:

### Standard Workflow
1. **Make changes** to your files
2. **Stage changes**: `git add .`
3. **Commit changes**: `git commit -m "Description"`
4. **Push to remote**: `git push`

### Branching Workflow
```bash
# Create a new branch
git branch feature-name

# Switch to the branch
git checkout feature-name

# Or create and switch in one command
git checkout -b feature-name

# List all branches
git branch

# Delete a branch
git branch -d feature-name
Merging Workflow
# Switch to main branch
git checkout main

# Merge feature branch into main
git merge feature-name

# Push merged changes
git push
GitHub Usage
GitHub is a web-based platform for hosting Git repositories.

Connecting to GitHub
# Clone a repository
git clone https://github.com/username/repo-name.git

# Add remote repository
git remote add origin https://github.com/username/repo-name.git

# View remotes
git remote -v

# Push to GitHub
git push origin main
Collaboration Commands
# Pull latest changes from GitHub
git pull

# Fetch changes without merging
git fetch

# Push a new branch to GitHub
git push -u origin branch-name
Best Practices
Write clear, descriptive commit messages
Commit frequently with logical changes
Pull before you push to avoid conflicts
Use branches for new features
Review changes before committing