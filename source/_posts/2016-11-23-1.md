---
layout: post
title: Angular指令数据绑定
date: 2016-11-23 08:55
comments: true
tags:
  - Angular
  - angular基础
  - 数据绑定
---


> 准备项目示例
 参考源码： https://github.com/momicafe/pro-angularjs/blob/master/Chapter%2009/Listing%2001.html
 <!-- more -->

* Angular数据绑定有几种类型?
*  Angular如何修改内联绑定符  `{{XXXX}}` ?
* Angular如何隐藏模板标记?
* Angular scope如何工作?
* Angular ng-bind 与 ng-bind-template区别?
        ```
                 <div>
                      There are <span ng-bind="todos.length"></span> items
                  </div>
                  <div ng-bind-template=
                       "First: {{todos[0].action}}. Second: {{todos[1].action}}">
                  </div>
        ```
        说明：`ng-bind` 只能处理单个数据绑定表达式， `ng-bind-template`可以处理多个数据绑定。所以一般用内联绑定符   {{  和 }}  （双括号，草拟娘的，hexo编译会自动屏蔽双大括号这个符号，MB~）  绑定数据。 傻子才会用这两个。O(∩_∩)O~

* asd
