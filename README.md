目录

[TOC]

题目 -》 考点、知识点 -》 题目
- JS 基础知识：规定语法（ECMA 262标准）
- JS Web API：网页操作的 API（W3C标准）



1. window.onload 和 DOMContentLoaded 的区别？
    考点：页面渲染、加载过程 -》 为什么 把 css 文件的加载放在 head 标签里，把 script 文件放在 body 最底下？
2. 手写节流 throttle、防抖 debounce   
    考点：性能、体验优化
3. Promise 解决了什么问题？
    考点：JS 异步 -》 同步、异步的区别 -》 异步的应用场景 -》 定时器应该在什么场景下去使用？


![image](https://user-images.githubusercontent.com/22387652/88448616-32143480-ce72-11ea-876d-035e71625625.png)

![image](https://user-images.githubusercontent.com/22387652/88448656-a9e25f00-ce72-11ea-8333-f98e9ae17ebb.png)



# Part01-变量和类型
1. 声明变量的几种方式
2. 数据类型：有哪些类型，值类型与引用类型的区别
3. 何时使用 === ，何时使用 ==
4. 数组中用过哪些方法？
- splice 和 slice 的区别
- for-in、for-of、for、forEach 的区别
- filter、map、find、forEach 的区别
5. 数组去重
6. 手写 flatern（数组拍平）
7. 知道 concat 吗？手写一个
8. 求 a、b、c 三个数组的交集、并集、差集
```js
const a = [1, 2, 3, 4, 5, 7, 9],
    b = [1, 3, 5, 7, 9],
    c = [1, 2, 4, 6, 8];
// 求 a∩b∩c => [1]   a∪b∪c => [1-9]   a≠b≠c => [6,8]
```
9. 什么是深拷贝、浅拷贝？
10. 手写深拷贝


# Part02-执行上下文、作用域、闭包
1. 什么是作用域？分为？全局作用域、函数作用域、块级作用域（ES6 新增）
2. 闭包在实际开发中的应用场景，举例说明
3. 场景题：创建 10 个 \<a>标签，点击的时候弹出来对应的序号

# Part03-全面解析this
1. this 的不同应用场景，如何取值？
2. 手写 bind、call、slice 函数


# Part04-原型和继承
1. 如何判断一个变量是不是数组？
2. 手写一个简易的 jQuery，考虑插件和扩展性
3. class 的原型本质，怎么理解？

# Part05-单线程、异步

# Part06-JS Web API（BOM、DOM、AJAX、事件）
1. DOM 是哪种数据结构？
2. DOM 操作常用的 API
3. attribute 和 property 的区别
4. 一次性插入多个 DOM 节点，考虑性能
5. 手写一个简易的 AJAX
6. 跨域的常用实现方式


# Part07-页面渲染与性能优化


# ES 6/7/8/9



# 各种手写代码
1. 手写深拷贝
2. 手写 flat
3. 手写 bind 函数


<!-- # Part4 异步和性能
1. 重学 JS 系列 - JS是单线程的
2. 重学 JS 系列 - 任务队列及Event-loop
3. 重学 JS 系列 - 宏任务和微任务
4. 重学 JS 系列 - AJAX及跨域
5. 重学 JS 系列 - DOM
6. 重学 JS 系列 - 事件机制 -->



<!-- # JS 专题系列目录
- JS专题系列（1）- 字符串（回流等）
- JS专题系列（2）- 数组（去重、扁平化、最值等）
- JS专题系列（3）- 深浅拷贝
- JS专题系列（4）- 防抖、节流
- JS专题系列（5）- 性能优化
- JS专题系列（6）- 正则 -->

