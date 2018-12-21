- pwd
> 显示当前目录
- git init
> 将所目录变为仓库
- 添加/修改文件到仓库
 1. git add
 2. git commit
```
$ git commit -m "描述"
```
- git status
> 仓库当前状态
- git diff
```
# 查看修改内容
$ git diff fileName
```
- git log
> 查看历史记录
或者 git log --pretty=oneline
- 回退
> HEAD表示当前版本
> HEAD^表示上个版本 ...
> HEAD~100
***
> git reset
```
$ git reset --hard HEAD^

$ git reset --hard commit_id(需回退到的版本的id)

# 或者reflog找到此id
$ git reflog
```