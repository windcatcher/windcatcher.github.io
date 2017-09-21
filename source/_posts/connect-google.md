---
title: 国内访问google--使用host
date: 2017-09-18 15:29:27
categories:
- 工具
tags:
- host
---
介绍如何使用host的访问google、Facebook等国外主流网站  
由于上网需要，我们经常需要使用到google搜索，但避免不了被墙，所以网络上有各种梯子。比较使用，个人认为host使用起来还是比较方便和高效的    
在选择搜索引擎方面，基于不浪费生命的原则，由于google搜索匹配度比百度的高，个人更倾向使用google  
<!--more-->


> host文件访问域名的原理  
A.用户主机访问某一个域名,先从host文件中读取，如果host文件有该域名的ip地址，则直接返回该ip地址  
B.如果没有该ip地址，则从dns服务器中获取ip，并将ip保存到host文件中   

#### 需要的工具和环境
###### 最新host文件
* [下载地址](https://laod.cn/hosts/2017-google-hosts.html)
> host 文件里包含了google等网站的ip地址  
> windows环境下host文件路径 
> *C:\windows\system32\drivers\etc* 

###### SwitchHosts! 软件
* [下载地址](https://github.com/oldj/SwitchHosts/releases)

#### 步骤
###### 1安装SwitchHosts! 软件
###### 2使用管理员身份运行SwitchHosts! 软件
###### 3拷贝host内容并启用
将下载的host文件的全部内容拷贝SwitchHosts! 软件myhost选项页中，并启用  
![效果](http://owdourx5j.bkt.clouddn.com/switchhost.png)
###### 4测试使用google
https://www.google.com/ncr





