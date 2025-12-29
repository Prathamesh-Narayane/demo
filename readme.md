# Basic Git Commands (Windows – VS Code)

This README explains the most commonly used **Git commands** when working in **VS Code on Windows**.

Make sure your project folder (for example: `demogithub`) is open in VS Code.

Open the integrated terminal using:
Ctrl + `

---

## Initialize a New Git Repository

Run this command once inside your project folder:

git init

---

## Check Repository Status

Shows the current status of files (modified, staged, untracked):

git status

---

## Add Files to Staging Area

Add all files:

git add .

Add a specific file:

git add filename.ext

---

## Commit Changes

Commit staged files with a message:

git commit -m "Your commit message here"

Example:

git commit -m "Initial project setup"

---

## View Commit History

View commit history in short format:

git log --oneline

---

## Get Help with Git

General help:

git --help

Help for a specific command:

git commit --help

---

## Notes

- Always check `git status` before committing
- Use meaningful commit messages
- Run Git commands inside your project folder

---

You are now ready to use Git confidently in VS Code on Windows 🚀
