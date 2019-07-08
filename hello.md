hello git test!

# markdown常用语法

## 1.标题
在想要设置为标题的文字前面加#来表示
一个#是一级标题，二个#是二级标题，以此类推。支持六级标题。
注：标准语法一般在#后跟个空格再写文字


## 2.字体
### 加粗
要加粗的文字左右分别用两个*号包起来 
**加粗**

### 斜体
要倾斜的文字左右分别用一个*号包起来
*斜体*

### 斜体加粗
要倾斜和加粗的文字左右分别用三个*号包起来
***斜体加粗***

### 删除线
要加删除线的文字左右分别用两个~~号包起来
~~删除线~~


# Git常用命令
## 1.初始化用户
git config --global user.name 'chentian114@sina.com'
git config --global user.email 'chentian114@sina.com'
git config --list

## 2.添加一个git仓库
git init

## 3.查看仓库状态
git status

## 4.添加文件到暂存区
git add xxx

## 5.将文件从暂存区提交到仓库
git commit -m 'add hello.md'

## 6.将修改文件添加到暂存区
git add xxx

## 7.将暂存区数据提交到仓库
git commit -m '第一次提交到仓库'

## 8.删除仓库中文件
rm xxx  删除本地文件
git rm xxx 删除仓库中文件
git commit -m '提交描述'

## 9.将文件从本地提交到github仓库
### 克隆github仓库到本地
git clone xxx.git
### 修改或添加文件，从工作区提交到暂存区
git add xxx
### 将暂存区数据提交到仓库
git commit -m '提交描述'
### 将分库数据提交到github仓库
git push


















