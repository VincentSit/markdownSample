---
layout: post
title: "5分钟掌握 Markdown 常用语法"
date: 2013-09-21 05:21
comments: true
categories: Markdown

---

## 标题
`#`+`空格`+`标题`。
通过 1 到 6 个 `#` 可以指定不同字号的标题，1 个 `#` 代表一级标题（最大），6 个 `#` 代表六级标题（最小）。

{% img /images/blog2013/Sep/learnMarkdown1.png %}
<!-- more -->

标题还有一种比较少用的语法是：输入标题后换行，在第二行写三个以上 `=` 或 `-`，如：

{% img /images/blog2013/Sep/learnMarkdown8.png %}

## 加粗和倾斜
倾斜：`*要倾斜的文字*` 或 `_要倾斜的文字_`；
加粗：`**要加粗的文字**` 或 `__要加粗的文字__`。


在文字的两端各添加一个 `*` 或 `_` 表示这段文字倾斜，各添加两个 `*` 或 `_` 表示这段文字加粗。

{% img /images/blog2013/Sep/learnMarkdown2.png %}

## 删除线
`~~文字~~`。下面效果的代码是 `~~删除线~~`   
~~删除线~~。

## 链接
`[文字](点击文字后链接到的 URL "标题")`。   
如 [Google](www.google.com) 的代码是：`[Google](www.google.com)` 我省略掉了标题。

## 图片
`![文字](点击文字后链接到的 URL "标题")`

图片和链接和像，只是在链接的语法前面加上一个 `!`。图片的 **文字** 和 **标题** 都可以省略掉。
如下面的图片代码就是 `![](https://www.google.com/images/srpr/logo4w.png)`。

![](https://www.google.com/images/srpr/logo4w.png)

## 引用
`> 引用的文字`

引用只需要在引用的文字前面加上 `>`+`空格` 即可。如果是多层引用就多个 `>`。
如下面的引用代码是 `> Hello Markdown!`。
> Hello Markdown!.

## 列表
`序号. 文字` 或 `* 文字`。注意 `序号.` 或 `*` 与文字之间都需要加一个 `空格`。支持嵌套。

1. 列表 A
2. 列表 A
3. * 嵌套 A
   * 嵌套 A
   * 嵌套 A

或

* 列表 B
* 列表 B
* 1. 嵌套 B 
  2. 嵌套 B
  3. 嵌套 B

上面效果的代码是：

{% img /images/blog2013/Sep/learnMarkdown3.png %}

## 分割线
`___` 或 `***` 或 `- - - -`， 效果都是一样的：
***

## 强制换行
`文字后加两个或两个以上空格`。下面是对比效果图：  
回车但未强制换行：

{% img /images/blog2013/Sep/learnMarkdown4.png %}

{% img /images/blog2013/Sep/learnMarkdown5.png %}

回车并强制换行：

{% img /images/blog2013/Sep/learnMarkdown6.png %}

{% img /images/blog2013/Sep/learnMarkdown7.png %}

## 代码
一行的情况：首尾加上`` ` `` 即可，如：   
`#include <stdlib.h>`   
的代码是 `` `#include <stdlib.h>` ``。   
多行的情况：每行缩进 4 个 `空格` 或一个 `Tab`，如

	#include <stdlib.h>   
	#include <stdio.h>   
	#include <conio.h>   
代码是:

{% img /images/blog2013/Sep/learnMarkdown9.png %}

你可以从 [Dropbox](https://www.dropbox.com/s/pwy02rsbxdmvnuu/2013-09-21-learn-markdown-syntax-in-5-minutes.markdown) 或 [百度网盘](http://pan.baidu.com/share/link?shareid=454598908&uk=1141297894) 下载本文的 Markdown。