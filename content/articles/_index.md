---
title: "Articles"
date: 2019-08-24T18:18:12+08:00
menu:
  docs:
    parent: "articles"
    weight: 1
toc: false
draft: false
---
{{ with .Site.GetPage "/blog" }}
{{ with .GetPage "my-post.md" }}{{ .Title }}{{ end }}
{{ end }}