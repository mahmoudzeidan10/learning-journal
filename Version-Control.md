# Version Control
***a system that allows you to revisit various versions of your files  by recording all of your changes.***
 There are three types of version control:
 1- Local Version Control
 2- Centralized Version Control
 3- Distributed Version Control 
 ### what is Git?
 - Git is a Distributed Version Control that stores data in a file system made up of snapshots, so Git creates a snapshot of the file and stores a reference to it.
 - Git mostly relies on local operations because most necessary information can be found in local resources.
 -  Every  change that applied to any file  is tracked by Git, so any change tracked by Git.
 ### The states of the files in Git mainly is three:
 - **Committed**: Data is securely stored in a local database
 - **Modified:**File has been changed but not committed to the database
 - **Staged:** Flagged a file’s changed version to be committed in the next snapshot.
 ### So, How the Work on Git?
The local Git repository has three components:
- Working Directory: The actual files reside here.
- Index: The area used for staging
- Head: Points to the most recent commit
 
![Local Repository Structure](http://practicalseries.com/1002-vcs/01-pages/02-02-concept/02-images/fig-02-01.svg)  
## Now, i will mention **some** of the commands i learned
- you can Check File Status using **[$ git status]**
- you can Track all files in a repository using **[$ git add *]**
