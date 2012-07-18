---
layout: post
title: "函数式C#的尝试"
date: 2012-07-18 07:20
comments: true
categories: [函数式, C#, lambda]
author: huangcd
---

由于工作的需要，最近需要大量使用MS系的产品，
Visual Studio和C#首当其冲（吐槽一下，
Visual Studio的快捷键和Intelligence太弱了，
好不容易有个ReSharper还是收费的。。。）

不得不说，几年不见，C#跟以前长得都不一样了。
我印象中的C#基本上是Java的翻版，现在一看，
我勒个去，各种lambda、LINQ满天飞。。。

<!--more-->

lambda是我喜欢的，作为一个低级的Haskell爱好者
和Python的中度用户，lambda表达式为链式处理带来的
快捷体验是无可比拟的，
Python的map、reduce、filter
等函数式方法以及Generator Expression是谁用谁知道啊。

粗略看了一下C#，发现居然没有map、reduce、filter几个函数，
深感无力，决定自己轮子一下：

{% gist 3133167 %}