---
title:  hexo使用
date: 2017-09-16 18:34:28
categories:
- 工具
tags:
- Hexo
---
介绍如何使用hexo编译/部署博客文章到GitHub上，做为个人的博客使用
hexo支持markdown语法，有丰富的主题和第三方服务，基本满足个人博客的使用
<!--more-->

## hexo使用
#### 步骤
##### 发布新文章
```bash  
hexo new post "article title"
```
##### 编辑md文件
使用markdown编辑器，编辑title，categories（类别），tags（标签）
```js 
---
title:  hexo使用
date: 2017-09-16 18:34:28
comments: false
categories:
- 工具
tags:
- Hexo
---
```
添加文章摘要  
<center>
![文章摘要](http://owdourx5j.bkt.clouddn.com/hexo_zhaiyao.png "文章摘要")
</center>
##### 清理编译
```bash  
hexo clean
```
##### 生成编译
```bash  
hexo g
```
##### 本地启动服务，查看md是样式否合理
启动本地服务
```bash  
hexo s
```
输入地址
> http://localhost:4000/
##### 部署
```bash  
hexo d
```
也可以执行
```bash  
hexo d -g #在部署前先生成
```
##### 远程gitgub查看
> 输入地址：https://windcatcher.github.io/
#### 参考
*   [手把手教你用Hexo+Github 搭建属于自己的博客](http://blog.csdn.net/gdutxiaoxu/article/details/53576018)
*   [Jekyll迁移到Hexo搭建个人博客](https://www.ezlippi.com/blog/2016/02/jekyll-to-hexo.html)
*   [next主题配置](http://theme-next.iissnan.com/getting-started.html#third-party-services)
*   [ hexo 怎么删除文章？](http://blog.csdn.net/time888/article/details/70249241)
*   [hexo常用命令笔记](https://segmentfault.com/a/1190000002632530)
*   [博客园markdown代码块支持的语言](http://www.cnblogs.com/qyf404/p/5019631.html)
*   [从今天开始使用HyperComments啦！](http://goozy.github.io/2017/03/22/%E4%BB%8E%E4%BB%8A%E5%A4%A9%E5%BC%80%E5%A7%8B%E4%BD%BF%E7%94%A8HyperComments%E5%95%A6%EF%BC%81/)
*   [百度分享集成+https](http://blog.csdn.net/cl534854121/article/details/76121105)
  