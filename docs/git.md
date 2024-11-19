# Git and GitHub

## Glossary
**Git** - a program to track changes in test files.

**GitHub** - the social and user interface built on top of it.

![Image](../imgs/git_terminology.png)

**Repository** - a project's folder.

**Branch** - a parallel version of a repository.

**Commit** - an individual change to a file (or a set of files).

Resources:
1. [Git glossary](https://docs.github.com/en/get-started/learning-about-github/github-glossary#git)

## Basic operations with repository

### Creation
Create new git repository in current directory:
```bash
git init
```

Clone repository from specified `url` to `path`:
```bash
git clone <url> (<path>)
```

For now, it is more straightforward to create an empty repository online (e.g., on GitHub) and then clone it locally.

### Branches
List all branches in a repository:
```bash
git branch
```

Create a new branch with name `branch_name`:
```bash
git branch <branch_name>
```

Delete a branch (safe version, prevents deletion if there are unmerged changes):
```bash
git branch -d <branch_name>
```

Delete a branch (hard version):
```bash
git branch -D <branch_name>
```

### Staging area and commits
Check status of the repository:
```bash
git status
```

![Image](../imgs/staging_area.png)

Add files or changes:
```bash
git add <file>
```

Restore file to its previous version:
```bash
git restore <file>
```


Resources:
1. [Adding locally hosted code to github](https://docs.github.com/en/migrations/importing-source-code/using-the-command-line-to-import-source-code/adding-locally-hosted-code-to-github).