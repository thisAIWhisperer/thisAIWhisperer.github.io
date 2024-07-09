---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: {{ .Date }}
draft: true # 草稿
tags:
  - "Sample"
author: "AI 溝通師"
showToc: true # 目錄
TocOpen: false # 目錄預設是否開啟
hidemeta: false # 是否隱藏文章的發布日期等等
comments: false # 留言功能
description: "文章簡單敘述優化SEO"
disableShare: false # 文章底部分享區
searchHidden: false # 是否要在搜尋功能隱藏該文章
ShowReadingTime: false # 顯示閱讀時間
ShowBreadCrumbs: true # 顯示文章所在路徑
ShowPostNavLinks: true # 顯示上下一篇文章
ShowWordCount: false # 顯示文字數字
UseHugoToc: false # 是否使用 Hugo 預設的目錄
cover:
    image: "<image path/url>" # image path/url
    alt: "<alt text>" # alt text
    caption: "<text>" # display caption under cover
    relative: false # when using page bundles set this to true
    hidden: true # only hide on current single page
---