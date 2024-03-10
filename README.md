- git init 初始化仓库

- git status 查看仓库状态

- git add 向暂存区中添加文件

- git commit 保存仓库的历史记录

vim 编辑

退出命令是，按 ESC 键 跳到命令模式，然后输入:q（不保存）或者:wq（保存） 退出。

- git diff 查看更改前后的差别

# Git 教程

工作树 暂存区的区别

- git diff head 查看工作树和最新提交的差别

这里的 head 是指 当前分支中最新一次提交的指针

- git branch 显示分支一览表

- git checkout -b 创建，切换分支

## Git 教程

1. feature-A

- git checkout - 切换回上一分支

- git merge --no-ff 为了在历史记录中明确记录下本次分支合并 在合并时加上 --no-ff 参数
