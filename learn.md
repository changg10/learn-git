记录学习git
git remote add origin git@github.com:changg10/learn-git.git
git remote -v  
git branch - main #指定分支的名字为main
git push -u origin main:main #关联main分支
git push <远程仓库名称> <本地分支名>:<远程分支名>
git push origin --delete master 删除分支
git branch -M main #会将当前分支（master）强制重命名为main
git branch  #查看当前分支名字