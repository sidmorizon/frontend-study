### 目录

# 准备工作

- 使用[Cloud9](http://c9.io)作为在线编码环境

# 基本角色

前端开发主要包含三个角色：HTML、CSS、JS

- HTML是基础结构，用于承载基本内容和数据
- CSS用于美化装饰，网站颜值的高低关键靠她
- JS用于实现逻辑、体验、动画和交互，现代网站必不可少

以房子类比，HTML相当于毛坯房，CSS类似于装修，JS相当于协调一切的东西，例如水电网络等，让整个房间良好的运转起来。

# 基础结构

下面来看一下最基本的HTML结构是怎么样的

``` html
<!DOCTYPE html>
<html lang="zh-CN">

<head>
  <meta charset="UTF-8" />
  <title>我是网页标题</title>
</head>

<body>
  <a href="http://image.baidu.com/channel/star">我是链接</a>
  <h1>我是文档一级标题</h1>
  <h2>我是文档二级标题</h2>
  <p>我是文档段落</p>
  <img src="http://h.hiphotos.baidu.com/image/w%3D310/sign=1db9b167d03f8794d3ff4e2fe2190ead/f636afc379310a553ce58c2bb34543a98326102f.jpg" alt="我是美女图片" />
</body>

</html>
```

> 提示: 在Cloud9编辑器里可以直接输入感叹号`!+TAB`快速生成HTML基础模板

# 概念解释

- 文档(document)
    
    整段代码称为**文档**
    
- 标签(tag)

    **文档**里用`<xxx>`表示的被称为**标签**,分为成对的起始标签(例如`<a>`)和结束标签(例如`</a>`)或自闭合标签(例如`<img/>`)
    
- 元素(element)

     一对标签构成了**元素**,例如`<a href="http://www.baidu.com">打开百度</a>`

- 属性(property或attribute)

    标签上可以有自己的属性,例如`<a href="http://www.baidu.com">打开百度</a>`,其中`href`是属性名,`http://www.baidu.com`是该属性的值

> 注意: 

>  - 标签必须完整闭合

>  - 标签必须按层级嵌套,禁止交错嵌套

>  - 属性值必须用引号包裹(如果值本身包含引号,请单引号和双引号交替使用,例如`href="It's me"`)
