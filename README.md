# Git Beginner Guide

Welcome to the Git Beginner Guide! This guide provides a brief overview of Git and the most common commands you'll use as a beginner.

---

## What is Git?

**Git** is a distributed version control system that helps you track changes in your code, collaborate with others, and manage your project history.

---

## Common Git Commands

### 0. **Install**

[install GIT](https://git-scm.com/downloads)

You may use VS code with a extension `Git Graph`.

### 1. **Setup**

```sh
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
```

### 2. **Start a Repository**

```sh
git init                # Initialize a new Git repository
git clone <url>         # Clone an existing repository
```

### 3. **Basic Workflow**

```sh
git status              # Show changed files
git add <file>          # Stage a file
git add .               # Stage all files
git commit -m "Message" # Commit staged changes
git log                 # View commit history
```

### 4. **Branching**

```sh
git branch              # List branches
git branch <name>       # Create a new branch
git checkout <name>     # Switch to a branch
git checkout -b <name>  # Create and switch to a new branch
```

### 5. **Merging and Rebasing**

```sh
git merge <branch>      # Merge a branch into current branch
git rebase <branch>     # Reapply commits on top of another base tip
```

### 6. **Remote Repositories**

```sh
git remote -v           # Show remotes
git push                # Push changes to remote
git pull                # Fetch and merge from remote
git fetch               # Fetch changes from remote
```

### 7. **Undoing Changes**

```sh
git checkout -- <file>  # Discard changes in a file
git reset HEAD <file>   # Unstage a file
git revert <commit>     # Create a new commit that undoes a commit
```

---

## Useful Tips

- Use `git status` often to see what’s going on.
- Commit often with clear messages.
- Use branches for new features or fixes.
- Always pull before you push to avoid conflicts.

---

## More Resources

- [Git Official Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com/)
- [Atlassian Git Tutorials](https://www.atlassian.com/git/tutorials)

Happy coding!
