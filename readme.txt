Git is a distributed version control system
Git is a free software distributed under GPL.
Git has mutable index called st4age.
Git tracks.
Git has a mutable index called stage.

Author --Lin Chen

git add fileName fileName

git diff
git diff HEAD --filename //查看工作区和版本库中最新文件的区别

git commit -m "message"
git status
git log --pretty=oneline
git reset --hard HEAD^
git reset --hard HEAD^^
git reset --hard commitId
git reflog
#将文件的暂存区代码（如果没有暂存区新版本就使用版本库代码）checkout，撤销未提交的修改
git checkout -- filename 
