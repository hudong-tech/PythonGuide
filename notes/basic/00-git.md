# git

### 远程仓库

``` shell
$ ssh-keygen -t rsa -C "hudong.tech@gmail.com"
# 进入用户目录下的.ssh文件夹
$ cd /home/.ssh
# 打开id_rsa.pub文件，将ssh key复制到github中
```

### 拉取远程代码

``` shell
$ git pull origin develop
```

### 提交

``` shell
$ git add a.txt
$ git commit -m "add a.txt"
$ git push origin develop
```

### 分支

``` shell
# 在当前分支下创建develop的本地分支
$ git checkout -b develop 
# 将develop分支推送到远程
$ git push origin develop
# 将本地分支develop关联到远程分支develop上
$ git branch --set-upstream-to=origin/develop 
#查看分支
$ git branch -a 
```

### tree

``` shell
# 打开可视化界面
$ gitk --all
```

### 解决冲突

