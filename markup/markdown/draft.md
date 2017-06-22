# Markdown

编写Web文档

## 目录

* [概述](overview.md)
* [语法](syntax.md)
* [草稿](draft.md)

## 推荐资料

* [Markdown简易教程](http://www.markdowntutorial.com/)
* [Markdown中文文档](http://wowubuntu.com/markdown/)


# 概述

使用易读易写的纯文本格式编写文档，然后转换成有效的XHTML(或者HTML)文档的轻量级标记语言

> * 语法全由一些符号组成
> * 兼容HTML
>   * HTML块级元素另起一行并空行隔开，且不解析块级元素内的Markdown语法
>   * HTML内联元素任意使用，且解析内联元素内的Markdown语法
> * 智能转义特殊字符(<,&等)


# 语法

## 字体

```markdown
_斜体_
*斜体*
__粗体__
**粗体**
```

## 代码

```markdown
`代码`
```

## 标题

```markdown
#标题1
##标题2
###标题3
####标题4
#####标题5
######标题6
```

## 段落

```markdown
空行
段落1
空行
段落2
空行
```

## 换行

```markdown
空行
文本1空格空格
文本2
空行
```

## 引用

```markdown
> 引用
> 继续引用
```

## 代码块

```markdown
四个空格代码1
四个空格代码2
```

## 分隔线

```markdown
三个或三个以上*或-或_
```

## 链接

```markdown
行内链接
[谷歌](www.google.com "title")

参考链接
[谷歌][google]

[google]: www.google.com "title"

自动链接
<www.google.com>
```

## 图片

```markdown
行内图片
[背景图片](/images/bg.jpg "title")

参考图片
[背景图片][background]

[background]: /images/bg.jpg "title"
```

## 列表

```markdown
无序列表
* item 1
* item 2
* item 3

有序列表
1. item 1
2. item 2
3. item 3
```

## 转义

使用反斜杠转义

```markdown
\*星号 不是斜体\*
```
