# Learning Git Github
Learning Git - Github with complete notes 
<br/> Have written useful commands for reference 
<br/> Created By - ***<span style="color:#9e3dd4">Tineshwar Singh</span>*** 😎 
<br/> ***#TineshLearning***

---
---
## 1. Git Version
---
### <01> git --version 
* To check the version of git 
* To check if Git is properly installed
---
---
## 2. Git Configuration
---
### <02> git config --global user.name "user_name" 
* To set user name (this info is important for version control systems)

### <03> git config --global user.email "user_email_id" 
* To set user email id (this info is important for version control systems)

### <04> git config --global --edit
* To set user name and user email in vim editor
---
---
## 3. Starting with Git
---
### <05> git init 
* To initialize empty git repository in directory (folder)

### <06> git clone repository_url 
* To clone the existing remote repository in local system
---
---
## 4. Local Changes 
---
### <07> git add file_name 
* To add single spceific file in the current directory to the Staging Environment

### <08> git add . 
* To add all files in the current directory to the Staging Environment

### <09> git commit -m "our_message" 
* To create a information of the staged changes along a timeline of a Git projects history
* That message should be meaningful

### <10> git commit --ammend -m "new_message" 
* To combine changes in the staging environment with the latest commit, and creates a new commit
* One of the simplest things we can do with --amend is to change a previous commit message
---
---
## 5. Check Changes 
---
### <11> git status 
* To check the status of repository

### <12> git diff file_name 
* To check the changes that we made in the specific file

### <13> git show commit_id 
* To show the changes that we made till that specific commit
---
---
## 6. Check Commit History
---
### <14> git log 
* To check the history of commits for a repository

### <15> git reflog 
* The reflog is an ordered list of the commits that HEAD has pointed to it's undo history for your repo and it's purely local 
---
---
## 7. Branching 
---
### <16> git branch 
* To check all branches
* asterisk (*) symbol represents the active branch

### <17> git branch branch_name 
* To create new branch 
---
---
## 8. Git Checkout 
---
### <18> git checkout branch_name 
* To switch to new branch

### <19> git checkout hash_code 
* To take your repository till that hash commit
* To check the changes that you have done till that search commit

### <20> git checkout -b branch_name 
* To create new branch and checkout in that newly created branch at the time of creation
---
---
## 9. Branch - Merge / Delete / Modify
---
### <21> git merge branch_name 
* To merge the branches 
* This command merges the specified branch’s history into the current branch

### <22> git branch -D branch_name 
* To delete the branch

### <23> git branch -M modified_branch_name 
* To modify current branch name
---
---
## 10. Undo Changes 
---
### <24> git reset --hard 
* To reset previous commit completly (commit and changes both)
* It will remove previous commit and changes as well

### <25> git reset --soft 
* To reset previous commit (only commit)
* It will remove previous commit but not changes
---
---
## 11. Git Remote 
---
### <26> git remote -v 
* To check the configuration of the remote server

### <27> git remote add origin remote_repo_url 
* To connect local repository to remote repository
---
---
## 12. Git Push
---
### <28> git push origin branch_name 
* To add your local repository into remote repository
---
---
## 13. Git Pull
---
### <29> git pull origin branch_name 
* To add your remote repository into local repository
---
---
## 14. Git Ignore
---
### <30> .gitignore 
* It's a file name which use to specify selected files or parts of your project which we don't want to share 
---
---
## 15. Removing Files
---
### <31> git rm -rf 
* To remove git repository from local system 
---
---