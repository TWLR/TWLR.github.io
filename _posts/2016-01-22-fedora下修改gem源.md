---
layout: post
title: "fedora下修改gem源"
date: 2016-1-22 12:39
tags: jekyll  gem  fedora

---
1. 查看gem当前源：`gem sources`
2. 删除默认源地址：`gem sources -r https://rubygems.org/`
3. 添加淘宝源地址：`gem sources -a http://ruby.taobao.org/`
4. 更新源的缓存:`gem sources -u`

> 参考链接：[如何修改Ruby的gem源(gem sources)](http://jingyan.baidu.com/article/4853e1e51c770f1909f726fe.html)