# HTML&CSS

## 页面组成

可能大家都有所耳闻，一个页面通常是由HTML、CSS、JavaScript 组成。

### HTML、CSS、JS之间的关系

但是，这三者之间的关系是什么呢？HTML是网页中的内容的载体，CSS的页面中内容的表现，而JS是用来实现页面上的效果。

用一个比较老掉牙的比喻，比方说我们要盖一座大楼，
HTML就是整个大楼的地基、以及钢筋混凝土的大楼整个楼体，光有这些肯定不行，最多算是烂尾楼；
所以我们就需要CSS，就相当于是大楼内外贴的瓷砖、玻璃，从而使大楼看起来是“楼样”。
光有这两样呢，还不能完全的入住，而JS呢，就像是大楼内水电煤等管道系统。
这样呢，人们才可以顺利的入住大楼，用户呢才可以顺利的浏览网页~

## HTML


知道了网页三剑客的关系了，我们先来了解一下HTML。
什么是HTML呢，HTML就是个筐

### 1.结构组成

通常一个html页面是这样的结构

```html
<!DOCTYPE html>
<html>
    <head>
        <meta charset="UTF-8">
        <title>我是标题</title>
    </head>
    <body>
        <h1>诗歌欣赏</h1>
        <div>
            <p>大王让我来巡山</p>
            <p>寻完南山寻北山</p>   
        </div>
    </body>
</html>

```

DOCTYPE 文档模式 常见的<!DOCTYPE html> 是HTML5文档写法。

...

### 2.标签

相当于你们的图层。盖大楼的砖块，所以说IT民工，我们都是搬砖的人~~

#### 开始标签、结束标签

<标签> <标签/>

#### 自闭合标签

img、input、br、link、meta等

#### 常用标签

有不同标签，相当于图层有不同种类，形状、文字、智能对象等。

- div
- 标题 h1-h6
- 链接a、列表ul、ol、li
- 文本p、span、img
- 修饰b、strong、em、i
- 表格table、tr、td
- 表单input、select、button


### 3.元素

```html
    div 是一个标签
    <div>我是元素内容</div> 就称作元素。
```

#### 块级元素
div、p、h1-h6、ul、li等等

#### 行内元素
a、span、b、strong、em、i、label等

#### 行内块元素
button、input、select、img等

#### 伪元素

::before ::after

### 4.元素属性

共有的属性 style、class、id 等等

特有的属性 a的 href target ，img的src等等


### 5.语义化

为什么要用不同标签

## CSS

到了大楼粉刷匠CSS登场了

### 1.样式

外部、内部、内联

浏览器默认样式

### 2.样式属性

#### 显示

display

#### 浮动

float

#### 定位

position top left right bottom

#### 背景

background

#### 文本

font、line-height

#### 间距与尺寸

见下

### 3.盒模型

![box](../img/box.jpg)

width、height、padding、border、box  

### 4.尺寸单位

px、em、%、rem等

### 5.选择器

标签选择器、类选择器、ID选择器、后代选择器、子选择器、伪类、通用、分组


### 6.继承、覆盖、优先级

balabala..


## JavaScript

简单介绍一下JS。

我们用CSS完成所有的静态页面，接下来我们需要用js来完成一些CSS做不到的交互动作。

就好像我们给大楼贴好了瓷砖 ，刷好了墙面，我们需要给大楼内房间安装门窗、水龙头、电闸、开关等等，这样大楼才能“住人”。

### JavaScript简介

js能做什么？

js能上九天揽月，js也可以下五洋捉鳖。

通常在一个网页中，我们用js来控制页面元素、对事件作出反应、校验用户输入、与后台数据交互、计算、实现动画动效等。

但这些都只是依托于浏览器这个环境来说，随着时间推移，js可以作的事情越来越多，它可以完成后端开发、管理数据库、写游戏、桌面应用、VR\AR、开发APP、甚至开发硬件\物联网。

当然大多这些用其他语言也可以实现，这些工作说白了也只是所谓计算机技术的成就而已。

## 线上调试

### chrome调试


