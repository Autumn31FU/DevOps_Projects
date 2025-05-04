# Collaborative Website Development with Git and Github

This project simulates the workflow of Tom and Jerry using Git and Github. This hands-on project will include installation of Git, setting up a GitHub repository, cloning the repository, creating branches, making changes, and merging those changes back into the main branch.


### Installation of Git
Confirmed installation of git by running **git version** command

![Git](Img/git_v.png)

### Created a new Github Repository
Created new repository called *ai-startup-website*

![Github repository](Img/ai_repo.png)


### Creating Directory
Created a new directory with **mkdir** command where the the *ai-startup-website* repository will be cloned into 

![Git](Img/mkdir.png)


### Cloning Repository
Cloned the *ai-website-repository* using **git clone**

![Git clone](Img/git_clone.png)


### Changing Directory

Changed directory into the *ai-startup-website* directory using **cd** command

![Git](Img/cd_command.png)


### Creating an empty file 
Created a new index.html file using the **touch command**

![Git](Img/touch_index.png)


### Adding content to the empty file
Updated the file using **vim**

![new file](Img/vim_index.png)


### Checking file status
Checked file status using **git status** command

![Git status](Img/git_status.png)


### Adding changes to staging area
Added file to staging area using **git add** command and confirming it with **git status** command

![Git add](Img/git_add.png)


### Committing changes
Committed changes made by running **git commit** command

![Git commit](Img/git_commit.png)


### Pushing changes
Pushed the changes to the remote repository using **git push**

![Git push](Img/git_push.png)

<br>






# Part 2: Simulating Tom and Jerry's Work 

<br>

## Tom

### Navigating to Project Directory
Moved backed into the project directory *ai-startup-website* using **cd** command

![Git](Img/cd_ai.png)


### Checking current branch
Checked the current branch using **git branch** command

![Git](Img/git_branch.png)


### Creating new branch

Created a new branch *update-navigation* for Tom using **git checkout -b**

![Git](Img/git_checkout.png)


### Confirming new branch
Confirmed the new branch with **git branch** command again
![Git](Img/git_branch2.png)


### Adding content to Tom's branch
Updated the file in the new branch using **vim**
![Git](Img/vim_update.png)


### Checking staged changes
Checked the file status using **git status** command

![Git](Img/git_status2.png)


### Adding new changes to Staging Area
Added the file to staging area with **git add**

![Git](Img/git_addT.png)


### Confirming new changes in Staging Area
Confirmed file is being tracked with **git status** command again

![Git](Img/git_statusb.png)


### Committing changes
Committed the changes to the new branch *update-navigation* with **git commit**

![Git](Img/git_commitb.png)


### Pushing changes
Pushed the changes with **git push**

![Git](Img/git_pushb.png)


# Jerry


### Switching back to main branch
Switched backed into the *main* branch using **git checkout**

![Git](Img/git_checkoutj.png)


### Pulling latest changes from tom's branch
Pulled the latest changes from tom's branch using **git pull**

![Git](Img/git_pullO.png)


### Creating Jerry's branch
Created a new branch for jerry using **git checkout -b** command

![Git](Img/git_checkoutj2.png)


### Updating Jerry's file
Updated jerry's file using **vim**

![Git](Img/vim_j.png)


### Adding Jerry's file to staging area
Added the new changes to staging area with **git add**

![Git](Img/git_addj.png)



### Committing Jerry's changes
Committed jerry's changes with **git commmit**

![Git](Img/git_commitj.png)


### Pushing Jerry's changes

Pushed jerry's changes with **git pull**

![Git](Img/git_pushF.png)