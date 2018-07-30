# abhaydham
One time setup:
- Download and install git:  https://git-scm.com/download/win
- Download and install pycharm:  https://www.jetbrains.com/pycharm/download/
- Set the correct path for git :  https://stackoverflow.com/questions/26620312/installing-git-in-path-with-github-client-for-windows
- Clone the github project created by Abhinav
- Once the project is cloned, it creates a folder called 'abhyadhama'
- cd abhyadhama --> Now you are in the project folder

Simple commands to work with github code
- git branch --> this command lets you know which branch you are using currently, 'master' is the master branch
- When working on your code locally, always use a branch so that you don't accidentally corrupt 'master' branch.
- git checkout -b my-first-trial  --> This creates a local branch off master
- Open pycharm and open this folder 'abhyadhama'.
- On the bottom right corner, you'll see that it is pointing to 'my-first-trial' branch (good sign to always work on a branch other than master)
- Add/Edit/Delete files or code.
- To check in any code to github, click on VCS(version Control System) -> git->Commit File
- Select the files to check in, add comment and click on the drop-down arrow next to 'Commit'. Select 'Commit and Push' and go through the options to 'PUSH' your branch to github.
- Your local branch now gets pushed to github and sits as a new 'branch' under 'master'.

Github Branch:
- You can view your branch on github.
- Create a Pull Request (PR) and set an assignee "Abhi/Anuj' so that they can view your code and know your changes.
- If no assignee, double check your PR and Merge your code.
- Once merged your branch can be deleted or you can keep your branch.

Local Changes once your branch has been pushed:
- git checkout master ---> you will now point to the 'master' branch locally
- git pull --> this gets the latest code from github repository
Now delete your local branch
- git branch -D my-first-trial ----> this will delete your local branch. You need to be in master to delete any branches underneath.


Repeat all of the commands above if you want to start over again, starting from 'Simple commands to work with github code'.

A lot of help is available for git commands and problems in stackoverflow.


