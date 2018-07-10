1. 网页标题及内容标题

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

2. 添加css示例

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
3. 添加段落和图片

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

4. 标签

<> </>
如：
（1） <p></p>

（2） <div></div>

（3） <span></span>
嵌套：
<div><p></p></div>
