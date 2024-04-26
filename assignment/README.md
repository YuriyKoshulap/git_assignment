a. What is an issue?
An Issue in GitHub is a bug tracker for a project which has its own section in every repository.

b. What is a pull request?
A pull request is a proposal to merge a set of changes from one branch into another.

c. How do I open up a pull request?

git pull origin branch-name

or

git pull origin main

d. Give me a step by step guide on how to add someone to your repository.
1. Navigate to Your Repository
2. Access Repository Settings
3. Manage Access or Collaborators
4. Choose Access Level
5. Confirm and Save Changes

e. What is the difference between git and GitHub?
Git is a version control system used for tracking changes in code, while GitHub is a web-based platform built around Git, providing hosting, collaboration, and project management tools for code repositories.

f. What does git diff do?
git diff shows the differences between changes made to files in the working directory and the staging area.

g. What is the main branch?
The main branch, often named "master" or "main," serves as the primary line of development in a Git repository, typically reflecting the most stable version of the project.


h. Besides our initial commit if it is a new repository, should we directly push our changes directly into the main branch?

no. It's generally recommended to avoid pushing changes directly to the main branch and instead create a new branch for feature development or bug fixes, then merge them into the main branch through a pull request after review.