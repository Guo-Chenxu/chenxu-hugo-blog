---
title: "{{ replace .Name "-" " " | title }}" #标题
date: {{ .Date }} #创建时间
lastmod: {{ .Date }} #更新时间
author: ["Chenxu"] #作者
categories: 
- 分类1
- 分类2
tags: 
- 标签1
- 标签2
description: "" #描述
weight: # 输入1可以顶置文章，用来给文章展示排序，不填就默认按时间排序
slug: ""
draft: false # 是否为草稿
showToc: true # 显示目录
TocOpen: true # 自动展开目录
hidemeta: false # 是否隐藏文章的元信息，如发布日期、作者等
disableShare: true # 底部不显示分享栏
showbreadcrumbs: true #顶部显示当前路径
mermaid: true #是否开启mermaid
cover:
    image: "" #图片路径：posts/tech/文章1/picture.png
    caption: "" #图片底部描述
    alt: ""
    relative: false
---
