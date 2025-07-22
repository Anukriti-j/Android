# Android
My android development work here
start with git
what is git githubb
create repo
git config to configure git into git to associate with particular user
git status to chekc status of file added, modified, or staged, untracked

next class add file and commit to remote repo 
git --version
git config --global user.name "username"
git config --global user.email "email"
git clone "link"
cd <foldername> switch to current folder
git status
git add: to take the chnages to staging 
git commit: finally save the chnages to take to remote repo
staging area: get the changes prepared wihtout saving to remote 
command to stage the chnages
git add <filename>
commit. snaping of changes that are made and save them
untracked status = new file
modified status = changes made in existing file

git log command to show commits - summary of logs with author name
git show <commit id> details of commit
git push origin main - main is the branch and origin means the branch from which we pulled the data
git push -u origin main  - -u means setting upstream , then it will always psuhed into main
 git branch branchname // to create a new branch
 git switch branchname // to move to another branch
git switch -c branchname //creating a branch and switching to it
git merge // pull changes from one branch to another'
git merge branchname
to merge the branch first switch to main becox we want to merge in that only
than write git merge branchname // the branch we want to merge or pull from
resolving conflicts , suppose having chnage sin same file in two branches and they are getting merged , this is done manuallyq
git show / git log 
git pull origin main // taking latest chnges from known branch that are already in the system from remote //merging all the chnages automatically to current ccode
git fetch   to take all the branches from remote //only download chnegs and not merge it automatically to be done manually
git remote  // we can see remote we have , for now we have origin
git remote add <remotename>
git remote add than remote link
git remote remove and name of remote
git remote rename currentremote name then newname

git reset  //go one commit behind our current commit 
--soft    // changes still present in staging area HEAD ~1 tilt one says to go back to one commit 
--mixed    // default selection of git when we do git reset // put back them to modified files present status chnages not staged anymore
--hard  //every chnges gets removed even from staging area 
// HEAD ~ 2 means go back by 2 commits and work to reset them
git revert
