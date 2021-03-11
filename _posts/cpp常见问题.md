---
layout:     post
title:      cpp常见问题
date:       2021-3-7
author:     skymelody
header-img: img/the-first.png
catalog: true
tags:
    - cpp
---

1. 构造函数可以是虚函数吗？为什么？

   不行，cpp对象在构造的时候需要初始化虚函数指针， 这个过程在构造函数中完成。

2. 如果没有定义默认构造函数， 编译器会为你合成一个吗？

   不一定，有四种情况。

   ![img_1](../img-post/cpp常见问题_1.png)