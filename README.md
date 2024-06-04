# Peto's Web Bible

## Description

Hey, Peto here. This is a document I've been constantly writing for the past few months that condenses web-related information across the different programming languages, markup languages, frameworks, among others.

This "handbook" aims to:

- Be easy to read and comprehend, saving you time from checking the documentation of each language.
- Create consistency within the different processes, whenever a new project is started or a current project is modified.
- It also serves as a practice markup document for your server.

## Git and GitHub

### Git commands

> `git status`

Checks the status of your project by stating if the branch is up to date, checking if changes are or aren’t staged, listing which files have been added, modified or deleted.

> `git add` (Thanks to [Steffen](https://stackoverflow.com/users/13329399/steffen) for writing this detailed answer on this stackoverflow [question](https://stackoverflow.com/questions/26042390/git-add-asterisk-vs-git-add-period))

- `git add -A` or `git add --all` → Adds everything, so that everything in your folder on disk is represented in the staging area.

- `git add .` → Stages everything but does not remove files that have been deleted from the disk.

- `git add *` → Stages everything but not files that begin with a dot and does not remove files that have been deleted from the disk.

- `git add -u` or `git add --update` → Stages only modified files, removes files that have been deleted from disk, does not add new.

- `git add file1 file2` → Adds only certain files, in this case file1 and file2.

> `git commit`

Creates a new update without pushing into the repository.

- `git commit -m “Commit title” -m “Commit description.”` → Commits with a title and a description.

> `git reset`

Undoes a commit or a staged snapshot.

> `git push`

Pushes the commits into the repository.

- `git push origin master` → Pushes the changes into the specified branch “master”.

> `git remote`

## Linux (Ubuntu)

### Key commands

> `ls`

Command for listing the files of a directory.

- `ls` → Lists the files of the current directory.
- `ls /home/directory` → Lists the files of the specified directory.

> `cd`

Command for changing of directory.

- `cd ..` → Changes to the parent directory (previous directory).
- `cd directory_name` → Changes to the specified directory inside the current directory.
- `cd /home/directory` → Changes to the specified directory.

> `mkdir`

Command for creating a new directory.

- `mkdir directory_name` → Creates a directory named "directory_name" inside the current directory.

> `rm`

Command for removing a specified directory.

- `rm file.html` → Removes `file.html` from the current directory.
- `sudo rm -rf directory` → Runs as admin, -r means recursively, -f means force. Deletes the specified directory.

> `unzip`

Command for unzipping a specific file.

- `unzip file.zip` → Unzips `file.zip` inside the current directory.