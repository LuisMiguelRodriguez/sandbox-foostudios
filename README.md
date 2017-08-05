# sandbox-foostudios
 ### For first Run do steps 1 -11 if project is already forked and worked on do steps 4 - 11
 
 
 ### step#1 Fork repo you want to work on
 
 ### step#2 git clone forked repo

 ### step#3 git remote add upstream -original repo URL that you forked- //this allows you to connect to the original repo you cloned

 ### REPEAT STEPS BELOW IF YOU HAVE ALREADY DONE STEPS 1 -11 once before
 
 
 ### step#4 git branch new-features // create a new git branch

 ### step#5 git checkout new-features // switches to new branch that was just made

 ### step#6 Make what ever changes you would like to make

 ### step#7 git add -A , git commit -m "Changes mades"

 ### step#8 git push origin new-features // updates your repo

 ### step#9 go to your github account and create a pull request

 ### step#10 now you need to wait for user to accept the pull request and merge
 
 ### step#11 after merge delete branch and return to master branch
     git branch -d the_local_branch

 ### step#11 now you will need to update your master branch run git pull upstream master 

  git fetch upstream
  git checkout master
  git merge upstream/master
  git push origin master
