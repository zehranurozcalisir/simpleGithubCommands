# Basic Github Commads
|commad|description|
|:---|:---|
|**git init**|The folder is converted to GIT file|
|**git clone** url| Pulls github files into the folder|
|**git status**| Shows changes made to the project|
|**git add . -file**|Adds codes into staging area |
|**git restore --staged**|Rverts changes|
|**git commit -m**|Saves changes permanently|
|**git commit -a -m / -am**|Saves the changes in the project without git add but does not add new classes|
|**git rm -r [file_name]**|Remove file|
|**git branch -a**|Lists all branch|
|**git branch [branch_name]**|Creates a new branch|
|**git branch -d [branch_name]**|Deletes a branch|	Merge a branch into the active branch
|**git push origin --delete [branch_name]**| Delete a remote branch|
|**git checkout -b [branch_name]**|Creates a new branch and switches to it |
|**git checkout -b [branch_name] origin/[barnch_name]**|Starts using a remote branch|
|**git branch -m [old_branch_name] [new_branch_name]**| Changes the branch name|
|**git checkout [branch_name]**| Starts use branch|
|**git checkout -**|Switches to the last used branch|
|**git checkout -- [file_name]**|Deletes changes to the file|
|**git merge[branch_name]**|Merges the used branch into the active branch |
|**git merge [source branch] [target branch]**|Merges two specified branches|
|**git push origin [branch name]**|The branch is sent to the remote repository|
|**git push** |Sends all changes|
|**git push origin --delete [branch name]**| Deletes the branch in origin |
|**git pull origin [branch_name]**| Pulls changes|
|**git log --summary / -oneline**|Views changes|
|**git diff [source branch] [target branch]**|Shows differences between 2 branch|

### .gitignore file
> Prevents tracking of changes in some files.
### .gitkeep file
>Tracks changes even though the file is empty
