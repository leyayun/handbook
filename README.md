# handbook

用于知识点整理、记录，方便以后查找回顾

# 前端

## 浏览器
- [浏览器渲染原理与性能优化](https://juejin.cn/post/6944369057709686821)
- http 请求头
  - 301 永久重定向；此时搜索引擎不会收录当前请求地址，会收录重定向后的地址。
  - 302 临时重定向；
  - 304 请求的内容未发生改变（cotent not modify ）使用浏览器缓存；
  - 400 客户端错误(bad request) ；一般是请求参数错误。
  - 401 未认证（Unauthorized）；未登录状态返回。
  - 403 无权限（Forbidden）；无权限请求访问的资源。
  - 500 服务内部异常；
  - 502 网关超时；
- http 协商缓存与强缓存
- 跨域问题
  - 配置 nginx 转发
  - jsonp


## JavaScript 

- 闭包的理解
- 作用域
- 原型链
- 集成的实现
- 宏任务与微任务
- promise 实现
- 节流与防抖
- class extends / super 关键字


## 网络协议
- 七层架构
- http 1.1 、http 2.0 与 http 3.0
  - 
- https 
- tcp 三次握手

## 工程
- 构建工具 
  - webpack 
    - [深入解析 loader](https://juejin.cn/post/6944349196539396133)
    - webpack 打包优化
    - webpack 5.0 引入了长缓存，解决开发时编译慢的问题
  - vite
  - babel
- 前端监控
  - Sentry 可用于浏览器和 Nodejs 的运行时报错监控告警
- 代码质量扫描
  - SonarQube 可以扫描出代码中不好写法，帮助开发人员写出干净、安全的代码。最佳实践：接入 ci/cd 的 pipeline 或者接入 gitlab workflow




