Git is a distributed version control system
Git is a free software distributed under GPL.
Git has mutable index called st4age.
Git tracks.
Git has a mutable index called stage.

Author --Lin Chen

#将工作区文件提交到暂存区“
git add fileName fileName

git diff
git diff HEAD --filename //查看工作区和版本库中最新文件的区别
#将暂存区文件提交到分支
git commit -m "message"
git status
git log --pretty=oneline
git reset --hard HEAD^
git reset --hard HEAD^^
git reset --hard commitId
git reflog
#将文件的暂存区代码（如果没有暂存区新版本就使用分支代码）checkout，撤销工作区代码的修改
git checkout -- filename 
#将暂存区文件恢复到工作区
git restore --staged filename
#将文件从版本库删除，需要commit命令确认。
git rm filename

#生成ssh文件
ssh-keygen -t rsa -C "youremail@example.com
#将生成的id_rsa.pub文件拷贝到SSH_key里面

#将本地的已有仓库和空的远程库相连接,gabbychen/GitLearn.git是文件在git库中的位置
git remote add origin git@githu.com:gabbychen/GitLearn.git