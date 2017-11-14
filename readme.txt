Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.

git checkout -- file  delete modification in work space
git reset HEAD file delete modification in stage
Version rollback   git reset --hard HEAD^  or  git reset --hard file_id


git remote add origin git@github.com:PengfeiCui/learngit.git
git push -u origin master

git push origin master   

New branch
git checkout -b dev    same to git branch dev + git checkout dev  
switched to a new braunch 'dev'

git branch    check all branches

git merge dev   merge two branches