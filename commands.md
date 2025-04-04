# Git Commands Explained

This document provides detailed explanations for the Git commands included in the presentation slides. Use this file as a reference while working on exercises covering cloning, branching, committing, merging, and resolving merge conflicts in Git and GitHub.

---

## `git clone`
**Description:**  
Clones a remote repository to your local machine so you can work on it.

**Usage:**  
```bash
git clone <repository-url>
```

**Example:**  
```bash
git clone https://github.com/owner/repo.git
```

---

## `git add`
**Description:**  
Adds changes from your working directory to the staging area, preparing them for a commit.

**Usage:**  
```bash
git add <file-name>
```

**Example:**  
```bash
git add exercise.txt
```

---

## `git commit`
**Description:**  
Records staged changes in the repository along with a descriptive commit message.

**Usage:**  
```bash
git commit -m "Your commit message"
```

**Example:**  
```bash
git commit -m "Added initial exercise file"
```

---

## `git branch`
**Description:**  
Lists branches in your repository or creates a new branch. Branches enable you to work on separate features or versions of your code.

**Usage:**  
- To list existing branches:  
  ```bash
  git branch
  ```
- To create a new branch:  
  ```bash
  git branch <branch-name>
  ```

**Example:**  
```bash
git branch feature1
```

---

## `git checkout`
**Description:**  
Switches between branches or restores working tree files from a branch, commit, or tag.

**Usage:**  
```bash
git checkout <branch-name>
```

**Example:**  
```bash
git checkout main
```

---

## `git merge`
**Description:**  
Merges changes from one branch into another. This command integrates the work from different branches.

**Usage:**  
```bash
git merge <branch-name>
```

**Example:**  
```bash
git merge feature1
```

---

## Merge Conflicts
**Description:**  
Merge conflicts occur when changes from different branches conflict. Git marks the conflicting areas in the affected files with:

- `<<<<<<< HEAD`
- `=======`
- `>>>>>>> branch-name`

**Steps to Resolve a Merge Conflict:**
1. Open the conflicted file and review the conflict markers.
2. Edit the file to decide which parts to keep (or merge both sets of changes).
3. Remove the conflict markers.
4. Stage the resolved file:
   ```bash
   git add <file-name>
   ```
5. Commit the merge resolution:
   ```bash
   git commit -m "Resolved merge conflict in <file-name>"
   ```

**Example:**  
```bash
git add exercise.txt
git commit -m "Resolved merge conflict in exercise.txt"
```

---

## `git status`
**Description:**  
Shows the current status of your working directory and staging area (e.g., which files are staged, modified, or untracked).

**Usage:**  
```bash
git status
```

---

## `git log`
**Description:**  
Displays a history of commits in the repository.

**Usage:**  
```bash
git log
```

---

## `git pull`
**Description:**  
Fetches changes from the remote repository and merges them into your local branch.

**Usage:**  
```bash
git pull origin <branch-name>
```

**Example:**  
```bash
git pull origin main
```

---

## `git push`
**Description:**  
Uploads your local commits to the remote repository.

**Usage:**  
```bash
git push origin <branch-name>
```

**Example:**  
```bash
git push origin feature1
```