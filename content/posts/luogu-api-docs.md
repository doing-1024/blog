+++
date = '2026-04-08T19:15:26+08:00'
draft = false
title = '非官方的洛谷Api文档'
tags = ["Luogu"]
+++
这两天帮老师研究洛谷爬虫，需要爬取题解、题目标签等信息，但是尝试直接爬取网页就会发现效率慢且有的信息（比如tags）爬取不到。猜测是洛谷采用了前后端分离的方式，遂寻找API。

寻找的过程中发现Github上有一份热心网友整理的[文档](https://github.com/0f-0b/luogu-api-docs/)（为避免意外，我也[fork](https://github.com/doing-1024/luogu-api-docs)了一份），整理的非常全面，各个方面都有，同时把所有的鉴权操作都列了出来，爬虫时只需要注意控制限速即可了，后续我也会将我的代码发到这个blog。
