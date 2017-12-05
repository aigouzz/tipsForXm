# tips for xiaomi

______________________

1：gulp版本号要对应好
2：node版本号最好是7.9.0
3：直接安装npm install

————————————————————————

1：先master拉个新分支，然后在push到远程仓库
2：然后切到master，然后merge新分支，把修改的东西推到master
3：然后切到RELEASE，merge master，把修改的东西推到RELEASE
4：之后打tag，也就是执行./mitag.sh，然后去发布系统
5：再到cms生成页面，然后刷缓存

---------------------------

git branch -a
git checkout .
git checkout newbranch
git branch -D thebranch
git push origin --delete thebranch
Git checkout -b newbranch


---------------------

Administrative-divisions-of-China:城市三级联动
自己能够写出来最好

-------------------------