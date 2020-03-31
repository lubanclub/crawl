# crawl
A simple, easy-to-use crawler

## QuickStart
只需三步，你就可以部署一个爬取 gocn 网站的所有新闻的爬虫

- 第一步，你需要去 github 上生成一个自己的 token
  Settings ——> Developer settings ——> Personal access tokens ——> Generate new token

- 第二步，配置自己的环境变量 export GITHUB_TOKEN=(第一步生成的 token)，或者将代码中全局 Token 修改为自己 token
  ```
  var Token = GetValueFromEnv("GITHUB_TOKEN")
  ```
   
- 第三步，git clone 代码仓库，并且在后台进程中运行爬虫，每 6 个小时爬取当天新闻并进行 github 推送。
```
git clone https://github.com/lubanproj/crawl.git
cd crawl
go build -v 
./crawl &
```

## 展示效果

展示效果如下：

<h3><p>GoCN 每日新闻 (2020-03-29)</p></h3><ol>
<li>Go 编译器指南 <a href="https://www.caffeinatedwonders.com/2019/12/26/tour-of-go-compilers/" rel="nofollow" target="_blank">https://www.caffeinatedwonders.com/2019/12/26/tour-of-go-compilers/</a>
</li>
<li>从 gRPC 的重试策略说起 <a href="https://gocn.vip/topics/10135" rel="nofollow" target="_blank">https://gocn.vip/topics/10135</a>
</li>
<li>Go 实现 LeetCode 全集 <a href="https://github.com/austingebauer/go-leetcode" rel="nofollow" target="_blank">https://github.com/austingebauer/go-leetcode</a>
</li>
<li>分布式从 ACID、CAP、BASE 的理论推进 <a href="https://gocn.vip/topics/10121" rel="nofollow" target="_blank">https://gocn.vip/topics/10121</a>
</li>
<li>dubbogo 1.4 最新特性 <a href="https://gocn.vip/topics/10119" rel="nofollow" target="_blank">https://gocn.vip/topics/10119</a>
</li>
</ol><hr><h3><p>GoCN 每日新闻 (2020-03-26)</p></h3><ol>
<li> 结构体转 map <a href="https://www.liwenzhou.com/posts/Go/struct2map/" rel="nofollow" target="_blank">https://www.liwenzhou.com/posts/Go/struct2map/</a>
</li>
<li> Go 每日一库之 sjson &nbsp;<a href="https://segmentfault.com/a/1190000022148617" rel="nofollow" target="_blank">https://segmentfault.com/a/1190000022148617</a>
</li>
<li> 用面向对象设计原则理解 Go 中 interface  <a href="https://mp.weixin.qq.com/s/MqQ6b-Z_wvYe9YpNI5LDeA" rel="nofollow" target="_blank">https://mp.weixin.qq.com/s/MqQ6b-Z_wvYe9YpNI5LDeA</a>
</li>
<li>Go 项目简单接入 travis ci  <a href="https://juejin.im/post/5e7592c0518825494a3fadd9" rel="nofollow" target="_blank">https://juejin.im/post/5e7592c0518825494a3fadd9</a>
</li>
<li> 微服务设计模式  <a href="https://mp.weixin.qq.com/s/mHHPaYEvon4zFHHDNP8A9A" rel="nofollow" target="_blank">https://mp.weixin.qq.com/s/mHHPaYEvon4zFHHDNP8A9A</a>
</li>
<li>[深圳] 腾讯 PCG 技术运营部招聘 Go 后台开发 <a href="https://gocn.vip/topics/10108" rel="nofollow" target="_blank">https://gocn.vip/topics/10108</a>
</li>
</ol><hr><h3><p>GoCN 每日新闻 (2020-03-23)</p></h3><ol>
<li>使用 Go 基准测试解决旅行商问题的精确算法 <a href="https://medium.com/@damien.leroux.pro/benchmark-an-exact-algorithm-solving-the-traveling-salesman-problem-with-go-e502b0ca3d0e" rel="nofollow" target="_blank">https://medium.com/@damien.leroux.pro/benchmark-an-exact-algorithm-solving-the-traveling-salesman-problem-with-go-e502b0ca3d0e</a>
</li>
<li>关于收集，标准化和集中化处理 Golang 日志的一些建议 <a href="https://segmentfault.com/a/1190000022106356" rel="nofollow" target="_blank">https://segmentfault.com/a/1190000022106356</a>
</li>
<li>Golang 三种方式实现超时退出 <a href="https://juejin.im/post/5e774a73e51d4526c70fd0a4" rel="nofollow" target="_blank">https://juejin.im/post/5e774a73e51d4526c70fd0a4</a>
</li>
<li>Go 进程的 HeapReleased 上升，但是 RSS 不下降造成内存泄漏？ <a href="https://pengrl.com/p/20033" rel="nofollow" target="_blank">https://pengrl.com/p/20033</a>
</li>
<li>分享一个 微信 Golang SDK <a href="https://gocn.vip/topics/10094" rel="nofollow" target="_blank">https://gocn.vip/topics/10094</a>
</li>
</ol><hr>

详情可见：[go_read](https://github.com/lubanproj/go_read)
