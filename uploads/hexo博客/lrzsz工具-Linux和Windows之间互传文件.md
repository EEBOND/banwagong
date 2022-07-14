---
title: lrzsz工具 Linux和Windows之间互传文件
summary: 该工具需要在支持文件传输的终端工具中使用，如xshell可以，而putty不能 
categories:
  - Linux
tags:
  - lrzsz 
cover: https://i.picsum.photos/1280/954
date: 2021-11-16 23:04:38
---
该工具需要在支持文件传输的终端工具中使用，如xshell可以，而putty不能。
### 安装lrzsz工具

```bash
yum install -y lrzsz
```

### Linux端接收来自Windows端的文件

```bash
rz
```

输入命令后会弹出文件选择框
![](https://cdn.jsdelivr.net/gh/eebond/images/Markdown/20211117155926.png)

### Linux端发送文件到windows端

```bash
sz [文件路径]
```

输入命令后会弹出文件保存位置选择框
![](https://cdn.jsdelivr.net/gh/eebond/images/Markdown/20211117160215.png)  
