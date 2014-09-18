## 移动Web开发最佳实践

在移动端做Web开发跟PC端不太相同，可能会关注

- 2G、3G网络网络加载慢
- 需要考虑用户数据流量

等PC端不会去关注的点。比如2G、3G网络下加载资源速度都是我们一直所重视的。通过对资源的各种组合方式的合并来解决这个问题。当然流量也需要着重考虑，所以除了压缩、gzip等预处理外，缓存使用率的提高也成为研究的重点。


本方案将从资源请求控制、缓存使用量两个方面来提供一种可行方法。

---
请关注我们 http://fis.baidu.com