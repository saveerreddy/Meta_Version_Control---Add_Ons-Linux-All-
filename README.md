# Meta_Version-Control - Add_Ons for Linux and all
Hello! Fellow Readers Creating this repository to add missed or Skipped content during the course (Version Control by Meta - Coursera). Please feel free to create Pull requests with additional information if missed any.

***Please find the missing/skipped content along with their titles below***

## Installing Git on Linux(Ubuntu)


 - **Step 1 : sudo apt-get update** *( This updates linux - This is a standard practice to update before installing any )*
 
 - **Step 2 : sudo apt-get install git** *( This installs updated git version )*
 
 - **Step 3 : git --version** *(Verify the installed version)*
 

## Connecting to GitHub via SSH


 - Please run the commands as shown in the reading till step 6
 
 - While at step 7 linux users will encounter an error **`pbcopy: command not found`** because pbcopy and pbpaste commands are exclusively available only on Mac OS X platform
 
 - `pbcopy is used to copy` the key from `.pub file`
 
 - Instead of pbcopy please use **CAT Command** **`cat < ~/.ssh/<YOUR KEY>.pub`**
 
 - This opens key in terminal. Please copy it manually and paste in your GitHub
 
 ## Creating and cloning a repository 
 
 - Described cloning using HTTPS in the vedio. **Here is how to clone using SSH**
 
 - **`git clone <Complete SSH Link>`** eg.,`git clone git@github.com:mkdocs/mkdocs.git`
 
 ## Example Workflow
 - After creating new branch using -b flag 
 ```
 git checkout -b feature/my-new-feature
 touch README.md
 git add README.md
 ```
 - `git add README.md cannot create a new file` so please create it using `touch command` and follow up
 
 ## Blame
 - During the course we will be using a public repository called **MKdocs** but no rep info has been shared so please find repository link here **[mkdocs/mkdocs](https://github.com/mkdocs/mkdocs)**
 ```
 git clone https://github.com/mkdocs/mkdocs.git
 (or)
 git clone git@github.com:mkdocs/mkdocs.git
 cd mkdocs
 ls -l
 ```
 - once cloned and moved to mkdocs directory as show above please follow up with the vedio
 
