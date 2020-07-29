# Revisions and the Cloud

When working on our repositories we can also work on and update our sites directly from our computer. By copying your link into your terminal you can create a *clone* on your desktop. Then when updating from your computer it will automatcally update on github, and vice versa. 

Start by navigating to the Github repository you want to clone. Click the green button in the top right corner labeled **"Code"** and copy the link provided for your repository. Next open your terminal and navigate to where you want the cloned copy to live. We put ours on the desktop so I typed "cd desktop" to take me there. From there you can start the cloning process by typing "git clone" a space, then pasting the link to your repository. Click enter and it should create a directory!

From there you can access the directory by typing "cd (your repository's name)" and clicking enter. This action will open the folder. While in the folder typing "code ." will open VS Code. VS Code will allow you to utilize the same or similar capabilities as Github has when working with your pages. Make sure to document your changes in the terminal. 

  - "git status" shows changes made to repository
  - "git add ." will add the changes you've made
  - "git commit -m (insert an explanation of change)" to explain what you changed
  - "git push origin master" to make sure those changes are shared with Github
 
All your changes should now be shared between both your saved repository on your computer as well as the repository on Github!
