---
title: Git. Version control.
date: 2022-10-08
math: true
image:
  placement: 2
  caption: ''
---

**Git** (pronounced "git") is a distributed version control system. The project was created by Linus Torvalds to manage the development of the Linux kernel, the first version was released on April 7, 2005. To date, he is supported by Junio Hamano.

### Git Basics

Every time you save your work, Git creates a commit. A commit is a snapshot of all files at a particular point in time. If a file has not changed from one commit to the next, Git uses the previously saved file. This design is different from other systems that keep the initial version of the file and keep a record of changes over time.
Commits create links to other commits, forming a development log graph. You can revert code to a previous commit, check how files have changed from one commit to the next, and view details about where and when changes were made. Commits are identified in Git by a unique cryptographic hash of the contents of the commit. Because everything is hashed, it's impossible to make changes, lose information, or corrupt files without Git detection. Version control systems can also provide additional, more flexible functionality. For example, they can support working with multiple versions of the same file, keeping a common change history up to the version branch point and each branch's own change history. In addition, information is usually available about which of the participants, when and what changes were made. Typically, this kind of information is stored in a change log, access to which can be restricted. Unlike classical ones, in distributed version control systems, the central repository is not required.


### Branches

Each developer saves changes to their own local code repository. As a result, there can be many different changes based on a single commit. Git provides the means to isolate changes and then merge them. Branches, which are simplified pointers for doing work, govern this division. After the work created on a branch is completed, that branch can be merged back into the team's main branch (or trunk).


### Files and commits

Files in Git are in one of three states: modified, intermediate, or committed. The first time a file is modified, the changes only exist in the working directory. They are not yet part of the commit or development history. The developer must prepare the modified files for inclusion in the commit. The staging area contains all the changes that need to be included in the next commit. When the developer is happy with the intermediate files, the files are packaged as a commit with a message describing the changes. This commit becomes part of the development history.

Staging allows developers to select changes to files to store in a commit, in order to break large changes into a series of smaller commits. By reducing the scope of commits, it is easier to look through the commit log to find specific changes in a file.


### Git — is not GitHub

Git is a program that needs to be installed and connected to a project in order to manage the version control system. GitHub is a repository site for project version histories: you connect Git, register on GitHub, create an online repository, and transfer files from Git to GitHub.

Git is the most popular version control system and GitHub is an online code repository. Git and GitHub are designed to work together and are therefore often used as a single mechanism for working with a project.

If needed, Git can be replaced with an alternative version control program, and GitHub with another online code repository. Most employers don't need this, as familiarity with other services is time-consuming and inconvenient for many developers.
