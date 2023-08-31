# GIT Task 1 - Repository Initialization and Version Control
This task is designed to help you gain skills in working with GIT. You will perform various operations individually and document them using screenshots with comments when necessary.

## Table of Contents
- [Task Description](#task-description)
- [Workflow](#workflow)
  - [Part 1: Repository Initialization and First Commit](#part-1-repository-initialization-and-first-commit)
  - [Part 2: Working with Changes](#part-2-working-with-changes)
  - [Part 3: Working with Previous States](#part-3-working-with-previous-states)
  - [Part 4: Working with Tags](#part-4-working-with-tags)
  - [Part 5: Working with the Revert Function](#part-5-working-with-the-revert-function)

## Task Description
This task aims to familiarize you with GIT and its version control capabilities. You will perform various actions within a GIT repository, including initialization, making commits, working with branches, and using tags.

## Workflow

### Part 1: Repository Initialization and First Commit

1. Create a working directory.
2. Initialize the repository in it and customize the config file.
3. Create a working directory with the name `student_name` (replace `name` with your last name).
4. Create 3 project files in the working directory (e.g., `hello_name.rb`).
5. Check the repository status.
6. Index the files.
7. Make the first commit with the comment 'first commit name' (replace `name` with your last name).
8. Make changes to the files.
9. Make a commit of the changes.

### Part 2: Working with Changes

1. Make changes to one of the files (e.g., `file1`).
2. Index the file.
3. Make new changes to `file1`.
4. Check the status.
5. Make a commit.
6. Explain the result.
7. Display the history of the project using `$ git log`.
8. Use the command `$ git log --pretty=oneline` to display the latest commits for 5 minutes.

### Part 3: Working with Previous States of the Repository

1. Revert the state of the files in the working directory to the second commit since the start of the task (use the `git checkout <hash>` command).
2. Revert the state of the files to the latest commit.

### Part 4: Working with Tags

1. Create a tag in the current repository snapshot. Tag name - `V1_name` (where `name` is your last name).
2. Make changes and at least two commits in the current directory.
3. Demonstrate reverting to a tagged repository state.
4. Revert to the last master state.

### Part 5: Working with the Revert Function

1. Make changes to the current state of the working directory.
2. Index the changes.
3. Use the restore command to restore the original state of the files.
4. Make directory state changes.
5. Index and commit.
6. Revert the last commit.
7. Show the log.
