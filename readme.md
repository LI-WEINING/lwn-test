# readme
+ 项目文档

## 查看配置列表： git config --list

## git init
1. 把当前目录初始化为版本库
2. 会在目录下生成一个隐藏文件.git

## git add 文件名
1. 把当前下文件目录下文件提交到暂存区域
2. git add readme.md 把这个文件提交到暂存区
3. git add . 当前目录所有变动提交到展存区域

## git status
1. 查看当前文件目录状态（新增、删除、修改）

## git commit -m '提交注释文本'
1. 把暂存区的内容提交到本地仓库

## 本地涉及到的三个部分
1. 工作区域（实际文件）
2. 展存区域
3. 本地仓库

## git log
1. 查看操作日志 

## git reflog
1. 查看操作日志（简单版）

## git diff 文件变更信息
1. 查看文件变更信息


## git reset --hard 版本号
1. 退回版本 HEAD^回到上一个版本
2. 回到指定版本

## 主要几个操作
1. git init -> 创建版本库
2. git add 文件名 -> 工作区提交到暂存区
3. git commit -m '注释' ->暂存区提交到本地仓库

## git remote add origin 远程仓库
1. 把本地仓库与远程关联

## git remote -v
1. 查看本地仓库关联的远程仓库地址

## git push -u origin master
1. git push 本地仓库提交到远程仓库
2. -u origin master 设置默认远程仓库和分支
3. 执行完这个命令之后，以后可以直接：`git push`提交到本地产库的master分支

## 更新代码
1. 把远程代码更新到本地，先提交到本地再更新
2. git pull 把远程代码拉取到本地
3. git clone 把远程仓库克隆到本地

## git branch
1. 查看分支
2. 当前分支前面有*

## gt branch 分支名
1. 创建分支

## git checkout 分支名
1. 切换分支

## git branch -d 分支名
1. 删除分支

## git merge 分支名
1. 合并分支


