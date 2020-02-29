---
layout: default
title: 每周记录第8期
excerpt: 思考一种打包文件格式。
tags: [Thinking]
---
{{ page.title }}
================

本周，我思考了一种打包文件格式，讲文件的名称放入文件头部，文件名称用文件名的MD5值代替。这样可以很快速的检索到文件，并且不需要额外的文件记录文件名对应表。只是每个文件头部增加一些字节来达到这个目的。我看这种打包文件格式其实跟tar工具的思想是差不多的，只不过可以将多个文件一起打包，并且在文件头部把目录结构写进去。

下周还是很忙，希望可以多写点代码。

{{ page.date | date: "%Y-%m-%d" }}