#### Git Tutorial Notes
- Version Control: Recording Changes
- Easy to revert back to a previous version, track modifications and compare changes
- Local Version Control (LVS) existed on a hard disk, led to Centralized Version Control System (CVCS)-- a single server storing all changes and versions, accessible by multiple clients; hosted on a single server
- A Distributed Version Control systems (DVCS) creates mirrored repositories with data backups can easily be placed on a server to replace lost information
  - Enables the use of various simulatenous workflows
 
 ##### What is Git
 - Snapshots: Saved versions are called commit and references it
 - Local Operations store necessary information, reducing time to fetch history information
 - Tracking Changes: Tracked by Git, detects file corruption or loss of information
 - Loss of Data: Greatly minimizes the possiblity of irreversible damage to files, hard to lost files that are committed
 - State of Content:
  - Committed: Data is stored in a local database
  - Modified: File has been changed but not committed to the database
  - Staged: Flagged a file's changed version to be committed in the next snapshot
 
 ##### History of Git
 - Linux project (circa 2002)
 - DVCS being used was called BitKeeper and a company behind BitKeeper no longer providing access via open source
 - Linus Torvalds, Chief Architect of Linux kernel created Git
 
 ##### Importing
 - $ cd test (switch to the target project's directory)
 - Tracking changes:
  - $ git add #.c
  - $ git add LICENSE
  -$ git commit -m "any message here"
  
  ##### Cloning
  - Clong Command: $git clone https://github.com/test
  - Command leads to the creation of a directory called test which has copies of all versions of all files for the specified project
[x] automatically checks out the newest copy of the project
 
 #### Local Repository Structure
 1. Working directory: Where files live
 1. Index: Used for staging
 3. Head: most recent commit
[x] Check file status: $ git status
  
 1. Tracking and Staging a new file
  -git add file name
 1. $git add*
 1. Commiting a File
  - $git commit -m "made change..."
  - $ git commit -a
  - git push origin master
  
  > Stashing Changes: temporarily removes changes and hides them, giving you a clean workind directory. When you are ready to continue working on the changes-- git stash apply retrieves the hidden changes
 
 
 
  
