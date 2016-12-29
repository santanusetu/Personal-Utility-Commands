# Personal-Utility-Commands

#### Finding The Application Running on Specific Port
* netstat -a -o | find "8080"

#### Killing the process on windows
* Taskkill /PID 26356 /F

------------




#### Undo 'git add' before commit
To remove the file from the current index('about to be commited' list) without changing naything else
* git reset "filename"

To un-stage all due changes. This comes handy when there are too many files to be listed.
* git reset 



------------

#### Git Stashing
To stash all the current changes and clear the status report
* git stash

To see what is in the stash
* git stash list

To pull changes from the upstream branch. 
* git pull
(Make sure it says fast-forward in the report. If it doesn't, you are probably doing an unintended merge)

To apply stashed changes back to working copy and remove the changes from stash unless you have conflicts.
* git stash pop
(In the case of conflict, they will stay in stash so you can start over if needed)

------------

#### Git delete unpushed git commits
To Delete the most recent commit, keeping the work
* git reset --soft HEAD~1

To Delete the most recent commit, destroying the work
* git reset --hard HEAD~1

------------

#### Git branching commands
Create issue branch using JIRA

To create a branch and changing to it
* git checkout -b iss53

To changing to it
* git checkout iss53

To delete a branch from remote
* git push origin --delete [branchName]

To delete a branch from local
* git branch --delete [branchName]
------------

# Unit Testing
#### Ignore code coverage for unit tests in EclEmm
Preferences->Java->Code Coverage and set the "Only path entries matching" option to src/main/java



--------------
# Web Development Utility 

### Bootstrap cheatsheet
https://hackerthemes.com/bootstrap-cheatsheet/
