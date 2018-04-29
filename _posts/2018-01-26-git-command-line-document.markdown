---
layout: post
title:  "git 命令行文档"
date:   2018-01-26 18:46:40 +0800
tags: git
author: Yiwen
---

```js
    // 删除文件夹
    git rm -rf --cached folderName
    
    // 创建分支
    git branch <name>
    
    // 切换分支，加上 -b 表示创建并切换
    git checkout <name>
    git checkout -b <name>
    
    // 删除本地分支
    git branch -d <name>
    
    // 删除 github 上的远程分支
    git push origin :<name>
    
    // 提交本地分支到 github 远程分支，没有远程分支会自动创建
    git push origin <本地分支名称>:<远程分支名称>
    
    // 合并分支到当前分支
    git merge <name>
     
    // 提交
    git add -A
    git commit -m '操作说明'
    git push
```
