---
title: "Hugo"
date: 2019-08-24T21:53:04+08:00
menu:
  docs:
    parent: "hugo"
    weight: 1
draft: true
---

# 记录一下目前使用 HUGO 学习到的知识

## 创建项目

``` sh
$ cd to/parent/dir/of/project
$ hugo new site <project-name>
```

## 目录结构

```
.
├── layouts           // html模板文件夹
├── static            // 静态数据文件夹
├── config            // 出其他配置文件
└── content           // 主页面文件夹
    └── about
    |   └── index.md  // <- https://example.com/about/
    ├── posts
    |   ├── firstpost.md   // <- https://example.com/posts/firstpost/
    |   ├── happy
    |   |   └── ness.md  // <- https://example.com/posts/happy/ness/
    |   └── secondpost.md  // <- https://example.com/posts/secondpost/
    └── quote
        ├── first.md       // <- https://example.com/quote/first/
        └── second.md      // <- https://example.com/quote/second/
```
