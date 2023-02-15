# Git_theory


### Note: How to duplicate an existing repository on Github into another repository

1. Create a bare clone of the repository:
`git clone --bare https://github.com/EXAMPLE-USER/OLD-REPOSITORY.git`

2. Mirror-push to the new repository:
`git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git`

3. Remove the temporary local repository you created earlier:
```
cd OLD-REPOSITORY.git
git push --mirror https://github.com/EXAMPLE-USER/NEW-REPOSITORY.git
```

---

## Version control 

Version control is a system that manages changes to documents, software code, or other types of files over time. It allows multiple people to collaborate on a project, keep track of changes, revert to earlier versions, and merge changes made by different contributors. Version control systems provide a history of changes, including who made them and when, making it easier to understand the evolution of a project and to diagnose and fix problems. 

---

## Git

Git is a popular distributed version control system used for tracking changes in source code during software development. 
Git allows multiple developers ot work on the same codebase simlutaneously and track their changes independently.

It also supports branching and merging, which enables developers to experiment with different approaches to coding and then integrate their changes back into the main codebase.


--- 

## What are the benefits of using Git?

1. Collaboration: Allows developers to work on the same code base simultaneously and track their changes
2. Versioning: Git tracks changes to files over time, making it easy to see what changes have been made, who made them, and when. This helps the developers to understand the history of a project and to revert to earlier versions if needed.
3. Branching and merging: Git supports branching, which allows developers to experiment with different approaches to coding without affecting the man codebase. Branches can be merged back into the main codebase when they are ready. 


## Why is Git used in DevOps

Git is a DevOps tool used for source code management. It is free and open-source version control system used to handle small to very large projects efficiently.

Git us used to tracking changes in the source code, enabling multiple developers to work together on non-linear development. 


---

## GitHub

Github is an online platform where developers can **store, share and collaborate on software code.**

It provides tools and features that make it easy to **manage changes to code, track issues and bugs, and collaborate with the other developers.**


## Git vs GitHub

1. Git us a tool used for version control that allows developers to track changes to their code. Git does not require internet connection to work, making it ideal for working offline or in situations where internet connectivity is limited.

2. GitHub on the other hand, is an online platform built around Git that provides a web-based interface for managing Git repositories, making them accessible  to others. 

GitHub provides features like:

- Issue tracking
- Pull request
- Code review tools
