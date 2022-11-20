#markdown标题

#一级标题

##二级标题

###三级标题

####四级标题

#####五级标题

######六级标题

#markdown文字

*斜体文字*

**加粗文字**

***粗斜体文字***

#markdown列表

PS：注意列表之间以空格隔开

- 无序列表

+ 无序列表

* 无序列表

1. 有序列表

2. 有序列表

#混合用法

- 无序列表
1. 有序列表
+ 无序列表
2.有序列表

#markdown区块

>最外层

>>第一层

>>>第二层

#与列表混合使用

##方法一

>列表

>1. 有序列表

>- 无序序列表

##方法二

1. 第一项

>测试

+ 第二项

>测试

#markdown代码

如果是段落上的一个函数或片段的代码可以用反引号把它包起来（`）

`<p>这是一个段落</p>`这是一个段落

##代码区块
PS：四个反引号或者一个制表符（tab）

```
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>这是一个标题</title>
</head>
<body>
    <h1>我的第一个标题</h1>
    <p>我的第一个段落。</p>
</body>
</html>
```

    <h1>我的第一个标题</h1>

#markdown链接

[链接名称](链接地址)

或者

<链接地址>

[知乎](https://www.zhihu.com/)

##高级链接

通过变量来设置一个链接，变量赋值在文档末尾进行：

这个链接用 1 作为网址变量 [Google][1]
这个链接用 runoob 作为网址变量 [Runoob][runoob]
然后在文档的结尾为变量赋值（网址）

  [1]: http://www.google.com/
  [runoob]: http://www.runoob.com/

 #markdown图片
 
 Markdown 图片语法格式如下：

>`![alt 属性文本](图片地址)`

>!`[alt 属性文本](图片地址 "可选标题")`

    开头一个感叹号 !
    接着一个方括号，里面放上图片的替代文字
    接着一个普通括号，里面放上图片的网址，最后还可以用引号包住并加上选择性的 'title' 属性的文字。

使用实例：

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png)

![RUNOOB 图标](http://static.runoob.com/images/runoob-logo.png "RUNOOB")

当然，你也可以像网址那样对图片网址使用变量:

这个链接用 1 作为网址变量 [RUNOOB][1].
然后在文档的结尾为变量赋值（网址）

[1]: http://static.runoob.com/images/runoob-logo.png

Markdown 还没有办法指定图片的高度与宽度，如需要，可以使用普通的` <img>` 标签。

```
<img decoding="async" src="http://static.runoob.com/images/runoob-logo.png" width="50%">
```

#Markdown表格

Markdown 制作表格使用 | 来分隔不同的单元格，使用 - 来分隔表头和其他行。

语法格式如下：

>|  表头   | 表头  |

>|  ----  | ----  |

>| 单元格  | 单元格 |

>| 单元格  | 单元格 |

##对齐方式

我们可以设置表格的对齐方式：

    -: 设置内容和标题栏居右对齐。

    :- 设置内容和标题栏居左对齐。

    :-: 设置内容和标题栏居中对齐。
    