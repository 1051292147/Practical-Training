1、操作Git

1.1、将本地文件上传到远程仓库

1.1.1、创建一个本地项目

cd  实训

git init

git add .

git commit -m "介绍"

复制仓库地址

git remote add origin 地址

git push -u origin master

若出现如下
1、操作Git

1.1、将本地文件上传到远程仓库

1.1.1、创建一个本地项目

cd  实训

git init

git add .

git commit -m "介绍"

复制仓库地址

git remote add origin 地址

git push -u origin master

若出现如下
error: failed to push some refs to *****************


git pull origin master --allow-unrelated-histories //把远程仓库和本地同步，消除差异

重新add和commit相应文件

git push origin master

此时就能够上传成功了


git pull origin master --allow-unrelated-histories //把远程仓库和本地同步，消除差异

重新add和commit相应文件

git push origin master

此时就能够上传成功了
