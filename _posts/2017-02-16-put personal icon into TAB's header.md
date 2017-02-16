---
layout: post
title: 在标签页头部插入个性图标
data:  2017-02-16 18:00:00 +0800
categories: html 
tag: icon
---

* content
{:toc}

1.浏览器通用方法  
-------------------------------
把favicon.ico图标放到网站根目录下，在网页的'<head></head>'中加入

	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />

2.IE或TT浏览器 
------------------------------
把需要显示的16x16像素的ICO图标命名为favicon.ico放置在网站根目录下，浏览器会自动检索

3.Firefox浏览器 
------------------------------
图标格式没有IE那么严格，GIF和PNG格式的图标也可以显示，图标名称也可以不是favcion

把图标放在根目录后，在<head></head>中加入

	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
	<link rel="icon" href="gif_favicon.gif" type="image/gif" >

或

	<link rel="shortcut icon" href="favicon.ico" type="image/x-icon" />
	<link rel="icon" href="png_favicon.png" type=" image/png" >

*实际上现在只要在网站根目录下放置一个faviocn.ico，浏览器都能识别了。*