## Version Control
- Version Control is a system that allows you to revisit various versions of a file or set of files by recording changes.
- version control allows you to revert files or projects to a previous version. 
- Three types of version control Local, Centralized, and Distributed.

Local VC | Centralized VC | Distributed VC
---------|----------------|-----------
One database | One server | creates mirrored repositories
No backup | More knowledge with certain files | CVC with fail-safe


## Git
- Git is a Distributed VC that stores data in a file system made up of snapshots.
- It lets multiple developers wordon the same code.
- Keeps all of your project files in one repository.
- Git is the "recipe" Githum is the "bakery".

## States of files in Git
- Commited
Data is securely stored in a local database

- Modified
File has been changed but not committed to the database

- Staged
Flagged a file’s changed version to be committed in the next snapshot

## Local Repository structure

1. Working Directory: The actual files reside here.
1. Index: The area used for staging
1.  Head: Points to the most recent commit



- $ "git status"- will determine the state of files.

- $ "git add `*`"- will track all files in a repository.

- $ "git commit -m ''"- will commit your added files with a message.

- $ "git push origin master"- will push files.

- $ "git push -f"- will force push all files that you have locally.


[table of contents](https://samuelclark907.github.io/learning-journal/)



