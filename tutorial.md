# HTML&CSS

## 页面组成

可能大家都有所耳闻，一个页面通常是又HTML、CSS、Javascript 组成。

### HTML、CSS、JS之间的关系

但是，这三者之间的关系是什么呢？HTML是网页中的内容的载体，CSS的页面中内容的表现，而JS是用来实现页面上的效果。

用一个比较老掉牙的比喻，比方说我们要盖一座大楼，
HTML就是整个大楼的地基、以及钢筋混凝土的大楼整个楼体，光有这些肯定不行，最多算是烂尾楼；
所以我们就需要CSS，就相当于是大楼内外贴的瓷砖、玻璃，从而使大楼看起来是“楼样”。
光有这两样呢，还不能完全的入住，而JS呢，就像是大楼内水电煤等管道系统。
这样呢，人们才可以顺利的入住大楼，用户呢才可以顺利的浏览网页~

## HTML


知道了网页三剑客的关系了，我们先来了解一下HTML。
什么是HTML呢，HTML是

### 结构组成

通常一个html页面是这样的结构

```
<!DOCTYPE html>
<html>
    <head>
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

DOCTYPE 是什么，html

### 标签

开始标签、结束标签

相当于你们的图层。盖大楼的砖块，所有IT民工，我们都是搬砖的人~~

#### 自闭合标签

img、input、br、link、meta等

#### 常用标签

div，标题 h1-h6，链接a、列表ul、ol、li，文本p、span，修饰b、strong、em、i，表格table、tr、td，表单input、select、button。

相当于图层有不同种类，形状、文字、智能对象等

### 元素

```
    div 是一个标签
    <div>我是元素内容</div> 就称作元素。
```

#### 块级元素
div、p、h1-h6、ul、li等等

#### 行内元素
a、span、b、strong、em、i、lebal等

### 行内块元素
button、input、select、img等

### 伪元素

::before ::after

### 元素属性

共有的属性 style、class、id

特有是属性 a的 href target ，img的src等等


### 语义化

为什么要用不同标签

## CSS

到了粉刷匠登场了

### 样式写法位置

外部、内部、内联

浏览器默认

### 样式属性

显示

display

定位

position top left right bottom

背景



文本

间距与尺寸 见下

### 盒模型

图

width、height、padding、border、box  

#### 尺寸单位
px、em、%、rem等

### 选择器

标签选择器、类选择器、ID选择器、后代选择器、子选择器、伪类



### 继承、覆盖、优先级


## 线上调试

### chrome调试


