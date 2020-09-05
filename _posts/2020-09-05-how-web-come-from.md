---
layout: post
title: '网页搭建过程'
date: 2020-09-05
author: Ameliy
color: rgb(153, 153, 229)
cover: '../assets/cover_pictures/sunset-background-lighting-at-dusk-sky-evening-sky.jpg'
tags: Web
---

# 网页起始
* TOC
{:toc}
## 目的
为了记录和监督学习，准备在个人网页分享学习过程；
## 关于我
中途转技术美术er；学习加油哇！  
不管是个人网页还是其他，都是边学习边分享~（包括现在这篇也是test吼吼吼）  
## 搭建过程
我的搭建拖了很久，不是很记得，也不是重点，简单记一下；  
首先，查找资料；  
### 参考
目前成功的是参考这些：  
 [Github Pages+jekyll搭建个人站点](https://zhuanlan.zhihu.com/p/51240503)  
[官网资料可以多看看](https://www.jekyll.com.cn/docs/"%3Ehttps://www.jekyll.com.cn/docs/%3C/a%3E)  
[我参考的模板（感谢作者）](http://jekyllthemes.org/themes/HardCandy-Jekyll/)  
[Jekyll kramdown配置](https://developer.aliyun.com/article/25449)  
### 问题和解决
1. 主要是参考文章安装几个包；可以自检；另外make版本不一样应该没问题；
2. 遇到gem install一些版本依赖问题，也是Google解决；比如ffi安装错误，参考https://github.com/ffi/ffi/issues/598  
  （另添加md目录，_config.yml添加use_coderay:true，提交导致编译失败；最终注释又能有目录，迷幻结果）
