# GIT
Learning GIT


git config --global user.name "Name"
git config --global. user.email email
git config --list. # to check changes

git log.    #to check all commits
git clone link  #copy repository to local machine
git status   # to track changes
git add filename  # to send file to staged
git commit -m "Message"
git push origin main       #to upload code to github
git remote add origin link    # 
git remote -v.   #to verify remote

git branch.   #to check branch
git branch -M "Rename".    # to rename branch
git checkout branchname.    # to change branch
git checkout -b new branch name    # to create new branch
git branch -D branchname.      #to delete branch
git push origin branchname

git diff brachname.   #to compare two branches
git merge branchname   #to merge two branches


#Undo changes
git reset filename. #to restore file from staged area
git reset HEAD~1.   #restore previous state

git reset hashvalue.  #to reset at particular commit
git reset --hard hashvalue.  #hard reset

git push origin --delete branchname.  #to delete branch from remote


