# Git Lesson 05 - Branches

## Goal

Understand what a Git branch is and why branches are useful.

## Branch

A branch is a pointer to a commit in Git history.

Example:

```text
A → B → C
         ↑
       master
```

## Multiple Branches

Branches allow different development paths.

```text
A → B → C
         \
          D → E
```

## Why Use Branches?

Branches allow us to develop new features without directly changing the main development line.

Example:

```text
master
feature/data-pipeline
feature/ai-agent
bugfix/login
```

## Important Commands

```bash
git branch
```

Shows existing branches.

```bash
git switch -c feature/test
```

Creates a new branch and switches to it.

```bash
git switch master
```

Switches back to the master branch.

## Mental Model

A branch is a pointer to a commit.

It is not a separate copy of the entire project.

## My Understanding

A branch allows me to create a separate development path from the main project history.
## Branch Experiment

I am currently working on:

```bash
feature/test-branch
```

This change is intentionally made only on the feature branch.