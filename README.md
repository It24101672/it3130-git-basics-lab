# IT3130 Git Basics Lab
## Purpose
This repository demonstrates a basic Git workflow for IT3130.
## Files- HelloWorld.html - a small web page used to practise version control- README.md - project documentation
## Commands practised
## What I learned
Working through this lab helped me understand the three-stage Git workflow. Editing a file only
changes the working directory — Git sees it as "modified" but tracks nothing until I run `git add`,
which moves that snapshot into the staging area. Only `git commit` then saves the staged snapshot
permanently into the local repository's history. I also learned that staging isn't a one-time thing:
every new change to a tracked file has to be re-added before it can be committed, since Git only
commits what's currently staged, not whatever is in the working directory at that moment.

git init, git status, git add, git diff, git commit, git log, git remote, git push