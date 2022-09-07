# Meta_Version-Control - Add_Ons
Hello! Fellow Readers Creating this repository to add missed or Skipped content during the course (Version Control by Meta - Coursera). Please feel free to add additional information if missed any.

***Please find the missing/skipped content along with their titles below***

## Installing Git on Linux(Ubuntu)

 - **Step 1 : sudo apt-get update** ***( This updates linux - This is a standard practice to update before installing any )***
 - **Step 2 : sudo apt-get install git** ***( This installs updated git version )***
 - **Step 3 : git --version** ***(To Verify the installed version)***

## Connecting to GitHub via SSH

 - Please run the commands as shown in the reading till step 6
 - While at step 7 linux users will encounter an error ==pbcopy: command not found== because pbcopy and pbpaste commands are exclusively available only on Mac OS X platform
 - In here ==pbcopy is used to copy== the key from ==.pub file==
 - So instead of pbcopy please use **CAT Command** ==**cat < ~/.ssh/<YOUR KEY>.pub**==
 - This opens key in terminal
 - Copy the key manually and paste in your GitHub
