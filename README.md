### 回滚至之前版本  
  git log  
  git reset --hard 版本号  
### 回滚至之后版本   
  git reflog  
  git reset --hard 版本号  
### 取消跟踪文件/文件夹     
  git rm --cached <filename>  
  git rm -r --cached <folder>  
### 查看分支  
  git branch  
### 创建分支 
  git branch 分支名称  
### 切换分支  
  git checkout 分支名称  
### 分支合并（可能冲突）  
  git merge 要合并的分支  
  git merge 分支名称 --no-ff -m " 本次合并添加的注释信息"  
### 删除分支
  git branch -d 分支名称  
### 给远程仓库起别名   
  git remote add origin 远程仓库地址  
### 校验本地代码与远程仓库  
  git remote show origin  
### 向远程仓库推送代码  
  git push -u origin 分支名称  
### 合并版本记录
  git rebase -i 版本号 (合并版本号与之间所有版本到目前版本)  
  git rebase -i HEAD~数字 (合并目前版本前数个版本到当前版本)  
### 给版本打上tag  
  git tag -a <tag> -m "注释信息"  
  git push origin --tags  
