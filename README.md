#回滚至之前版本  
  git log  
  git reset hard -- 版本号  
###回滚至之后版本###   
  git reflog  
  git reset hard -- 版本号  
###查看分支###  
  git branch  
###创建分支###
  git branch 分支名称  
###切换分支###
  git checkout 分支名称  
###分支合并（可能冲突）###  
  git merge 要合并的分支  
###删除分支###
  git branch -d 分支名称  
###给远程仓库起别名###   
  git remote add origin 远程仓库地址  
###向远程仓库推送代码###  
  git push -u origin 分支名称  
