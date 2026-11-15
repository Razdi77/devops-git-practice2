new new new 123456789123456
# Git Commands Reference

This document contains the Git commands used during Git setup and basic repository operations.

## 1. Setup & Config

### 1. git --version
- **What it does:** Checks the installed Git version.
- **Example:**
```bash
git --version
```

### 2. git config --global user.name
- **What it does:** Configures the username used for Git commits.
- **Example:**
```bash
git config --global user.name "Arjun Singh"
```

### 3. git config --global user.email
- **What it does:** Configures the email address used for Git commits.
- **Example:**
```bash
git config --global user.email "arjun@example.com"
```

### 4. git config --list
- **What it does:** Displays the current Git configuration.
- **Example:**
```bash
git config --list
```

### 5. git config --global --list
- **What it does:** Displays all global Git configuration settings.
- **Example:**
```bash
git config --global --list
```

---

## 2. Basic Workflow

### 1. mkdir
- **What it does:** Creates a new directory for the Git project.
- **Example:**
```bash
mkdir devops-git-practice
```

### 2. cd
- **What it does:** Changes the current working directory.
- **Example:**
```bash
cd devops-git-practice
```

### 3. git init
- **What it does:** Initializes a new Git repository in the current directory.
- **Example:**
```bash
git init
```

### 4. touch
- **What it does:** Creates an empty file.
- **Example:**
```bash
touch git-commands.md
```

### 5. nano
- **What it does:** Opens a file in the Nano text editor for editing.
- **Example:**
```bash
nano git-commands.md
```

---

## 3. Viewing Changes

### 1. git status
- **What it does:** Shows the current state of the working directory and staging area.
- **Example:**
```bash
git status
```

### 2. git status --short
- **What it does:** Displays a compact summary of repository changes.
- **Example:**
```bash
git status --short
```

### 3. ls
- **What it does:** Lists files and directories in the current location.
- **Example:**
```bash
ls
```

### 4. ls -la
- **What it does:** Lists all files, including hidden files and directories.
- **Example:**
```bash
ls -la
```

### 5. ls .git
- **What it does:** Displays the contents of Git's internal repository directory.
- **Example:**
```bash
ls .git
```

### 6. cat
- **What it does:** Displays the contents of a file in the terminal.
- **Example:**
```bash
cat git-commands.md
```

---

## Key Learning

- Git tracks changes in files and directories.
- `git init` creates a Git repository.
- `git config` configures your Git identity.
- `git status` helps monitor repository changes.
- The `.git` directory stores Git repository metadata and history.
