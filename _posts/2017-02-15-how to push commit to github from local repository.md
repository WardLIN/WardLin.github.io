---
layout: post
title: 如何将本地仓库的新版本推送到github上
data:  2017-02-15 23:14:00 +0800
categories: document
tag: git
---

* content
{:toc}

git操作
-------------------

1.在github上创建一个空项目；

2.通过git clone 获取github项目 先复制下项目的地址

>命令行:git clone 项目地址


3.可以本地的项目里编写代码,创建文件了

4.提交编辑的文件到git暂存区

>命令行:git add .

5.提交暂存区的文件到本地git

>命令行:git commit -m "提交说明"

6.提交本地git到远程服务器 github

>命令行:git push origin master

输入账号密码

*PS*：每次执行完命令行应该都看下执行状态

>命令行:git status


第一次提交项目到远程服务器的时候可以需要配置用户名和邮箱 不提示就不需要配置

>命令行：git config --global user.name "用户名"

> git config --global user.email "邮箱"
