# Case Study: Basic Git Commands and Version Control

## Student Information

- **Name:** Angelo Boreta
- **Course:** BSIT (Bachelor of Science in Information Technology)
- **Section:** Block B - 3rd Year
- **Subject:** Web App Development

---

## Project Description

This project is a case study focused on understanding the foundamentals of version control before working on real client projects.

The primary objective of this activity is to demonstrate proper use of Git commands to track changes, save versions, and review project history.

---

## Built With

- **HTML5** - Structured content layout
- **CSS3** - Custom typography, layout centering, and color styling
- **Git** - Local version control management

---

## Core Git Workflows Demonstrated

This project serves as a practical application of the following fundamental Git commands:

### Part 1: Project Setup

```bash
# Initialize a brand new local repository
git init

# Configure git account variables
git config user.name "username"
git config user.email "email"

# Establish Connection with a Github Repository
git remote add origin github_url # HTTPS/SSH link

# Check github connection
git remote -v
```

### Part 2: Tracking Changes

```bash
# Check repository status
git status

# Add all the files for commit
git add .

# Create first commit
git commit -m "initial project setup"

# Push the project to Github
git push -u origin main

# View commit history
git log
# or
git log --oneline
```

### Part 3: Updating the Project

```bash
# Modifying the webpage by adding changes
git status
git add .
git commit -m "Updated webpage content"
git push
git log --oneline
```

---
