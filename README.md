## 移动Web开发最佳实践

在移动端做Web开发跟PC端不太相同，可能会关注

- 2G、3G网络网络加载慢
- 需要考虑用户数据流量

等PC端不会去关注的点。比如2G、3G网络下加载资源速度都是我们一直所重视的。通过对资源的各种组合方式的合并来解决这个问题。当然流量也需要着重考虑，所以除了压缩、gzip等预处理外，缓存使用率的提高也成为研究的重点。

本方案将从`资源请求控制`、`缓存使用率`两个方面来提供一种最佳的实践方法。

内容包括

- 提高缓存利用率提供`基于localStorage的静态资源差异化更新方案`
- 实现`WebApp`，提供[Quickling解决方案](https://github.com/xiangshouding/bigpipe.smarty)
- 提供灵活的合并资源的方法（FIS资源合并），轻松配置进行合包；


---
请关注我们 http://fis.baidu.com