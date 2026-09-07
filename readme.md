# Linux and Git Command Cheat Sheet

This cheat sheet contains basic Linux and Git commands that I practiced for Module 1.

## pwd

**Description:** Displays the current working directory.

**Syntax:**

`pwd`

**Example:**

`pwd`

## ls

**Description:** Lists files and directoties in the current directory.

**Syntax:**

`ls`

**Example:**

`ls -la`

The `-l` option displays detailed information, and the `-` option includes hidden files.

## cd

**Description:** Changes the current working directory.

**Syntax:**

`cd directory`

**Example:**

`cd Documents`

To return to the home directory:

`cd~`

## mkdir

**Description:** Creates a new directory.

**Syntax:**

`mkdir directory_name`

**Example:**

`mkdir project`

## touch

**Description:** Creates a new empty file or updates the timestamp of an existing file.

**Syntax:**

`touch filename`

**Example:**

`touch notes.txt`

## cp

**Description:** Copies files or directories,

**Syntax:**

`cp source destination`

**Example:**

`cp notes.txt backup.txt`

##mv

**Description:** Moves or renames files and directories.

**Syntax:**

`mv source destination`

**Example:**

`mv old.txt new.txt`

## rm

**Description:** Removes files or directories.

**Syntax:** 

`rm filename`

**Example:**

`rm old.txt`

Use `rm -r` to remove a directory and its contents.

## git sttatus

**Description:** Shows the current status of the working directory and staging area.

**Syntax:** 

`git status`

**Example:**

`git status`

This command shows modified, staged, and untracked files.

## git add

**Description:** Adds changes to the Git Staging area.

**Syntax:**

`git add filename`

**Example:**

`git add readme.md`

To stage all changed files:

`git add .`

## git commit

**Description:** Records staged changes in the Git repository.

**Syntax:**

`git commit -m "message"

**Example:**

`git commit -m "update readme"

The `-m` option allows you to write a commit message directly in the command.

## git branch

**Description:** Lists, creates, or deletes Git branches.

**Syntax:**

`git branch`

**Example:**

`git branch`

To create a new branch:

`git branch new-feature`

## git switch 

**Description:** Switches between Git branches.

**Syntax:**

`git switch branch_name`

**Example:**

`git switch main`

To creat and switch to a new branch:

`git switch -c new-branch`

## git merge

**Description:** Combines changes from another branch into the current branch.

**Syntax:**

`git merge branch_name`

**Example:**

`git merge feature-branch`

This command is usually run from the branch that will receive the changes.

## git log

**Description:** Displays the commit history of a Git repository.

**Syntax:**

`git log`

**Example:**

`git log --online`

The `--oneline` option displays each commit in a compact format.

