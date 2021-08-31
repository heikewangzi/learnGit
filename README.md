# learnGit
跟廖雪峰学gitHub
git 要关联远程仓库，使用命令 git remote add origin '仓库地址'
关联一个远程仓库是要给仓库指定一个名字，一般origin默认名字
关联之后，第一次推送 git push -u origin master 第一次推送master分支的所有类容；
之后，每次提交，只要有必要，就可以命令git push origin master;
Creating a new branch is quick & simple.

命令git checkout -- readme.txt意思就是，把readme.txt文件在工作区的修改全部撤销
， git checkout -- readme.txt
Git同样告诉我们，用命令git reset HEAD <file>可以把暂存区的修改撤销掉（unstage），重新放回工作区 git reset HEAD readme.txt
11