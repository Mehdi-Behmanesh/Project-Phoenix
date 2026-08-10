# Git Lesson 04 - History & Snapshot

## Goal

Understand Git history and commits.

## View History

```bash
git log --oneline
```

Shows the commit history in a compact format.

## Commit Hash

Each commit has a unique identifier called a commit hash.

Example:

```text
6ecc5c2
```

## Snapshot

A commit represents a snapshot of the project at a specific point in time.

## Important Commands

```bash
git status
```

Shows the current state of the working tree.

```bash
git log --oneline
```

Shows the history of commits.

## Mental Model

Working Directory
        ↓
    git add
        ↓
Staging Area
        ↓
   git commit
        ↓
Commit / Snapshot
        ↓
Git History

## My Understanding

A commit is a saved snapshot of the project at a specific point in time.

Git history allows me to see previous commits and understand how the project changed over time.