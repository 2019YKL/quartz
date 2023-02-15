---
title: "CSS选择器"
aliases: 
tags: 
author:
source:
date created: 星期二, 二月 14日 2023, 8:54:38 晚上
date modified: 星期三, 二月 15日 2023, 11:56:48 晚上
---

>[!note]
>所谓选择器，就是怎么选择，这底下讲解了怎么选中元素。


## 元素选择

使用元素名称选择，例如`<p>`

## id选择

使用`#id`的形式来选择，例如

```css
#paral{color: red;}
```

html里则是这样写

```html
<p id="paral">text</p>
```

## 类选择

使用`.classname`来选择，例如

```css
.box1{text-align: center}
```

还可以指定特定的HTML元素受影响，例如

```css
p.box1{...}
```

## 引用多类

HTML中允许引用多个CSS类，类中间用逗号隔开，方式如下

```html
<p large center>text</p>
```

## 通用选择

用`*`来表示，如

```css
*{...}
```

## 分组选择

如果他们样式相同的，可以精简表示，不同元素用逗号隔开

```css
h1,h2,p{...}
```

