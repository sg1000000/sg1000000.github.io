---
title: Git 学习笔记
author: songgen80
date: 2019-08-09 20:55:00 +0800
categories: [Blogging, Tutorial]
tags: [学习笔记]
pin: true
---

配置git， Git Bash终端

```bash
git config --global user.name "name"
git config --global user.email "email"
```

查看配置是否成功

```bash
git config --list
```

将 git 仓库 https://github.com/sg1000000/the-craft-of-selfteaching 克隆到本地

```bash
git clone https://github.com/sg1000000/the-craft-of-selfteaching
```

查询远程仓库路径
```
git remote -v
```

设置上游代码库 upstream 

```bash
git remote add upstream https://github.com/selfteaching/the-craft-of-selfteaching.git
```

上传同步到github

```bash
git add .
git commit -m '说明'  //说明可替代为其他任意
git push
```

