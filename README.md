# gittest
git,github学习仓库

git命令
本地仓库创建
git init 初始化一个本地仓库，在同级目录下生成一个.git文件
配置
git config -l 查看
git config user.name name 配置
三级配置文件
.git/config
当前用户目录 /.gitconfig
git安装目录 /etc/gitconfig
本地提交
git add filename 提交到索引（-A 代表所有，包括新增、变更、删除；.代表新增和变更）
git commit -m '描述'  提交到文件库
git commit -am ‘版本描述' 一步完成
