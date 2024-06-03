# Basic Git commands and step by step guide for beginners
# Make an account on github by simply continuing by google or facebook..
# To install git on your computer visit 
https://www.git-scm.com/downloads \
# Configure Your git user-name and email as the github to interact the git with your github account by following commands:
git config --global user.name "USER-NAME of github account" \
git config --global user.email "Your email" \
# If you want to see the configures username and email use given command:
git config --global --list \
<!-- Git is a software which can be installed locally on your computer where as github is cloud platform to host your repositories just think like google drive. Git interacts with github to manage the versions of repositories.--> \
# Once you have configured all these now lets Start 
# The simplest way of using git and github is go to your github account and just click on New and name your repository.
# Now copy the link given there and use:
git clone copied-url \
# Now you will see the clone of the repository in your local computer you can now make changes in the repo and push it using simple commands and rest of the work git will do by itself.
git status  -> very and handy yet very helpfull command you will \ use through your git n gihub journey. As the name suggests the \
command will tell you the status (Untracked, staged and commited). \
Basically there are three working area in git  \
1) Untracked -> once created file in the git repo(local or remote repo) will be untracked until it is added to stagging area.\
2) Staged  -> Once you say the git to add it puts the copy of untracked to the stagging area.The staged area file will be the copy of untracked and any changes in the local file will not appear in the staged file until you again add. \
3) Commited -> Once you have done all the work and added to the stagging area now you can finally commit to tell that it is the final file. \
and finally you can push the file to your github repo.\
# To do the above work you have to use following commands:
git add .  To add all the untracked files to staging area \
git commit -m "Some message"  To commit the changes \
git push -u origin main  To push the file to your github repo \
OR use just "git push" once you have already pushed \
Use git status in each steps for clear understanding. \

# How to revert commit?
git revert HEAD \
changes the commit. \
You can push the file again. \
# How to unpush the pushed repo?
 git reset HEAD~1 \
 git push -f origin main \
 These two commands will unpush the pushed repo as they never been published on github. \

 *Thanks for reading*