

<div align="center">
  <a href="#">
    <!-- <img src="https://camo.githubusercontent.com/f85e9f52aec085fb258e80d7dcbf0eb5ec93dd65/68747470733a2f2f63646e2e7261776769742e636f6d2f79616e677368756e2f66726f6e742d656e642d696e746572766965772d68616e64626f6f6b2f323364383963382f6173736574732f7363726f6c6c2e737667" alt="Interview Plan" width="400"/> -->
    <img src="https://gw.alicdn.com/imgextra/i2/O1CN01PB5Inc1foJyHZQ0EX_!!6000000004053-2-tps-868-467.png" alt="Interview Plan" width="100%"/>
    </a>
  <br>
</div>

## 整体大纲
- [技术跟进](#%e6%8a%80%e6%9c%af%e8%b7%9f%e8%bf%9b)
- [资料](#%e8%b5%84%e6%96%99)
- [语言基础部分](#%e8%af%ad%e8%a8%80%e5%9f%ba%e7%a1%80%e9%83%a8%e5%88%86)
- [浏览器](#%e6%b5%8f%e8%a7%88%e5%99%a8)
- [计算机网络](#%e8%ae%a1%e7%ae%97%e6%9c%ba%e7%bd%91%e7%bb%9c)
- [业务层面](#%e4%b8%9a%e5%8a%a1%e5%b1%82%e9%9d%a2)
- [React和Vue实现原理](#react%e5%92%8cvue%e5%ae%9e%e7%8e%b0%e5%8e%9f%e7%90%86)
- [Node](#node)
- [Webpack](#webpack)
- [Web安全](#web%e5%ae%89%e5%85%a8)
- [源码阅读](#%e6%ba%90%e7%a0%81%e9%98%85%e8%af%bb)
- [设计模式](#%e8%ae%be%e8%ae%a1%e6%a8%a1%e5%bc%8f)
- [数据结构和算法](#%e6%95%b0%e6%8d%ae%e7%bb%93%e6%9e%84%e5%92%8c%e7%ae%97%e6%b3%95)
- [现代前沿技术](#%e7%8e%b0%e4%bb%a3%e5%89%8d%e6%b2%bf%e6%8a%80%e6%9c%af)
- [Linux](#linux)
- [Python](#python)

## 技术跟进

- 【完成】react hooks迁移
- 【进行中】前端工程化体系(工程方向、跨端方向)
  - 开发webpack插件
  - 开发babel插件
  - jsx-compiler 小程序转化的编译器(给予babel的应用层)
  - TypeScript 编译器（底层编译）
  - babel相关项目
  - [深入理解TypeScript](https://jkchao.github.io/typescript-book-chinese/project/dynamicImportExpressions.html)
  - [微内核架构应用研究](https://yunsong0922.github.io/2018/12/09/%E5%BE%AE%E5%86%85%E6%A0%B8%E6%9E%B6%E6%9E%84%E5%BA%94%E7%94%A8%E7%A0%94%E7%A9%B6/)
  - [透过现象看本质: 常见的前端架构风格和案例](https://juejin.im/post/5d7ffad551882545ff173083?utm_source=gold_browser_extension#heading-9)
- 微前端技术架构
  - [qiankun](https://github.com/Genluo/qiankun)： 支付宝微前端解决方案
  - [icestark](https://github.com/ice-lab/icestark): 淘系微前端解决方案
- Node C++ addons开发
- WebAssembly技术上的融合： C++、Rust、AssemblyScript
- [浏览器工作原理与实践](http://blog.poetries.top/browser-working-principle/guide/part1/lesson01.html#%E8%BF%9B%E7%A8%8B%E5%92%8C%E7%BA%BF%E7%A8%8B)

- serverless 服务上云
  - [将你的服务部署到ZEIT](https://cnodejs.org/topic/5de4705539af564604bbfcb8)

- [Node后端框架学习](https://github.com/Genluo/Blog/issues/61)
  - koa-ts
  - NestJs


## 资料

- [文章收集](./文章收集.md)
- [工具类](./工具.md)
- [前端性能优化](https://alienzhou.github.io/fe-performance-journey/)

## 语言基础部分

- [调用堆栈](https://github.com/Genluo/Blog/issues/7)
- [作用域和闭包](https://github.com/Genluo/Blog/issues/8)
- [this全面解析](https://github.com/Genluo/Blog/issues/9)
- [对象全面解析](https://github.com/Genluo/Blog/issues/10)
- [原型链](https://github.com/Genluo/Blog/issues/11)
- [深浅拷贝](https://github.com/Genluo/Blog/issues/12)
- [位操作](https://github.com/Genluo/Blog/issues/13)
- [Promise规范解读](https://github.com/Genluo/Blog/issues/14)
- [处理异步问题的方法](https://github.com/Genluo/Blog/issues/15)
- [函数防抖/节流原理](https://github.com/Genluo/Blog/issues/16)
- [垃圾回收机制](https://github.com/Genluo/Blog/issues/17)
- [模块化原理](https://github.com/Genluo/Blog/issues/18)
- [数据类型判断](https://github.com/Genluo/Blog/issues/19)
- 语言层面性能优化
- ES6重点难点
  - Symbol
  - 修饰器
  - Reflect

## 浏览器

- [浏览器整体架构](https://github.com/Genluo/Blog/issues/20)
- [Event loop原理](https://github.com/Genluo/Blog/issues/21)
- [浏览器渲染机制](https://github.com/Genluo/Blog/issues/22)
- 浏览器性能调试及其性能优化技巧
- 跨域原因及其解决方法
- 浏览器如何执行Javascript代码
- [浏览器存储技术](https://github.com/Genluo/Blog/issues/23)
- 浏览器缓存机制
- 浏览器脚本演进历史
- 浏览器层面性能优化

## 计算机网络

- [TCP连接](https://github.com/Genluo/Blog/issues/24)
- [DNS解析](https://github.com/Genluo/Blog/issues/25)
- [HTTP2.0、HTTP3.0](https://github.com/Genluo/Blog/issues/26)
- 七层网络结构
- RESTful规范
- [Http持久连接及其现代方法](https://github.com/Genluo/Blog/issues/27)
- [http缓存](https://github.com/Genluo/Blog/issues/28)
- 安全认证方式
- 网络层面性能优化

## 业务层面

- 前端用户数据分析
- 搜索引擎优化及其基础
- 移动端适配性
- [单点登录系统实现原理](https://github.com/Genluo/Blog/issues/59)
- 搭建系统整体原理及其构建流程
- 如何实现骨架屏
- 帧动画实现思路
- Postmessage实现方式
- 反向代理的几种开发流程
- CDN原理
- 同构渲染、预渲染之间的区别
- 埋点实现思路

## React和Vue实现原理

- [MV*模式](https://github.com/Genluo/Blog/issues/29)
- [React和Vue核心思想](https://github.com/Genluo/Blog/issues/30)
- [VirtualDom原理和DIff算法](https://github.com/Genluo/Blog/issues/37)
- [immutable对象构建算法](https://github.com/Genluo/Blog/issues/31)
- [react生命周期演进过程](https://github.com/Genluo/Blog/issues/60)
- [React最新特性学习](https://github.com/Genluo/Blog/issues/32)
- [CSR（Client Side Rendering）网页首帧优化总结](https://github.com/Genluo/Blog/issues/33)
- [Redux原理](https://github.com/Genluo/Blog/issues/34)
- [前端路由控制原理](https://github.com/Genluo/Blog/issues/35)
- React性能优化
- React事件系统
- [MVVM双向绑定原理与实现原理](https://github.com/Genluo/Blog/issues/36)
- hooks核心思想
- vue中双向绑定

## Node

- 核心模块
  - 缓存、流、模块
    - [Buffer学习](https://github.com/Genluo/Blog/issues/40)
    - [stream](https://github.com/Genluo/Blog/issues/41)
    - [fs](https://github.com/Genluo/Blog/issues/42)
    - [path](https://github.com/Genluo/Blog/issues/43)
  - 网络处理相关模块
    - [net](https://github.com/Genluo/Blog/issues/44)
    - [tls](https://github.com/Genluo/Blog/issues/50)
    - [dgram](https://github.com/Genluo/Blog/issues/45)
    - [http](https://github.com/Genluo/Blog/issues/49)
  - 系统与进程、集群
    - [os](https://github.com/Genluo/Blog/issues/46)
    - [process](https://github.com/Genluo/Blog/issues/47)
    - [child_process](https://github.com/Genluo/Blog/issues/48)
    - [cluster](https://github.com/Genluo/Blog/issues/51)
  - 辅助模块URL处理，工具类
    - [url](https://github.com/Genluo/Blog/issues/53)
    - util
  - 模块、全局对象
    - [global](./issues/54)
    - [module](https://github.com/Genluo/Blog/issues/55)
    - [console](https://github.com/Genluo/Blog/issues/56)
    - timers
  - 加密、编码、压缩
    - [string_decoder](https://github.com/Genluo/Blog/issues/52)
    - crypto
    - zlib
- 实现Http2.0
- 事件循环流程
- 核心模块的认识
- 流的概念
- socket编程
- 模块化实现原理
- NPM工具详解
- 了解Libuv
- 缓存方案设计及其常见缓存算法
- 待续

## Webpack

- 项目实战
- babel原理
- webpack整体架构
- 未完待续

## Web安全

- XSS/CSRF
- 待续

## 源码阅读

- [Koa](https://github.com/koajs/koa)
- [Eggjs](https://github.com/eggjs/egg)
- [MVVM](https://github.com/DMQ/mvvm)
- [koa-ts](https://github.com/unix/koa-ts)
  - [typedi](https://github.com/typestack/typedi) : 依赖注入容器
- [icestore](https://github.com/ice-lab/icestore)

## 设计模式

- 设计模式六大原则
- 看懂UML图，流程图
- 23类设计模式（创建类型（5）、结构类型（7）、行为类型（7））
- node中常见的设计模式

## 数据结构和算法

- 剑指Offer算法
- [设计一个最小栈](https://github.com/Genluo/Blog/issues/39)
- 时间复杂度和空间复杂度
- 算法设计常用思想
  - 贪婪法
  - 分治法
  - 动态规划
  - 信息复用
  - 回溯算法
  - 解空间的穷举法
- 常见算法
  - 霍夫曼编码
  - 二分查找
  - 深度优先和广度优先算法
  - 快速排序算法
  - KMP字符匹配算法
  - 最大流算法
  - 堆排序算法
  - 红黑树算法
  - hash算法
  - 最短路径算法
  - [LRU算法](https://github.com/Genluo/Blog/issues/38)

## 现代前沿技术

- Hybrid APP
- Native
- 小程序实现原理
- babel实现原理
- 预渲染、SSR、服务器渲染原理
- webworker技术优化项目
- webComponent技术
- TypeScript学习

## Linux

待续

## Python

待续

https://juejin.imw/post/5cc1da82f265da036023b628
