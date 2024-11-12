# git练习
## 常用命令
### config系列命令
- **git config --global user.name "用户名" 设置用户名**
- **git config --global user.email "邮箱" 设置邮箱**
- git config --global core.editor "编辑器" 设置默认编辑器   
- git config --global core.autocrlf true 解决windows换行符问题
- git config --global alias.别名 命令 设置别名
- git config --list 查看所有配置信息
- git config --global --unset user.name 删除用户名
- git config --global --unset user.email 删除邮箱
- git config --global --unset core.editor 删除默认编辑器
- git config --global --unset core.autocrlf 删除windows换行符问题解决方案
- git config --global --unset alias.别名 删除别名
### 基本操作命令
- git clone 仓库地址 克隆远程仓库到本地
- **git init 初始化一个仓库**
- **git add 文件名 添加文件到暂存区**
- git commit -m "提交信息" 提交暂存区到仓库
- git status 查看仓库状态
- git log 查看提交历史
- git diff 查看文件修改内容
- git reset --hard HEAD^ 回退到上一个版本
- git reset --hard HEAD^^ 回退到上上个版本
- git reset --hard 版本号 回退到指定版本
- git branch 分支名 创建分支
- git checkout 分支名 切换分支
- git merge 分支名 合并分支
- git branch -d 分支名 删除分支
- git remote add origin 远程仓库地址 添加远程仓库
- git push -u origin master 推送本地仓库到远程仓库
- git pull 下载远程仓库到本地