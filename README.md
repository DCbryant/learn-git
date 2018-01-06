
ls -la .git

stage

working directiory

origin


new File

git add  => stage

stage file

git commit 

stage -> working dirctionary

git push 

working dirctionary -> origin



git diff 工作区和暂存区

git diff master(分支名) 工作区和历史区

git diff --cached 暂存区和历史区比较 


撤销

git checkout .(文件名)  (回不去) 从暂存区中将工作区内容覆盖掉

git reset HEAD .(文件名) 将暂存区回滚到上一阶段(回到上一次的暂存区)，然后可以使用git checkout .将暂存区内容覆盖工作区内容


git reset --hard id    将历史区的记录覆盖到工作区和暂存区

git reset --hard HEAD^   回滚到上一次历史并覆盖工作区和暂存区

git reflog  查看所有log

