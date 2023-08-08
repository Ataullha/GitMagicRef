<!-- # Basic Git Commands

## Initializing a Repository

- `git init`: Initializes a new local Git repository.

## Cloning and Copying

- `git clone [repository_link]`: Clones an existing repository to your local machine.

## Checking Repository Status

- `git status`: Shows the current status of your local repository.

## Adding Changes

- `git add .` or `git add --all` or `git add --A`: Adds all modified and new files to the staging area.
- `git add [file_name.file_extension]`: Adds a specific file to the staging area.
- `git add *.[file_extension]`: Adds files with a specific extension to the staging area.
- `git add *`: Adds new and modified files, excluding deletions, to the staging area.

## Committing Changes

- `git commit -m "message"`: Commits staged changes with a descriptive message.

## Undoing Changes

- `git reset`: Unstages changes from the staging area.
- `git reset HEAD~`: Undoes the last commit, keeping changes in the working directory.
- `git reset --hard`: Discards all changes, including those in the working directory, after the last commit.

## Removing Files and Folders

- `git rm [file_name.file_extension]`: Removes a file and stages the deletion.
- `git rm [file_name] -f`: Forces removal of a file.
- `git rm --cached [file_name.file_extension]`: Removes a file from staging, but keeps it in local storage.
- `git rm -r [folder_name]`: Recursively removes a folder and its contents.

## Branching

- `git branch`: Lists all branches in the repository.
- `git branch [branch_name]`: Creates a new branch with the specified name.
- `git checkout [branch_name]`: Switches to a different branch.

## Merging Branches

- `git merge [branch_name]`: Merges changes from another branch into the current branch.

## Remote Repositories

- `git remote add origin [repository_link]`: Links your local repository to a remote repository.
- `git push origin [branch_name]`: Pushes changes from your local repository to the remote repository.
- `git push origin [branch_name] --force`: Force pushes changes, potentially overwriting remote changes.

## Fetching and Pulling

- `git fetch`: Retrieves changes from a remote repository without merging.
- `git pull origin [branch_name]`: Fetches and merges changes from a remote repository. -->

# Basic Git Commands

## Initializing a Repository

- `git init`: Initializes a new local Git repository.

## Cloning and Copying

- `git clone [repository_link]`: Clones an existing repository to your local machine.

## Checking Repository Status

- `git status`: Shows the current status of your local repository.

## Adding Changes

- `git add .` or `git add --all` or `git add --A`: Adds all modified and new files to the staging area.
- `git add [file_name.file_extension]`: Adds a specific file to the staging area.
- `git add *.[file_extension]`: Adds files with a specific extension to the staging area.
- `git add *`: Adds new and modified files, excluding deletions, to the staging area.

## Committing Changes

- `git commit -m "message"`: Commits staged changes with a descriptive message.

## Undoing Changes

- `git reset`: Unstages changes from the staging area.
- `git reset HEAD~`: Undoes the last commit, keeping changes in the working directory.
- `git reset --hard`: Discards all changes, including those in the working directory, after the last commit.

## Removing Files and Folders

- `git rm [file_name.file_extension]`: Removes a file and stages the deletion.
- `git rm [file_name] -f`: Forces removal of a file.
- `git rm --cached [file_name.file_extension]`: Removes a file from staging, but keeps it in local storage.
- `git rm -r [folder_name]`: Recursively removes a folder and its contents.

## Branching

- `git branch`: Lists all branches in the repository.
- `git branch [branch_name]`: Creates a new branch with the specified name.
- `git checkout [branch_name]`: Switches to a different branch.

## Merging Branches

- `git merge [branch_name]`: Merges changes from another branch into the current branch.

## Remote Repositories

- `git remote add origin [repository_link]`: Links your local repository to a remote repository.
- `git push origin [branch_name]`: Pushes changes from your local repository to the remote repository.
- `git push origin [branch_name] --force`: Force pushes changes, potentially overwriting remote changes.

## Fetching and Pulling

- `git fetch`: Retrieves changes from a remote repository without merging.
- `git pull origin [branch_name]`: Fetches and merges changes from a remote repository.

