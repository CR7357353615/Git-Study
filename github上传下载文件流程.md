## cmd中设置邮箱和用户名
git config --global user.name "youname"

git config --global user.email "youeamil@email.com"

* 1.找到需要上传的文件的位置，右键git bash here
* 2.按照以下流程输入

  * git init //初始化仓库

  * git add .(文件name) //添加文件到本地仓库

  * git commit -m "first commit" //添加文件描述信息

  * git remote add origin + 远程仓库地址 //链接远程仓库，创建主分支

  * git pull origin master // 把本地仓库的变化连接到远程仓库主分支

  * git push -u origin master //把本地仓库的文件推送到远程仓库

* 拉代码
  * git fetch origin master

  * git log -p master..origin/master

  * git merge origin/master

  * git pull origin master
