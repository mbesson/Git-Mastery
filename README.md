# Git-Mastery
My notes to do some real damages with git (&amp; Github!)

---

## Git

### First configure your user name and email

This is only used to track who did what on a project, not for login.

git config --global user.name "Mathieu Besson"
git config --global user.email "mathieu.besson@tuta.io"

### Init the version control on a repository

In the current repository you want to put under version control, run the folowwing command: 

```bash
git init
```

### Getting the status of the repo

```bash
git status
```

### Creating a checkpoint

First, we add files on a staging area

```bash
git add myfile
```
(--all option to add everything or git add .)

and then 

```bash
git commit -m "Explain the commit"
```

### Checking the history

To check the history of comits, use the following command: 

```bash
git log
```

### Back to the past

To get a previous version: 

```bash
git checkout <commit-hash>
```

### Branch

It is a timeline of the project.

```bash
git branch <new-branch-name>
```

In order to work with the branch:

```bash
git checkout <new-branch-name>
```

To merge the changes I made : 

```bash
git merge <my-branch-name>
```
### List of useful commands
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
