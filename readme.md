# Test VSC and Git

This is a test made to add files, commit, and push code from VSC to GitHub. It assumes you have created a repo in GitHub and also linked your GitHub with VSC with proper permissions. 

Steps involved:

- Open your project local folder in VSC.
- Check the branch you are in, with:

`git status`

If this is not on the branch you want, make sure to change it.

If you are not on any branch, you might want to check you did initialize a new Git repo or reinitialize a new one with the command `git init`.

- Edit the things you want to add and change in VSC, make sure to save everything, and then add these files with:

`git add .`

- Commit with `git commit -m "Commit Message"`

- Finally, push the changes with the command `git push -u origin master`.  

**The `git remote add origin [remote repository URL]` command is used to add a new remote repository to your local Git repository**