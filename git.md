###

无论是切换分支还是合并分支都需要在内容修改之后 git add .和 git commit -m 'description'

###

回滚到某一版本
step1:git log -g
step2:git reset --hard commitId
若是想撤销回滚则：git reflog 可以得到所有的操作信息，然后找到某一版本的 commitId 之后 git reset --hard commitId

###

删除远程分支
git push origin -d branchName
