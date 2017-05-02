## 标题
标题是每篇文章都需要也是最常用的格式，在 Markdown 中，如果一段文字被定义为标题，只要在这段文字前加 # 号(需要空格隔开)即可。

# 一级标题

## 二级标题

### 三级标题

以此类推，总共六级标题，建议在井号后加一个空格，这是最标准的 Markdown 语法。

## 列表

熟悉 HTML 的同学肯定知道有序列表与无序列表的区别，在 Markdown 下，列表的显示只需要在文字前加上 - 或 * 即可变为无序列表，有序列表则直接在文字前加1. 2. 3. 符号要和文字之间加上一个字符的空格。

#### 无序列表
    * list1    
    * list2
    * list3
    * list4
##### 另一种样式
    - list1
    - list2
    - list3
#### 有序列表
    1. list1
    2. list2
    3. list3
## 引用

如果你需要引用一小段别处的句子，那么就要用引用的格式。

> 例如这样

只需要在文本前加入 > 这种尖括号（大于号）即可

## 图片与链接
插入链接与插入图片的语法很像，区别在一个 !号

```
图片为：![](){ImgCap}{/ImgCap}

链接为：[]()
```

插入图片的地址需要图床，这里推荐[围脖图床修复计划](http://weibotuchuang.sinaapp.com/) 与 [CloudApp](http://www.getcloudapp.com/) 的服务，生成URL地址即可。

![别人的图图](http://olz1di9xf.bkt.clouddn.com/2014082501.jpg)

## 粗体与斜体

Markdown 的粗体和斜体也非常简单，用两个 * 包含一段文本就是粗体的语法，用一个 * （_下划线也可以）包含一段文本就是斜体的语法。

例如：这里是 **粗体** 这里是 _斜体_ *斜体2*

## 表格

表格是我觉得 Markdown 比较累人的地方，例子如下：

```
| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |
```

这种语法生成的表格如下：

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## 代码框

如果你是个程序猿，需要在文章里优雅的引用代码框，在 Markdown下实现也非常简单，只需要用两个 `` 多行使用：```，单行使用：``把中间的代码包裹起来。图例：

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```
## 分割线

分割线的语法只需要三个 * 号：`***`，例如：

这里是分割线

***

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/xiaorg/xiaorg.github.io/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://help.github.com/categories/github-pages-basics/) or [contact support](https://github.com/contact) and we’ll help you sort it out.
