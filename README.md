# gitnotes


Git学习笔记
获取本地分支和远程分支信息

git remote -v

获取本地的分支

git branch

从远程端获取所有的分支信息

git fetch main

新建一个分支并pull代码

git checkout -b zhj-f-pre-release-v2.1 main/f-pre-release-v2.1

对这个分支push的分支进行设置（默认push到）

git push -u origin zhj-f-pre-release-v2.1:zhj-f-pre-release-v2.1

清楚所有的更改（强制）

git reset --hard

删除本地分支

git branch -D 分支名

移除有关git的所有东西

rm -rf .git/ 

删除链接的远程分支

git remote rm origin

//暂存
git stash

//取出
暂存


git stash pop
