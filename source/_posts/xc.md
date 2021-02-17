---
title: xc
date: 2021-02-17 18:31:41
tags:
---
关于lua中冒号:的使用
# :可以代替.点分语法，更加简洁，使用时可以用:后接函数直接带入运算
eg. `a={}`
`a:function(v)==a.function(a,v)--冒号既可用于创建函数，也可用于使用函数`

eg. `local f=assert(io.open(filename,"r"))`
  `local t = f:read("a")`
  `f:close()`