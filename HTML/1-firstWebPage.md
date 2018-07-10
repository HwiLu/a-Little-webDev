1.网页标题及内容标题

**浏览器是通过Content-Type这个标记来了解文件类型的，而不是后缀名。说明这是个html文件**

**charset=UTF-8：编码方式，用的是utf-8编码**

```html

<!DOCTYPE HTML>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
        <title>制作我的第一个网页</title>
    </head>
    <body>
        <h1>hello world</h1>
    </body>
</html>

```

2.添加css示例

html： HTML是网页内容的载体。
CSS样式：是表现。就像网页的外衣。比如，标题字体、颜色变化，或为标题加入背景图片、边框等。所有这些用来改变内容外观的东西称之为表现。
JavaScript：是用来实现网页上的特效效果。如：鼠标滑过弹出下拉菜单。或鼠标滑过表格的背景颜色改变。还有焦点新闻（新闻图片）的轮换。可以这么理解，有动画的，有交互的一般都是用JavaScript来实现的。
```html

<!DOCTYPE HTML>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
        <title>Html和CSS的关系</title>
        <style type="text/css">
        h1{
            front-size:12px;
            color:#930;
            text-align:center;
        }
        </style>
    </head>
    <body>
        <h1>Hello World!</h1>
    </body>
</html>
```
3.添加段落和图片

```html
<!DOCTYPE HTML>
<html>
    <head>
        <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
        <title>认识html标签</title>
    </head>


    <body>
        <h1>标题</h1>
        <p>段落1</p>
        <p>段落2</p>
        <img src="http://XXX.com/图片.jpg" >
    </body>


</html>
```

4.标签

```html

 < >  </ >
如：
（1） <p></p>

（2） <div></div>

（3） <span></span>
嵌套：
<div><p></p></div>
```
不区分大小写，建议使用小写
5.代码注释

```html
  <!--我是一行注释-->
```

6.标签

span
em
strong
`<em> `默认用斜体表示，`<strong> `用粗体表示

7.文章的标题标签

标题标签一共有6个，h1、h2、h3、h4、h5、h6分别为一级标题、二级标题、三级标题、四级标题、五级标题、六级标题。并且依据重要性递减。`<h1>`是最高的等级。
注意：因为h1标签在网页中比较重要，所以一般h1标签被用在网站名称上。

8.使用`<span>`标签为文字设置单独样式

```html
<!DOCTYPE HTML>
<html>
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
<title>了不起的盖茨比</title>
<style>
span{
    color:blue;
}
</style>
</head>
<body>
    <p>为了追寻他的<span>美国梦</span></p>
    <p>菲茨杰拉德</p>
</body>
</html>
```

9.短文本引用

`<q></q>`

10.长文本引用

`<blockquote> </blockquote>

11.分行显示文本

`<br />`

12.空格

```html
&nbsp;
```
13.水平横线

```html
html4.01版本 <hr>

xhtml1.0版本 <hr />
```
`<hr />`标签和`<br />`标签一样也是一个空标签，所以只有一个开始标签，没有结束标签。

14.地址标签

`<address></address>`

15.代码标签

`<code></code>`

16.大段代码

`<pre>语言代码段</pre>`
代码段内的空格和换行符都会被保留
17.ul标签，添加无序列表

无序列表
语法：
```html
<ul>
  <li>精彩少年</li>
  <li>美丽突然出现</li>
  <li>触动心灵的旋律</li>
</ul>
```
18.ol标签，添加有序列表

语法
```html

<ol>
   <li>信息</li>
   <li>信息</li>
   ......
</ol>
```

19.`div`实现分栏布局

```html
<div>
	...
</div>
```

20.给div命名

```html
<div id="div名称">

</div>
```

