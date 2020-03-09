---
title: hexo常用指令
tags: hexo
---
### hexo init
hexo init 命令用于初始化本地文件夹为网站的根目录

`hexo init [folder]`
* folder 可选参数，用以指定初始化目录的路径，若无指定则默认为当前目录

### hexo new  
用于新建文章，一般可以简写为 hexo n
### hexo generate  
命令用于生成静态文件，一般可以简写为 hexo g  
### hexo server  
用于启动本地服务器，一般可以简写为 hexo s  
### hexo deploy  
用于部署网站，一般可以简写为 hexo d  
### hexo clean  
用于清理缓存文件，是一个比较常用的命令
```
 将hexo部署到GitHub
 hexo clean
 hexo generate
 hexo deploy
```