Day 1 - GitHub from zero.



What is Git? - It is a tool that keeps track of everything that changes to a fil. Any file that you are working on. Has version history so you can rollback to other versions. You can monitor changes. You can see who, what, when, and where anyone made the changes. "Version control system". Runs locally on your PC.



Workflow for Git.

* Local - Runs on your local computer.

&#x09;- You start in your working directory (the place where your project is).

&#x09;- Then you stage it, which means they are ready for the next step.

&#x09;- Local repository - This is where all the files that you are working on are saved before saving 	them to the main repository.

* After which you "commit". MTF



What is GitHub? - Central online server. A place where all the files/code that you are working on will go. Other people working with you can contribute and their version will go there as well so you can track everyone's versions and merge them together. Synonymous to Google Drive or OneDrive.



What is a repository? - It is a place where all of your projects files are stored as well as their complete version history. Locally would be on your computer. "Remote" would be on GitHub. A repository can be created locally or on GitHub itself and then you can clone the remote one to your local machine.



What is a commit? - Like saving a file. Confirming. Saving to the local machine



git push will then push your commits to the remote repository.



git init = when this command is used in your working directory it will activate Git to start tracking changes to your files.



git status = shows you which files have been modified/changed.



Staging = adding. Getting the changes/files ready for commit.



git add = --all or -A for everything in your project.

git add . = puts all the files in your current directory for staging.

git add \* =  only stages new or modified files. if you add \*.txt or any file type it will add all files of that type.

git reset = Removes files from the staging area.



This is very important for developers whether solo or as a team to keep track of all your work, monitor changes and version history and collaborate with others for a singular project. It also acts as a cloud backup.





I installed Git and launched Git Bash from the desktop

* Ran git --version to confirm 
* git config --global user.name "username" and ... user.email "user email" to configure git to my remote repository on GitHub.
* cd \~ to take me to the home directory.
* mkdir homelab-journey to make a new directory for this project
* cd homelab-journey to take me to said directory
* git clone <url> . with the period at the end it clones the files directly into the current directory rather than making a new folder.



Today I was able to understand what GitHub and Git is to an extent.

I was able to set up everything, make a directory, clone a GitHub repository to that directory and commit it to the staging area where I then added it to the remote repository.



Setting up a personal access token

Creating a GitHub repository

Doing a CLI commit



