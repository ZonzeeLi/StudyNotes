## Go

### 类型

- [深度剖析Go的 nil](https://mp.weixin.qq.com/s?__biz=Mzg3NTU3OTgxOA==&mid=2247489619&idx=1&sn=12ca425680395d21489e7a68d68c84bd&chksm=cf3e0896f84981802dc38cc0c79f83b223f094247238a0b64656239533af45fc179eba01ac97&scene=21#wechat_redirect)
- [Go协程池(1): 线程vs协程](https://mp.weixin.qq.com/s/rgecHCCgBEpSC3lOQMn9Lg)

### Go 关键字

- [Go语言在select语句中实现优先级](https://www.cnblogs.com/xiao-xue-di/p/14439516.html)
- [Go语言中new和make你使用哪个来分配内存？](https://mp.weixin.qq.com/s?__biz=MzkyNzI1NzM5NQ==&mid=2247484796&idx=1&sn=c6a6f23cad936e8703412960b56e9b53&scene=19)
- [Go 面试题： new 和 make 是什么，差异在哪？](https://mp.weixin.qq.com/s?__biz=MzUxMDI4MDc1NA==&mid=2247487140&idx=1&sn=36d12263308fd24c32e9f5327e73ba21&chksm=f9041bf9ce7392ef036a1f777a32f982bf0cd6ad365a4086f470b719609d02611121af68e72a&scene=178&cur_album_id=1751854579329056768#rd)
- [Go语言new和make的使用区别和最佳实践](https://mp.weixin.qq.com/s?__biz=Mzg2MTcwNjc1Mg==&mid=2247483694&idx=1&sn=f3fea9db7d6f03fa73c9dee3b9cc6d46&chksm=ce124e41f965c7579fbd5f6aed919a78e27f91e0679fab317181a5af4235d432da85e77e6087&scene=178&cur_album_id=2135346850428747780#rd)

### 锁

- [面试官：哥们Go语言互斥锁了解到什么程度了？](https://mp.weixin.qq.com/s?__biz=MzkyNzI1NzM5NQ==&mid=2247486917&idx=1&sn=a46ec21c40bb4f225068e05ea5d16d94&scene=21#wechat_redirect)
- [面试官：哥们Go语言的读写锁了解多少？](https://mp.weixin.qq.com/s/8AvAXThTMax4Te8mpXihHQ)

### Go 数据结构

- [Go语言heap解析](https://www.cnblogs.com/zhangmingcheng/p/15502073.html)
- [關於用 Go 实现堆和堆操作，可能是最通俗易懂的讲解了](https://mp.weixin.qq.com/s/jkHoVL6Ex93WuTr4lUaAJg)

### Go 内存

- [面试官：简单聊聊 Go 逃逸分析？](https://mp.weixin.qq.com/s/JXLGLya8ryCMS3g6loTZHw)
- [一篇文章讲清楚golang内存泄漏](https://mp.weixin.qq.com/s?__biz=Mzg3NTg4NTE3Nw==&mid=2247483756&idx=1&sn=74f35279893de4972d386280c15c33e8&chksm=cf3be67af84c6f6c0096596fa27d437da0fb29d393845ea306d94e521746dd137ce2571f37ac&mpshare=1&scene=23&srcid=0210kQYZXU7DsVQI3DEpZjB4&sharer_sharetime=1675991217630&sharer_shareid=8e63b3540fd968d19d6f9b0d3401e83f#rd)
- [给大家丢脸了，用了三年golang，我还是没答对这道resp.Body.Close() 引发的内存泄漏题](https://studygolang.com/articles/31717?fr=sidebar)
- [Golang http请求忘记调用resp.Body.Close()而导致的协程泄漏问题](https://blog.csdn.net/qq_37102984/article/details/129326866)

### Go 编程

- [Go并发编程 — sync.Once 单实例模式的思考](https://mp.weixin.qq.com/s?__biz=Mzg3NTU3OTgxOA==&mid=2247488377&idx=1&sn=dfc6e5a18ca10cba978913ba5d2fced0&chksm=cf3e03bcf8498aaa6f3c96cabe7d6ed5b2b0651b8f5a2ae558f6d3c5e241fb62044c35f3e5d0&scene=21#wechat_redirect)
- [Golang 最细节篇之 — Reader 和 ReaderAt 的区别](https://mp.weixin.qq.com/s?__biz=Mzg3NTU3OTgxOA==&mid=2247486762&idx=1&sn=cfe9ec4eff708397e8982e2dcb1c669b&chksm=cf3e1deff84994f9d82abc00ea26b1192a301863ae2bff74ce51d0c6ddcca7ce456973891053&scene=21#wechat_redirect)
- [Go 并发编程 — 深入浅出 sync.Pool ，围观最全的使用姿势，理解最深刻的原理](https://mp.weixin.qq.com/s?__biz=Mzg3NTU3OTgxOA==&mid=2247487011&idx=1&sn=a39e1cb829c5e5f504e096794e6c91da&chksm=cf3e1ee6f84997f0a8cae728d88e3f531ac1cd122a3a303c98fea4838f8e699f8fd9ab9f7446&scene=142#wechat_redirect)
- [Go 并发编程 — sync.Pool 源码级原理剖析 终结篇](https://mp.weixin.qq.com/s?__biz=Mzg3NTU3OTgxOA==&mid=2247487157&idx=1&sn=231af45701885f70e40fbf013f032192&chksm=cf3e1e70f8499766622ccf8c204e6a5ee667c70372a530e9d3d77ed4cd54be8b257d9efb65e2&scene=21#wechat_redirect)
- [Go十大常见错误第10篇：Goroutine和循环变量一起使用的坑](https://mp.weixin.qq.com/s/5296PqK3e7A6rWVWr2p4HQ)
- [Go Http包解析：为什么需要response.Body.Close()](https://segmentfault.com/a/1190000020086816)
- [万字长文深入浅出 Golang Runtime](https://zhuanlan.zhihu.com/p/95056679)


### Go web

- [Go HTTP服务用了优雅关闭，为什么还是报错？](https://mp.weixin.qq.com/s/X4LSkIOjsoyXPB2z8AxtFA)
- [gRPC+gRPC Gateway 能不能不用证书？](https://www.jianshu.com/p/543396adb72f)
- [Go语言实现建立websocket连接并定时发送心跳](https://www.cnblogs.com/tianyun5115/p/12613274.html?ivk_sa=1024320u)
- [Golang 中的反向代理(ReverseProxy) 介绍与使用](https://www.cnblogs.com/FengZeng666/p/15643335.html)
- [Go 简单而强大的反向代理（Reverse Proxy）](https://h1z3y3.me/posts/simple-and-powerful-reverse-proxy-in-golang/)
- [golang 反向代理 Gin框架反向代理详解](https://www.cnblogs.com/shuiche/p/16922587.html)
- [Go语言HTTP请求流式写入body](https://studygolang.com/articles/29059)

### Go 框架

- [Kratos 中文文档](https://go-kratos.dev/docs/intro/design/)
- [Go Gin框架请求自动验证和数据绑定，看完这篇就会用了](https://mp.weixin.qq.com/s/cAwc6ZhdUwxkI5VT8LY9Hg)
- [颠覆微服务架构？谷歌最新开源service weaver初体验](https://mp.weixin.qq.com/s/uIk0Zw6mfV6ZLd3ODDjJHQ)

### Go 工具

- [玩转 Go 日志框架 zap](https://mp.weixin.qq.com/s/jncsoU7uK7PqKB8Th3y5fg)
- [Go 十年了，终于想起要统一 log 库了！](https://mp.weixin.qq.com/s/ZOdasSP0paVCLF94Vf9A9A)
- [这个Go可视化工具，能帮你把项目代码结构和依赖画出来](https://mp.weixin.qq.com/s/rCpiQxqx1jF0a0AIUX1wNQ)
- [高性能 Go 日志库 zap 设计与实现](https://www.luozhiyun.com/archives/542)
- [发现一个Go开发的隔空传送工具，支持跨系统传送](https://mp.weixin.qq.com/s/iESNOzkPaZqPp6fnSMKRzg)
- [Go 每日一库之定时任务库：cron](https://mp.weixin.qq.com/s/swdijAro2k8LuYu7q_La1A)
- [Golang：命令行框架cobra简介](https://www.cnblogs.com/realcp1018/p/15763061.html)
- [怎么开源自己的Go库](https://mp.weixin.qq.com/s/vRWo1ZrsXlBXOrabjYtBSw)
- [Go每日一库之Pie ：一个高性能、类型安全的slice操作库](https://mp.weixin.qq.com/s?__biz=MzAxMTA4Njc0OQ==&mid=2651454203&idx=1&sn=6897f7ef36756827c500d8cd41ded580&scene=21#wechat_redirect)
- [Golang最强大的访问控制框架casbin全解析](https://blog.csdn.net/qq_42015552/article/details/104013264?spm=1001.2101.3001.6650.1&utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-104013264-blog-128071277.235%5Ev28%5Epc_relevant_t0_download&depth_1-utm_source=distribute.pc_relevant.none-task-blog-2%7Edefault%7ECTRLIST%7ERate-1-104013264-blog-128071277.235%5Ev28%5Epc_relevant_t0_download)
- [golang中使用casbin做权限验证](https://blog.csdn.net/xujiamin0022016/article/details/128071277)
- [搞定Go单元测试（四）—— 依赖注入框架(wire)](https://juejin.cn/post/6844903853536575501)
- [Golang依赖注入框架wire全攻略](https://juejin.cn/post/6844903901469097998)
- 

### 设计模式

- [Go开源库、大项目的公共包，是这么用建造者模式的](https://mp.weixin.qq.com/s/ZQUiKmSQ-WSDRAfO-6cNag)
- [一些实用的编程模式 | Options模式](https://mp.weixin.qq.com/s?__biz=MzUzNTY5MzU2MA==&mid=2247489777&idx=1&sn=a9c17cc31cb77f9139a45c484057f7ac&chksm=fa80c966cdf74070c095a8578ae7b17ffc51fc381535b175f562cc4af13db8e76ba600fd6f16&token=1449569934&lang=zh_CN&scene=21#wechat_redirect)
- [Golang中常见的option设计探讨](https://mp.weixin.qq.com/s/mzI8-KoRBhH-fGdfcyqI-w)
- [工厂模式有三个Level，你能用Go写到第几层？](https://mp.weixin.qq.com/s/MlC6-TDf06LGpF8hxcSV_w)
- [两种 Option 编程模式的实现，Uber推荐这一种](https://mp.weixin.qq.com/s/LW8Woq5Rg4x31DbtD-_jeA)

### 面试相关

- [知乎高赞 | Go 技术一面一般考哪些内容](https://mp.weixin.qq.com/s/xKmGVWe7zz7OD3hULH-otw)

### 其他

- [Go语言如何操作文件](https://mp.weixin.qq.com/s/bb_8rb8r1VV8Df8v8zYhcg)
- [字节大规模微服务 Go 语言发展之路](https://mp.weixin.qq.com/s/Oz0Zn8Y43UfHIOPL6rZ5Ig)
- [以太坊协议](https://github.com/ethereum/go-ethereum)