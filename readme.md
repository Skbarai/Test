# Basic Git commands and step by step guide for beginners  

## Installation

 To install git on your computer visit  
 
https://www.git-scm.com/downloads   

## Configuration

To Configure Your git user-name and email as the github to interact the  git with your github account by following commands

```bash
git config --global user.name "USER-NAME of github account"    
git config --global user.email "Your email"  
```

If you want to see the configures username and email use given command

```bash
git config --global --list 
```

## Note 
Git is a software which can be installed locally on your computer where as github is cloud platform to host your repositories just think like google drive. Git interacts with github to manage the versions of repositories

## Cloning

Once you have configured all these now lets start.
The simplest way of using git and github is go to your github account and just click on New and name your repository.
Now copy the link given there and use

```bash
git clone copied-url 
```

Now you will see the clone of the repository in your local computer you can now make changes in the repo and push it using simple commands and rest of the work git will do by itself😊.



## Some Helpful Concepts and commands

```bash
git status
```
very and handy yet very helpfull command you will use through your git & gihub journey. As the name suggests the command will  tell you the status (Untracked, staged and commited).  

Basically there are three working area in git:
- Untracked : once created file in the git repo(local or remote repo) will be untracked until it is added to stagging area.
- Staged  : Once you say the git to add it puts the copy of untracked to the stagging area.The staged area file will be the copy of untracked and any changes in the local file will not appear in the staged file until you again add.  
To add all the untracked files to staging area
```bash
git add .
```
- Commited : Once you have done all the work and added to the stagging area now you can  commit to tell that it is the final file.
To commit the changes
```bash
git commit -m "Some message"
```  
And now you can push the file to your github repository.

## Pushing to github
To push the file to your github repository

```git
git push -u origin main
```
Use git status in each steps for clear understanding.


## How to revert commit?
```git
git revert HEAD  
```
This 
changes the commit.  
Now push the file again after final commit.

## How to unpush the pushed repo?
```git
 git reset HEAD~1   
 git push -f origin main  
 ``` 
These two commands will unpush the pushed repo as they never been published on github😆.

## Enough to Get Started will Update Soon

*Thanks for reading*