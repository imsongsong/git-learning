# git-learning
git learning

## git config --list
## git config global user.name 'ss'
## git config global user.email 'ss@gmail.com'
## git init XXX-Project(new project)
## git init (existing project)


## git add .：将工作空间新增和被修改的文件添加的暂存区
## git add -u:将工作空间被修改和被删除的文件添加到暂存区(不包含没有纳入Git管理的新增文件)


## 
## 删除不需要的分支 git branch -D XXX
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
