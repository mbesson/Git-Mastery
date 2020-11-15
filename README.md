# Git-Mastery
My notes to do some real damages with git (&amp; Github!)

## Git

### First configure your user name and email
git config --global user.name "Mathieu Besson"
git config --global user.email "mathieu.besson@tuta.io"

### 
git remote -v : this will list the remotes I have
git remote rm : to delete a remote

## Github
Github is a hosting platform for Git repositories

### how to push code on my local machine to Github?
 - First create a new repo on github.com
 - Create a "remote"

 Once created, you can select the url of the Github repo and do the following command

 ```bash
git remote add origin https://github.com/blabla/myrepo.git
 ```

 In this case, "origin" is the name of the remote. So you can change it it does not matter.
 - And push

 ```bash
 git push -u orign master
 ```

 Note than the "-u" option is only necessary the very first time you push
###
