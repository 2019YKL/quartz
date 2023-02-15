---
title: "CSS样式表的引用"
---

##  引用外部样式表

```html
<html>
<head>
<link rel="stylesheet" href="mystyle.css">
</head>
<body>

<h1>This is a heading</h1>
<p>This is a paragraph.</p>

</body>
</html>
```

这里的`rel`属性有各种标签，可以参考这里：[[Html-rel属性值]]

## 引用内部样式表

```css
<style>  
body {  background-color: linen;}  
  
h1 {  color: maroon;  
  margin-left: 40px;}  
</style>
```

## 行内样式

```css
<h1 style="color:blue;text-align:center;">This is a heading</h1>
```

## 优先顺序

行内样式>内外部样式>浏览器样式

内外部样式顺序取决于摆放位置，放在后面的生效，如下列例子中，最终显示`orange`

```css
<head>  
<link rel="stylesheet" type="text/css" href="mystyle.css">  
<style>  
h1 {  color: orange;}  
</style>  
</head>
```