# git-learning
git learning

## git config --list
## git config --global user.name 'ss'
## git config --global user.email 'ss@gmail.com'
## git init XXX-Project(new project)
## git init (existing project)

## 工作区/暂存区/HEAD（头指针）/Branch
## git add .：将工作空间新增和被修改的文件添加的暂存区
## git add -u:将工作空间被修改和被删除的文件添加到暂存区(不包含没有纳入Git管理的新增文件)
## 创建tag git tag XXX (YYY)
## 删除tag git tag remove XXX
## 创建分支 git checkout XXX (YYY)
## 删除分支 git branch -D XXX


## 
## 
## 修改最新commit的message git commit --amend
## 修改旧commit的message git rebase -i XXX
## 把连续的多个commit合并成1个 git rebase -i XXX
## 比较暂存区和Head的差异 git diff --cached
## 比较工作区和暂存区的差异 git diff
## 把暂存区恢复成和Head一样 git reset HEAD
## 取消暂存区部分文件的修改 git reset HEAD XXX
## 把工作区恢复成和暂存区一样 git checkout
## 清除最近的几次提交 git reset --hard XXX
## 比较不同提交的差异 git diff XXX YYY --ZZZ
## 临时加塞紧急任务 git stash/git pop/git apply
## 指定不需要git管理的文件 .gitignore /结尾 表示只忽略文件夹下的文件
## 
##
## 本地仓库同步到GitHub git remote add origin xxx.git; git fetch; git merge --allow-unrelated-histories origin/master; git push;
## 不同人修改不同文件
## 不同人修改同文件不同区域
## 不同人修改同文件统一区域
## 同时变更了文件名和文件内容
## 把同一个文件改成了不同的文件名
## 禁止push -f
## 禁止对集成分支做rebase
