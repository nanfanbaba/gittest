## git 的学习

### 基础命令
git add .
git commit -m "提交本次你修改的记录"
git pull origin master
git push origin master 


### 合并分支

假如你在aaa分支，你想要吧aaa分支的代码合并到bbb的分支

git:(aaa) git checkout bbb
git:(bbb) git pull origin bbb
git:(bbb) git merge aaa
git:(bbb) git add .
git:(bbb) git commit -m "合并aaa的分支"
git:(bbb) git push origin bbb 

