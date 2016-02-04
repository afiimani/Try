# Try
This is a Test directory to make sure Git is working. 
In order to set up more repositories through R see: https://support.rstudio.com/hc/en-us/articles/200532077-Version-Control-with-Git-and-SVN

But Beware: Setting up a new git repository will automatically add a Readme file that is not on the local directory. You need to pull that file to the local repository first before you can commit changes (or else you will get the error below.)

Inital Setup: 
Download git: Mine is in: usr/
Sign up for GitHUb: afiimani 

New ::: Comments
1. Create a remote repository on GitHub (Click +) New respoitory ::: Try
2. Create a local folder on my computer ::: ~Desktop/Try_GitHub/Try
3. Go to Terminal 
4. cd to local folder
5. git init ::: This adds a local .git repository folder in that directory
6. git remote add origin git@github.com:afiimani/Git_test.git ::: Defines for my local machine the path to the remote directory. (this path is copied from the GItHUb site next to the HTTPS tab). The path is saved in the variable called "origin"
7. Add files to this directory
8. git status ::: Should show all your new files as untracked
9. git add -A ::: Stages all files in the directory
10. git commit -m "First commit" ::: Adds new files to the local repository for tracking
11. git push -u origin master ::: Push all changes to GitHUb where the path == origin and the branch == master. 

Notes::: If you get an error try pull the files for Git HUb first before pushing. 
git pull origin master ::: Pull files to your local repository


Work flow: 
Create a new folder on my computer 
Stage 
