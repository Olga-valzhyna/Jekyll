---
layout: default
title: Making, committing, and pushing changes
parent: GitHub Desktop
nav_order: 4
---
# Making, committing, and pushing changes
1. To launch your external editor from within GitHub Desktop, click **Repository**, then click **Open in EDITOR**.
2. Make some changes to the **.md** file that you previously created.  When you are satisfied with your changes, save them in your text editor.
3. In GitHub Desktop, navigate to the **Changes** view. In the file list, you should see your **.md**. The checkmark to the left of the .md file indicates that the changes you've made to the file will be part of the commit you make. In the future, you might make changes to multiple files but only want to commit the changes you've made to some of the files. If you click the checkmark next to a file, that file will not be included in the commit.
4. At the bottom of the Changes list, enter a **commit message**. To the right of your profile picture, type a short description of the commit. Below the summary, you'll see a **"Description"** text field where you can type a longer description of the changes in the commit, which is helpful when looking back at the history of a project and understanding why changes were made. 
5. Click Commit to **BRANCH NAME**. The commit button shows your current branch so you can be sure to commit to the branch you want.

![GitHub Desktop](/assets/images/D8.jpg)  
To push your changes to the remote repository on GitHub, click **Push origin**.  
   
![GitHub Desktop](/assets/images/D9.jpg)

The **Push origin** button is the same one that you clicked to publish your repository to GitHub. This button changes contextually based on where you are at in the Git workflow. It should now say Push origin with a 1 next to it, indicating that there is one commit that has not been pushed up to GitHub.  
The "origin" in Push origin means that you are pushing changes to the remote called origin, which in this case is your project's repository on GitHub.com. Until you push any new commits to GitHub, there will be differences between your project's repository on your computer and your project's repository on GitHub.com. This allows you to work locally and only push your changes to GitHub.com when you're ready.
* In the window to the right of the Changes view, you'll see suggestions for actions you can do next. To open the repository on GitHub in your browser, click View on GitHub.
* In your browser, click 2 commits. You'll see a list of the commits in this repository on GitHub. The first commit should be the commit you just made in GitHub Desktop.

