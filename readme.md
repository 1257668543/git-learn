# 来聊聊git的进阶功能
    git add (./文件名) 将全部/指定文件提交到缓存区
    git commit -m '注释'  确认提交，添加日志信息
    git push 上传到github远程仓库
    git log 从最近到最远的一次提交日志
    git log--pertyy=oneline 将日志信息一行显示
    git diff 查看文件差异
    git reset --hard HEAD^ 回退到指定版本，HEAD后有多少个^就代表回退几个版本
    git reset --hard 日志号 回退到指定日志号的版本
    git reflog 当找不到所需日志号时，用此命令查看所有历史操作
    
    新增分支dev
        git branch 查看当前分支状态
        git checkout -b dev 在本地创建新分支dev
        git checkout 分支名 切换到指定的分支
        git push origin dev 将代码提交到dev分支上
        git merge dev 将dev分支合并到当前分支上,远程仓库的合并不使用命令行，在github网站上进行操作
        git branch -d dev 删除dev分支

Git is free software distributed under the GPL

HEAD^^