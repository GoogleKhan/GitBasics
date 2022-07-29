# GitBasics
only for demo

# Wipro_July
This batch starts from DevOps
------------------------------------
How to create a branch

1. Using GitHub
2. Using git CLI

To list down all the branches:
-----------------------------
$ git branch
* featureA
  main

How to pull latest changes from remote:
---------------------------------------
$ git pull origin

How to switch to a branch:
---------------------------------------
$ git checkout <branch_name>

$ git checkout featureA

How to add modified files in to git ecosystem:
------------------------------------------------
$ git add <file_name>

$ git add . # for all files in current directory


How to commit changes in local repository:
------------------------------------------------
$ git commit -m "any message"


How to post/push local changes into the remote repository(GitHub):
-------------------------------------------------------------------
$ git push

======================
How to create a branch:
-------------------------
$ git branch <branch_name>

after modification -> git add -> git commit 

For pushing chnages along with branch creation on GitHub:
---------------------------------------------------------
$ git push --set-upstream origin <branch_name> 

List all availabale tags:
---------------------------
$ git tag

How to create a tag:
---------------------
$ git tag <tag_name>

How to push a tag:
---------------------
$ git push origin <tag_name>

----------------------------------------
How to save incomplete/un committed changes into stash:
---------------------------------------------------------
$ git stash save

How to check stored changes in the stash:
---------------------------------------------------------
$ git stash list
stash@{0}: WIP on branch-2: 1d35dc2 addition method


How to get back my work from stash:
---------------------------------------------------------
$ git stash pop


