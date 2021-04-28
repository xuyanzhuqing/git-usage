<center>git 学习手册</center>

<br>

说来惭愧，工作接近 6 年 关于 git 还是有很多操作没有搞明白，故而下定决心好好学习一下 git


> git config 该命令用于配置初始化变量， 分为全局（--global），用户，本地级别 (--local)

```
设置全局环境变量

git config --global user.name "michael"
git config --global user.email "michael"
git config --global core.editor "/usr/bin/vi"

查看所有环境变量
git config --list

查看指定变量
git config user.name

查看是那一级生效
git config --list --show-origin
```

> 获取帮助
```
git [verb] -h
man git [verb]
git help [verb]
```

> 文件状态

```
untracked  未跟踪
unmodified 未修改
modified 已修改
staged 已暂存
```

