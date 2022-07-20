---
title: 如何运行py文件
author: Songgen80
date: 2022-7-20 9:55:00 +0800
categories: [编程学习]
tags: [jupyterlab,编程,笔记,python]
pin: true
---

### 如何运行py文件

打开 Jupyter lab 的目录（就是你保存 `ipynb` 文件的地方，以便在 Jupyter lab 中打开、浏览、编辑 `ipynb` 文件），运行 cmd 命令，运行以下命令，就可以打开 jupyter lab。

```
jupyter lab
```

接着打开 launcher 界面中的 Console 命令行工具 Python 3 运行如下命令即可。

```bash
%run 拆分excel文件.py
```
此时的 cmd 窗口不能关闭，否则 Jupyter lab 就停止运行了 —— 就将它放在那里。

随后会有个浏览器打开，指向 [http://localhost:8888/lab?](http://localhost:8888/lab?) —— 你就看到 Jupyter lab 的操作界面了。

目前，Jupyter lab 和 Jupyter notebook 是并存的，虽然前者是后者的下一步替代者。如果你依然习惯于使用 Jupyter notebook，那么，在浏览器中指向 [http://localhost:8888/tree?](http://localhost:8888/tree?) 看到的就是 Jupyter notebook.
