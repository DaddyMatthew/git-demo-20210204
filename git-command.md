---

工作区，暂存区，本地仓库，远程仓库 

---
### 一、命令
* git --help 调出Git的帮助文档  
* git +命令 --help 查看某个命令的帮助文档  
* git --version 查看Git的版本  
* git init 生成空的本地仓库  
* git add readme.md 将文件添加到暂存区   
* 初次commit之前，需要配置用户邮箱及用户名，使用以下命令：  
git config --global user.email "you@example.com"  
git config --global user.name "Your Name"

* git commit 将暂存区的文件提交到本地仓库
* git remote 用于管理远程仓库
* git push -u origin master 往origin仓库的master分支提交变更
* git clone 从远程仓库下载变更

   