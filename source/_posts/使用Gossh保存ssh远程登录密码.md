---
title: 使用Gossh保存ssh远程登录密码
date: 2018-03-30 16:28:19
tags:
---
开发或运维过程中频繁使用ssh，Mac也有一些ssh客户端，而我觉得还是终端下ssh比较好用，但无法保存密码，为了弥补它的不足

于是。。。

有了Gossh
## 什么是Gossh？
Gossh是使用Go编写的远程登录客户端，可以一键登录远程服务器，它解决了终端下ssh无法保存密码的问题。
使用Go语言编写的原因是它可以跨平台，并且用户无需安装运行环境，只需要一个终端它就能运行，Linux也可以使用。

## 下载
[https://github.com/i183/gossh/releases](https://github.com/i183/gossh/releases)

## 使用方法
下载后建议把gossh放到 /usr/bin 目录下，这样无需配置环境变量便可在任意目录下调用