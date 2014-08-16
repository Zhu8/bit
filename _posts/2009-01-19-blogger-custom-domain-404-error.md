---
title: Blogger绑定自定义域名404错误
date: 2009-01-19 12:46:24 +0800
layout: post
permalink: /blog/2009/01/blogger-custom-domain-404-error.html
noToc: true
categories:
  - 石马 | Code
tags:
  - 404
  - Blogger
  - 域名
---
**问题**：今天下午的时候blogger绑定的域名http://www.zhu8.net提示：**"The page cannot be found. (Error 404)"**。不知道出现404错误是什么原因，大概搜了一下，发现原来是因为DNS缓存的问题，可能在Godaddy上的设置过2-3天才会生效。


**解决方法**：将你的Blogger先切换回.blogspot.com，然后再切换回来。一切OK！（明后天再继续观察一下，因为我选中了redirect zhu8.net到 www.zhu8.net）