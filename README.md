# gitPractice

This is a for text pupose only.



What is a .git folder? 
The Git repository is stored in the same directory as the project itself, in a subdirectory called .git.There is only one .git directory, in the root directory of the project.

What is the Master?  
It is the main default branch of the project when a git project is initialized.
What is Origin?  
It is by itself just a name (a rather common one) to denote the remote repo. 

Insert from the memory: Shift + Insert



git  init   ⇒ initialize the folder for the git if the folder is initialized you see .git directory 

rm  -rf .git ⇒ remove the initialization, this will not delete the folder but just .git file which is used for the storing information by the git

git  status ⇒ check the status of the git

git  add filename or folder ⇒ to add in the staging area before committing
Example git doc.txt or git 

git commit -m “Message” ⇒ commits the changes, -m is for a message, the message should be in double quote. Example: git commit -m “This is a change in adding method.”. This will commit the source code with the message, “This is a change in adding method.” 

git  commit -a -m “message” ⇒ If you have lots of changed files in your working copy - and want all of them included in the next commit - you can make use of the "-a" parameter and thereby omit the "git add" step:


git  commit --ament “message” ==>
The "--amend" option comes in handy, for example, when you mistyped the last commit's message or forgot to add a change. The following example will correct the very last commit by overwriting its message and adding another change:

HEAD always refers to the most recent commit on the current branch.


git  log ⇒ To see the log of commits    example: git log -5 will list the last 5 commits

Unstage the file

git reset doc.txt ⇒ will unstage from staging area to modified file 
git reset. ⇒ unstage all files


git  pull ⇒ to pull the source codes from a remote repository and updates the local repostitory  (it is a combination of git fetch and git merge)

git push ⇒ to send the local repository's source codes  to the remote repository. Formula git push <remote> <branch>
Example: git push remote master
git  fetch ⇒ 


git  branch ⇒ to list all the branches
git  remote ⇒ to list all the remotes

git  remote <alias> <url>  ⇒ used for adding a remote repository to local repository   
Example: git remote origin https://github.com/birrana/gitPractice   

Here you can name any beside origin. 



