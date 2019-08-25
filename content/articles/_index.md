---
title: "Articles"
date: 2019-08-24T18:18:12+08:00
draft: true
---
{{ with .Site.GetPage "/blog" }}
{{ with .GetPage "my-post.md" }}{{ .Title }}{{ end }}
{{ end }}