# Checking Your Python (Anaconda) Installation

## Skills in this exercise

1. Use the command line.
2. Fork a repository so you can work on your own copy.
3. Create a "Pull Request" so your changes can be added to the original project.
4. Edit a README.md file.

## Summary of steps to complete

- [ ] Fork this repository so you have your own copy to work on.
- [ ] Clone the repository on your local machine. 
- [ ] Check your version of Python using an Anaconda Prompt and a regular Command Prompt
- [ ] Edit this README.md file on your machine.

## 1. Fork & Clone

* We did this in a previous assignment. Instructions are here: https://github.com/cmcntsh/N6806_Fall2020_DevNotes/blob/master/Projects/002%20-%20Practice%20Using%20Git%20and%20GitHub/README.md

## Edit your README.md file

* In an editor of your choice (i.e. VSCode) edit this README.md file to add the answers requested in the tables.

## Check version

* [ ] Open an Anaconda Prompt.
* [ ] Check your python version by running the code `python --version`
* [ ] Enter your version in the table below.

|   Command   |         Result          |
|     ---     |           ---           |
|`python --version` in Anaconda Prompt  |(enter result here)|

### Link your local repository to the GitHub repository

* [ ] Create a folder in the place you keep material for this class called `myProject`.
* [ ] Go into that folder.
* [ ] Create a file called `myName.txt` and add your name to that file.
* [ ] Save the file and open a terminal window.
* [ ] In your terminal window, `cd` to your `myProject` folder.
* [ ] Run `git init`. (Initializes your folder for tracking changes with git.)
* [ ] Go to your new repository on GitHub and copy the address shown when you click the 'Clone or download' button.
* [ ] Run `git remote add origin [Repository URL goes here]`. (This stores the address for your GitHub repository with your local repository.)
  * (If you accidentally DID initialize your repository with a README, you must do a `git pull origin master` first - to get the README file on your computer - before you'll be able to push.) 

### Push your local code to GitHub

* [ ] Open a terminal window and make sure it is in the directory of `myProject`.
* [ ] Run `git add nameOfMyFile.fileExtension`. (This tells git you want to track changes on that file and adds it to the staging area.)
* [ ] Run `git status`. (This will show what has changed in git.)
* [ ] Run `git diff`. (This shows what code has changed in the file.)
* [ ] Run `git commit -m "The sentence I want associated with this commit message"`. (This prepares the changes to be pushed to GitHub and logs the message you specify.)
* [ ] Run `git push origin master` (Your code is now pushed to GitHub. Be sure to include `origin master`, as this tells GitHub which branch you want to push to, and creates the branch if it doesn't exist yet.)
* [ ] Go to your repository on GitHub and see your updates.

## 2. Fork a repository

### Fork the repository into your own account on GitHub

* [ ] On this current GitHub repository, scroll to the top and look for a button that says `fork`.
* [ ] Click the `fork` button. (This copies all the code from the original repository into a new repository on your own GitHub account.)

### Clone the forked repository to your computer.

* [ ] Go to your forked repository on GitHub. It should appear under `Your repositories` which is next to the `New repository` button.
* [ ] Click on the green `clone or download` button and copy the URL.
* [ ] Open a terminal window and navigate to the folder where you keep work for this class.
* [ ] Run `git clone [the url you copied]`. (That copies the repository from your account on GitHub to your computer so you can make changes.)

### Make a change in your file and push it to GitHub

* [ ] Open the folder in your coding IDE.
* [ ] Make a change in a file.
* [ ] Run through the steps outlined in `Step 3` of the first project ( status, diff, add, commit, push ).
  * Since you've cloned this repository, it is already pointing to your forked version. Therefore, you don't need to tell your computer where to push the code.

## 3. Creating a pull request (and some extra practice cloning a repository to your computer)

### Delete and re-clone

* [ ] Delete the folder on your computer for the forked repository.
* [ ] Re-clone the fork to your folder where you keep work for this class.
* [ ] Make a change to any file.
* [ ] Run through the process of pushing to GitHub ( status, diff, add, commit, push ).

### Background - Why fork a repository?

If groups of individuals are working on the same project and everyone pushes code to one repo without verifying the quality of the code, things can get messy pretty quick. GitHub fixed this solution with 'Pull Requests.' Basically, you fork a project, make changes to your fork, then you make a Pull Request (PR) back into the original project requesting that some piece of code be added to the original repo. This is how the vast majority of open source code projects work. In this step, we will make a pull-request.

### Create a pull request

* [ ] Go to your forked repo on GitHub.
* [ ] Locate the button that says `Pull Request` and click it.
* [ ] Locate the green button that says `New pull request` and click it.
  * You should now see the file changes you've made and how they differ from the original repo.
* [ ] Click on the `Create pull request` button to submit your PR.
* [ ] Now if you navigate to the <a href="https://github.com/DevMountain/learn-git/pulls">original repository</a> and take a look at the `Pull Requests` your new pull request should be there.
