# Learning_Git_Github
Learning Git - Github with complete notes

Added Git and Github Notes

### <01> git --version -->
* ---> To check the version of git 
* ---> To check if Git is properly installed

<02> git config --global user.name "user_name" -->
---> To set user name (this info is important for version control systems)

<03> git config --global user.email "user_email_id" -->
---> To set user email id (this info is important for version control systems)

<04> git init -->
---> To initialize empty git repository in directory (folder)

<05> git status -->
---> To check the status of repository

<06> git add file_name -->
---> To add single spceific file in the current directory to the Staging Environment

<07> git add . -->
---> To add all files in the current directory to the Staging Environment

<08> git commit -m "our_message" -->
---> To create a information of the staged changes along a timeline of a Git projects history
---> That message should be meaningful

<09> git log -->
---> To check the history of commits for a repository

<10> git branch branch_name -->
---> To create new branch 

<11> git branch -->
---> To check all branches
---> asterisk (*) symbol represents the active branch

<12> git checkout branch_name -->
---> To switch branches 

<13> git checkout hash_code -->
---> To take your repository till that hash commit
---> To check the changes that you have done till that search commit

<14> git checkout -b branch_name -->
---> To create new branch and checkout in that newly created branch at the time of creation

<15> git merge branch_name -->
---> To merge the branches 
---> This command merges the specified branch’s history into the current branch

<16> git branch -D branch_name -->
---> To delete the branch

<17> git clone repository_url -->
---> To clone the existing remote repository to local repository

<18> git diff file_name -->
---> To check the changes that we made in the specific file

<19> git show commit_id -->
---> To show the changes that we made till that specific commit

<20> git reset --hard -->
---> To reset previous commit completly (commit and changes both)
---> It will remove previous commit and changes as well

<21> git reset --soft -->
---> To reset previous commit (only commit)
---> It will remove previous commit but not changes

<22> git remote add origin remote_repo_url -->
---> To connect local repository to remote repository

<23> git branch -M modified_branch_name -->
---> To modify current branch name

<24> git push origin branch_name -->
---> To add your local repository into remote repository

<25> git pull origin branch_name -->
---> To add your remote repository into local repository
