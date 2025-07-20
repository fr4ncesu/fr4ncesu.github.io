---
date: '{{ .Date }}'
draf: true
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
---
