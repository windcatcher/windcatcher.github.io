---
title: markdown 使用
date: 2017-09-16 10:34:28
comments: false
categories:
- 工具
tags:
- Hexo
---
介绍如何使用markdown编写个人文章
markdown是一种非常流行的文本标记语言，语法简洁明了，易于排版，便于书写，第三方支持丰富。
<!--more-->


## markdown 使用
>   总结了markdown 使用的常见语法和快捷键  

#### 常用语法

##### 换行与缩进  
* 换行：在行尾部处先按入**两个**以上的**空格**  
* 缩进：输入&amp;emsp;

##### 标题  
* 行首插入1 到 6 个 # ，对应到标题1到6阶

##### 列表 
-  无序列表：-或 * 即可变为无序列表
-  有序列表：直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。

##### 引用
* 需要在文本前加入** \> **

##### 粗体和斜体和字体颜色
* 粗体：**两个 \* **包含一段文本
* 斜体：用**一个 \* **包含一段文本
* 字体颜色：&lt;font color=red\>内容&lt;/font\>
    * *例如*   
    ><font color=red>内容</font>

##### 图片与链接
* 图片为：!\[\]\(\){ImgCap}{/ImgCap}
* 链接为：\[\]\(\)

##### 代码框
* \`\`\`java\`\`\`
* 示例：    
>\`\`\`java  
这是一段java代码  
\`\`\`
* *效果：*  
```java
//结算
public void deposit(double money) {  
        double newBalance=this.balance+money;  
        try {  
            Thread.sleep(10);  
        } catch (InterruptedException e) {  
            // TODO: handle exception  
        }  
        this.balance=newBalance;  
    }  
```

##### 分割线
* 分割线的语法只需要**三个 \* 号**

##### 页内跳转
###### 自动生成目录:
* 参考 快捷键[生成目录](#content)

###### 手动生成目录
* 目录内容    
        \* \[1.语法示例\](#1)  
        &emsp;\* \[1.1图片\](#1.1)    
* 正文  
       &lt;h5 id="1">1.语法示例&lt;/h2>  
        &emsp;&lt;h6 id="2">1.图片示例&lt;/h2>  
* 例如  
> 目录         
        [1.语法示例](#1)  
        &emsp;[1.1图片](#1.1)  
   正文     
        <h5 id="1">1.语法示例</h2> <h6 id="1.1">1.1图片</h2>

###### html标签实现  
- 定义一个锚(id)：&lt;span id="jump"\>跳转到的地方&lt;/span\>
- 使用markdown语法：\[点击跳转\]\(\#jump\)
- *例如：*
> <span id="jump">跳转到的地方</span>
    [点击跳转](#jump)
***

#### 常用快捷键
*   MarkdownPreview插件:    
**快速预览**：**alt+m**，*前提需要设置该快捷键，MarkdownPreview没有默认的快捷键*  
**生成网页**：按**CTRL + B**生成网页HTML；        
**生成目录**：在文章最前面添加**\[TOC\]**自动 <span id="content">生成目录</span>  ；  
**调出命令**：**Ctrl+Shift+P**或是点击Preference->Package Control调出命令面板，输入**mdp**
*   OmniMarkupPreviwer插件：       
**Ctrl+Alt+O**: Preview Markup in Browser       
Ctrl+Alt+X: Export Markup as HTML.      
Ctrl+Alt+C: Copy Markup as HTML  

*   MarkdownEditing插件  
插入链接：输入 “mdi + tab”    
插入图片：输入 “mdl + tab”   



***
#### 参考
*   [MarkDown技巧：两种方式实现页内跳转](http://www.cnblogs.com/JohnTsai/p/4027229.html#jump)
*   [Markdown 语法说明 (简体中文版)](http://www.appinn.com/markdown/)
*   [Markdown: Basics （快速入门）](http://www.appinn.com/markdown/basic.html)
*   [Markdown——入门指南](http://www.jianshu.com/p/1e402922ee32/)
*   [怎么结合印象笔记来使用Sublime Text？](http://www.jianshu.com/p/f8ff7dace5d4)
*   [使用Sublime Text 3写Markdown](http://blog.csdn.net/qazxswed807/article/details/51235792#t3)
*   [Sublime插件：Markdown篇](http://www.jianshu.com/p/aa30cc25c91b)
*   [MarkdownPad 2 安装和破解](http://blog.csdn.net/github_35160620/article/details/52158604)
*   [markdown语法之如何插入图片](http://blog.csdn.net/geekleee/article/details/73018194#inline)

