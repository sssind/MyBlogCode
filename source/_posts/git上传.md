---

layout: post
title: git上传
categories: [技术教程,新手教程]
tags:  教程
author: CKH
---

git的简单上传使用技巧

<!--more-->
# git简单上传使用技巧
## 1.  添加到暂存区

```
//将所有文件添加到暂存区
git add *

//也可以单独选择文件
git add test01.md
```

## 2. 添加到缓存区

 ```
 //提交暂存区到本地仓库（缓存区），-m 说明信息
 git commit -m "说明信息"
 ```


## 3.提交

```
//提交到指定分支
git push origin master
```


