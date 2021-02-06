**git commit -am 'Some message'**
----------

*Only work for all ready tracked files*
### No need to user git add (Express commit)




**git log**
----------
*--oneline*
### Use to how git log in one line without author info 

*--graph*
### Use to show git loges as line graph

**git config alias**
----------
To make your owen local shorthand with git 

*git config --global alias.linegraph "log --oneline --graph"*
### To show git logs graph without info (for all git repose)
###### use `git linegraph`

*git config --global alias.longlinegraph "log --graph"*
### To show git logs graph with info (for all git repose)
###### use `git longlinegraph`

*git config alias.linegraph "log --oneline --graph"*
### To show git logs graph without info (for current git repose)
###### use `git linegraph`

*git config alias.longlinegraph "log --graph"*
### To show git logs graph with info (for current git repose)
###### use `git longlinegraph`

**Add remote origin  to local branch**
----------
git remote set-url origin https://github.com/g1ji/notes.git