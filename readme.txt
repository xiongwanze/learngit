Gti is a distributed version control system
Git is free software distributed under the GPL
syn to github

// create repo
git init

//commit
git add filename
git commit -m "description"

//show log
git log

//check status
git status

//check diff
git diff filename

//update to the x version. HEAD-current version HEAD^-last version
git reset --hard commit_id

//show all git command
git reflog

//show the diff between workspace and the newest repo
git diff HEAD -- filename


//reserve the modify
git checkout -- filename

//delete filename
git rm filename
git commit -m "delete file"

//link local repo and remote repo
git remote add origin https...

//push local repo to remote repo
git push -u origin master
git push origin master


//clone remote to local
git clone https... 