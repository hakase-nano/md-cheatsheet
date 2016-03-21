# md-cheatsheet

1.标题
-----
- H1标题 <>H1标题 <h1>
H1标题[换行]----- or # H1标题

- H2标题 <h2>
H2标题[换行]===== or ## H2标题


2.段落
-----
- 段落 <p>
连续的多行为一个段落(不进行换行！)，段落间用空行分隔

- 换行 <br/>
在行末加上2个空格

- 水平分割线 <hr/>
- - - or * * *


3.字体样式
-----
- 斜体 <i>
*斜体*

- 粗体 <b>
**粗体**

- 粗斜体 <i><b>
***粗斜体***

- 删除线 <del>
~~删除内容~~

- 上标 <sup>
正常内容^上标内容
若上标内容有空格:
正常内容^(上标内容)


4.代码
-----
- 代码 <code>
`代码`

- 代码段 <pre><code>
[tab/4空格]代码


5.文字块
-----
- 块引用 <blockquote>
> 第一行内容
> 第二行内容
>> 嵌套块引用
注1: 可嵌套任意层数
注2: 多个连续的块引用会被连成一个块引用，即使中间有空行

- 无序列表 <ul><li>
* 表项
    * 子表项
注: */+/-这三个符号功能一样 可混用

- 有序列表 <ol><li>
1. 表项
注1: 有序无序列表在同一层级不可混用
注2: 但可互相嵌套(见高级玩法)


6.链接
-----
- 链接 <a>
[链接文字](链接地址)
[谷歌](https://www.google.com.hk/)

- 引用链接
[链接文字][链接引用标签]
[链接引用标签]: 链接地址
or
[链接文字][链接引用标签]
[链接引用标签]: (链接地址 "提示信息")
[百度][b2]
... ...
[b2]: (http://www.baidu.com/ "QuanJiaTong")

- 图片 <img>
![标签](链接)
![asuka](http://i2.pixiv.net/img54/img/asukaziye/mobile/40099644_240mw.jpg)


7.转义符号 \
-----


8.高级用法
-----
- 有序列表嵌套无序列表
1. Lists in a list item:  
    - Indented four spaces.  
        * indented eight spaces.  
    - Four spaces again.  
  
2. Blockquotes in a list item:  
    > Skip a line and  
    > indent the >'s four spaces.  
  
3. Preformatted text in a list item:  
  
        Skip a line and indent ***eight*** spaces.  
        That's four spaces for the list  
        and four to trigger the code block.  

- 块引用里面嵌套
> - A list in a blockquote  
> - With a > and space in front of it  
>    * A sublist  
-----  
>     Indent ***five*** spaces total. The first  
>     one is part of the blockquote designator.  
