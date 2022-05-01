# Git Practice Exercise

## What this exercises:
- Cloning repositories
- Creating your own branch
- Adding and committing files to your own branch
- Pushing your branch to a remote repository

## Why is this important
1. Git proficiency is crucial for working with source code in a collaborative way
2. Employers often share that they like students to have some coding skills, including using git
3. By learning to use git, you can collaborate on open source projects as well as share your own
 
## Overview of Directions
1. Clone this repository to your development environment
2. Create a branch named your firstname-lastname. For instance, Grace Hopper would create a branch called grace-hopper
3. Go to index.html and add an `<h1>` element that contains your name.
4. Add and commit your changes.
5. Push your local firstname-lastname branch to GitHub.

## Detailed Instructions for Command Line
1. Open up your terminal application
2. Navigate to your projects directory or wherever you normally add new projects.
3. Clone this repository: `git clone https://github.com/WGU-Cybersecurity-Club/Git-Practice.git`
4. Change directories into your copy of this project `cd Git-Practice`
5. Create a branch in your name. `git checkout -b firstName-lastName` where the first and last names are your first and last name.
6. Run `git status` to double check the new branch is created and you are working inside of it.
7. In your prefered editor, open up `index.html` and add an `h1` tag with your name. Be sure to save your work.
8. Running `git status` should show that you have uncommitted changes in `index.html`
9. Running `git diff` should show the changes that you have made to any files.
10. Run `git add index.html` to add the changes `index.html`
11. Run `git commit -m "adding my changes to index.html"`
12. Run `git push -u origin firstName-lastName`
13. In your browser, navigate to this repository on GitHub and double check to make sure your branch is pushed.

## Congratulations, you should be able to see your work on GitHub now!