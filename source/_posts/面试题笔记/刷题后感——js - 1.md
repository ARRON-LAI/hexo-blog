---
title: 刷题后感——js - 1
id: 68
categories:
  - 学海无涯我游啊游
  - Javascript
date: 2017-02-13 23:28:56
tags:
---

1.  
{% qnimg js/1-1.png title:js_1-1 alt:js_1-1 %}
green; blue - this指针对于普通函数调用指向window对象。
2.
{% qnimg js/1-2.png title:js_1-2 alt:js_1-2 %}
回调机制：回调函数会被放到event-loop等待线程中的函数执行结束后执行。
3.  字符串转bollean：空-&gt;false
4.  闭包：读取函数内部变量，可以使这些值一直保存在内存中。
5.  css属性写法去掉‘-’改为驼峰写法即为js中属性名称。
6.  1+ +"2" + "2" = 32; 1+"2"+"2" = 122; "A"-"B"+2 = NaN; "A"-"B"+"2" = NaN2; 单独+是一元操作符，调用Number()函数获得取值。加法会变成字符串，减法变成数字。
7.  <div class="result-question-box">
<div class="subject-question">
<div>输出对象中值大于2的key的数组</div>
<div>var data = {a: 1, b: 2, c: 3, d: 4};</div>
<div>Object.keys(data).filter(function(x) { return <span class="blank-num">__</span> ;})</div>
<div>期待输出：[“c”,”d”]</div>
<div>return data[x]&gt;2</div>
<div>Object.keys(object)返回object可枚举的属性和方法名称，Array。</div>
<div>Array.filter(function)按条件对Array筛选并返回。</div>
</div>
</div>
