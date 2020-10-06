---
title: 群晖安装Docker
img: /images/docker.png
top: false
cover: false
toc: true
mathjax: true
date: 2020-10-06 15:45:13
password:
summary: 如何在群晖上安装Docker？
tags: 群晖
categories: NAS
---

# 安装Docker

套件中心搜索Docker

![](Synology-Install-Docker/img001.png)

# 启用国内镜像加速

Docker->注册表->设置->编辑

![](Synology-Install-Docker/img002.png)

![](Synology-Install-Docker/img003.png)

勾选启用注册表镜像，输入镜像源地址

国内的镜像源地址（选择其一）：

https://registry.docker-cn.com
http://hub-mirror.c.163.com
https://3laho3y3.mirror.aliyuncs.com
http://f1361db2.m.daocloud.io
https://mirror.ccs.tencentyun.com

![](Synology-Install-Docker/img004.png)

确认后等待重启