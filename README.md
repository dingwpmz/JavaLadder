# JavaLadder
java进阶之梯，关注Java主流中间件，覆盖RocketMQ、Dubbo、Sentienl、Kafka、Canal、ElasticSearch、ElasticJob等12个专栏近300篇文章。

由于公众号对历史消息的支持不够友好，应粉丝朋友们的要求，决定将公众号中已发表的乘体系的java中间件文章迁移到GitHub，方便大家阅读。

公众号『中间件兴趣圈』主打成体系剖析Java主流中间件，从源码分析、架构设计、线上故障案例剖析、实战等４个维度开展。

> 建议各位粉丝朋友们，关注一下我的公众号，以便及时获取最新的更新内容，与笔者近距离沟通交流。

![在这里插入图片描述](https://img-blog.csdnimg.cn/20210328160616845.jpg?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3ByZXN0aWdlZGluZw==,size_16,color_FFFFFF,t_70#pic_center)

『中间件兴趣圈』公众号分享的主要内容包含**开源项目、电子书、专栏**

## １、开源项目
主要是提炼或开源一些入门代码，方便大家更加深刻的理解中间件，理论与实践结合，目前已包括 rocketmq-learing与 netty-learning。

1、RocketMQ入门实例
结合场景介绍RocketMQ使用。
![在这里插入图片描述](https://img-blog.csdnimg.cn/2021032816145764.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3ByZXN0aWdlZGluZw==,size_16,color_FFFFFF,t_70#pic_center)

代码链接：[rocketmq-learning](https://github.com/dingwpmz/rocketmq-learning)

2、Netty入门实例
提取RocketMQ RPC模块代码进行封装，提供一个可直接使用的netty框架，结合Netty专栏，理论与实践相结合。

![在这里插入图片描述](https://img-blog.csdnimg.cn/2021032816134360.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3ByZXN0aWdlZGluZw==,size_16,color_FFFFFF,t_70#pic_center)

代码链接：[netty-learning](https://github.com/dingwpmz/netty-learning)


## 2、电子书

为了更加方便读者朋友对专栏内容的阅读，会将公众号中的专栏转化为电子书，目前已将RocketMQ专栏转化为两本电子书：
![Apache RocketMQ ACL、消息轨迹、主从切换](https://img-blog.csdnimg.cn/2021030422241188.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3ByZXN0aWdlZGluZw==,size_16,color_FFFFFF,t_70#pic_center)


![Apache线上故障排查与实战](https://img-blog.csdnimg.cn/20210304222419291.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3ByZXN0aWdlZGluZw==,size_16,color_FFFFFF,t_70#pic_center)

获取方式：关注『中间件兴趣圈』，回复GRF，**即可免费获取**。

![](https://img-blog.csdnimg.cn/20210304222446606.jpg#pic_center)


## 3、专栏

#### 3.1 Netty专栏
《让天下没有难学的Netty》专栏将从通道篇、内存篇、性能篇、实战篇详细剖析Netty的实现原理、设计理念，同时通过抽取Apache顶级项目RocketMQ的网络通信模块，构建一个可直接使用的Netty网络通信框架。

##### 3.1.1 网络通道篇

1. [Netty4 Channel 概述](https://mp.weixin.qq.com/s/mIq-NjA9vir4wHCe5qpqBQ)
2. [Netty4 ChannelHandler 概述](https://mp.weixin.qq.com/s/n4duWYQIWyau7YLBqvYTHw)
3. [Netty4 事件处理传播机制](https://mp.weixin.qq.com/s/5dlUN0bzW3aKfcg1PSR5Ow)
4. [图文并茂剖析Netty编解码以及背后的设计理念](https://mp.weixin.qq.com/s/8uQlY-SthNTeg1xVPN5jzA)
5. [一文揭晓通信协议设计的奥妙，直接"秒杀"面试官](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485622&idx=1&sn=5697d1193cd3d9323013866325a85333&chksm=e8c3ff42dfb4765488912d83b715bf701efccef6014a4edace05dc51f194a77f7ec5159ccef8&token=1812684394&lang=zh_CN#rd)
6. [面试官：Netty的线程模型可不是Reactor这么简单](https://mp.weixin.qq.com/s/kcSI0yQH3HxZt5KFU-M8_w)
7. [Netty进阶：手把手教你如何编写一个NIO客户端](https://mp.weixin.qq.com/s/vrf8bO_K1YIac96A-HEV8A)
8. [Netty进阶：手把手教你如何编写一个NIO服务端](https://mp.weixin.qq.com/s/QZIXOT1fSmpu4di16vfyuQ)
9. [阿里面试真题:NIO为什么不适合文件上传场景、如何优雅解决](https://mp.weixin.qq.com/s/VMiB-4a15TgsIA2W-c4HHg)


##### 3.2 RocketMQ专栏



1. [我的另一种参与 RocketMQ 开源社区的方式](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484822&idx=1&sn=ecaada01b1bcf73b3a9fb750872b8e9d&scene=19#wechat_redirect)
2. [踩坑记：rocketmq-console 消费TPS为0，但消息积压数却在降低是个什么“鬼”](http://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484537&idx=1&sn=42922fc2b8713a75a2a0d2a97d570724&scene=19#wechat_redirect)
3. [RocketMQ msgId与offsetMsgId释疑(实战篇)](https://mp.weixin.qq.com/mp/homepage?__biz=MzIzNzgyMjYxOQ==&hid=7&sn=01e061bb781e13c0433218a798498a37)
4. [RocketMQ 一行代码造成大量消息丢失](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484718&idx=1&sn=de898f6efec78890e699eb02d8d1ee74&scene=19#wechat_redirect)
5. [RocketMQ消息发送常见错误与解决方案](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485278&idx=1&sn=f05b5a8544db0e6d5605ba2638c59c05&scene=19#wechat_redirect)
6. [从年末生产故障解锁RocketMQ集群部署的最佳实践](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485300&idx=1&sn=065c3106340c91117bce1ec8dce9e6eb&scene=19#wechat_redirect)
7. [RocketMQ实战：生产环境中，autoCreateTopicEnable为什么不能设置为true](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484340&idx=1&sn=45c0af3927266d321d5dbcd638f6c3cb&scene=19#wechat_redirect)
8. [RocketMQ 消息发送system busy、broker busy原因分析与解决方案](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484345&idx=1&sn=ed0076fed82ab10c1927fee7cccdeb52&scene=19#wechat_redirect)
9. [再谈 RocketMQ broker busy(实战篇)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484473&idx=1&sn=0ad69109dbd819fe834ad66b49730674&scene=19#wechat_redirect)
10. [RocketMQ实战：一个新的消费组初次启动时从何处开始消费呢？](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484375&idx=1&sn=8f9e39267c58ba7cad646f9976047e03&scene=19#wechat_redirect)
11. [RocketMQ生产环境主题扩分片后遇到的坑](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484417&idx=1&sn=7bc1beac079898fbc11391c0f54388c6&scene=19#wechat_redirect)
12. [一次 RocketMQ 进程自动退出排查经验分享（实战篇）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484481&idx=1&sn=4cc9d939eae36a2f612c5f2cbddbec2e&scene=19#wechat_redirect)
13. [从年末生产故障解锁RocketMQ集群部署的最佳实践](https://mp.weixin.qq.com/s/-5gzmrsYJuUTxIXP5-yPtw)
14. [RocketMQ 平滑升级到主从切换(实战篇)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484463&idx=1&sn=181b288aae09653e4806c2331d8f23b6&scene=19#wechat_redirect)
15. [RocketMQ学习环境搭建(RocketMQ安装与IDEA Debug环境搭建)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485300&idx=1&sn=065c3106340c91117bce1ec8dce9e6eb&scene=19#wechat_redirect)
16. [RocketMQ核心概念扫盲篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485310&idx=1&sn=c3c4d36a33fa489de93d2b2bde522c61&scene=19#wechat_redirect)
17. [RocketMQ HA机制(主从同步)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484350&idx=1&sn=f4055b462f3ae4fdf99e90e7d377fd90&scene=19#wechat_redirect)
18. [RocketMQ ACL使用指南](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484355&idx=1&sn=f1224fc830c9e4992441dfc77ac1ec3c&scene=19#wechat_redirect)
19. [RocketMQ消息轨迹-设计篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484369&idx=1&sn=72c9a807fe991d7fa720a3e2804d46d2&scene=19#wechat_redirect)
20. [蚂蚁二面:MQ消费端遇到瓶颈除了横向扩容外还有其他解决办法?）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484481&idx=1&sn=4cc9d939eae36a2f612c5f2cbddbec2e&scene=19#wechat_redirect)
21. [事务消息应用场景、实现原理与项目实战(附全部源码)](https://mp.weixin.qq.com/s/9sIjic10mTzdTLaAnd4ckA)
22. [源码分析RocketMQ ACL实现机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484360&idx=1&sn=701931ee71f022362db599f6595df37f&scene=19#wechat_redirect)
23. [源码分析RocketMQ消息轨迹](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484388&idx=1&sn=855150d480b7f56cde455c7c718507ab&scene=19#wechat_redirect)
24. [RocketMQ 多副本前置篇：初探raft协议](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484393&idx=1&sn=117208f86616ce7793d84fbe80c5ec5b&scene=19#wechat_redirect)
25. [源码分析RocketMQ多副本之Leader选主](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484399&idx=1&sn=7fc8c42c8f3062ba83618c9d6577e95a&scene=19#wechat_redirect)
26. [源码分析 RocketMQ DLedger 多副本存储实现](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484410&idx=1&sn=26e976cf97d8ff18283f173766e485b9&scene=19#wechat_redirect)
27. [源码分析 RocketMQ DLedger(多副本) 之日志追加流程](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484431&idx=1&sn=da4def8ab097dbe0b392e58bb2542156&scene=19#wechat_redirect)
28. [源码分析 RocketMQ DLedger(多副本) 之日志复制-上篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484432&idx=1&sn=c2c89e0850c9cce7815a52cacdede643&scene=19#wechat_redirect)
29. [源码分析 RocketMQ DLedger(多副本) 之日志复制-下篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484434&idx=1&sn=3234b76a43ed590777798db9e67d0881&scene=19#wechat_redirect)
30. [基于 raft 协议的 RocketMQ DLedger 多副本日志复制设计原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484445&idx=1&sn=38f257fa05c27483feddc9fa55bbee14&scene=19#wechat_redirect)
31. [RocketMQ 整合 DLedger(多副本)即主从切换实现平滑升级的设计技巧](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484452&idx=1&sn=798d3d3eb410edc98141462f337599a6&scene=19#wechat_redirect)
32. [源码分析 RocketMQ DLedger 多副本即主从切换实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484458&idx=1&sn=b9519059c1b74668469f2765bd58224f&scene=19#wechat_redirect)


##### 3.3 Sentinel专栏

以源码分析为主要手段，结合图解的方式深入剖析Sentienl限流的实现原理，带着问题看源码，加以思考、质疑并加以验证，该专栏不仅介绍Sentinel核心理念，更是笔者源码阅读方法论的一次实战。

1. [Alibaba Sentinel 限流与熔断初探](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484550&idx=1&sn=5e057b2d4c15411d743f84637a2cf9e3&scene=19#wechat_redirect)
2. [源码分析 Sentinel 之 Dubbo 适配原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484558&idx=1&sn=03a7a27bbfe9c50806d3b9c02dd4db77&scene=19#wechat_redirect)
3. [Alibaba Seninel 滑动窗口实现原理(文末附原理图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484565&idx=1&sn=dde2f448d0c626a8b2e47f59f6afc9fa&scene=19#wechat_redirect)
4. [寻找一把进入 Alibaba Sentinel 的钥匙(文末附流程图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484570&idx=1&sn=cd45fc4acd2c586453fb2c4512613ca9&scene=19#wechat_redirect)
5. [Sentinel 调用上下文环境实现原理(含原理图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484580&idx=1&sn=2ada79571d45cee8ec85ddd0924a5af7&scene=19#wechat_redirect)
6. [源码分析 Sentinel 实时数据采集实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484585&idx=1&sn=f40ddf6b2d13fa203ab95d98079468e1&scene=19#wechat_redirect)
7. [Sentinel FlowSlot 限流实现原理(文末附流程图与总结)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484595&idx=1&sn=19f7f77e31fb2fbab952f1d31c4e8ff9&scene=19#wechat_redirect)
8. [源码分析 RateLimiter SmoothBursty 实现原理(文末附流程图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484601&idx=1&sn=1e7bd53677615a8da919810750e428e5&scene=19#wechat_redirect)
9. [源码分析RateLimiter SmoothWarmingUp 实现原理(文末附流程图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484606&idx=1&sn=57884df6c7e45df3e648b468d2fc615a&scene=19#wechat_redirect)
10. [Sentienl 流控效果之匀速排队与预热实现原理与实战建议](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484625&idx=1&sn=2d1a3b9523afb4a3aa77036fe538a19b&scene=19#wechat_redirect)
11. [源码分析 Sentinel DegradeSlot 熔断实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484630&idx=1&sn=efeb57c897a10a5a4e11bafbe1e4840f&scene=19#wechat_redirect)
12. [Sentinel 动态数据源架构设计理念与改造实践](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484644&idx=1&sn=4b6e5f2a0d5551e54f76e104a58e7c24&scene=19#wechat_redirect)
13. [Sentinel 集群限流设计原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484656&idx=1&sn=4b184fc7c8137c5fe42de6a64811041e&scene=19#wechat_redirect)
14. [Sentinel Dubbo 适配器看限流与熔断(实战思考篇)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484689&idx=1&sn=6c959b0f4c99eb386081b760392e454d&scene=19#wechat_redirect)
15. [Sentinel 系统自适应限流原理剖析与实战指导](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484745&idx=1&sn=0e6fe482b0774a2120ac4da61a42ade5&scene=19#wechat_redirect)
16. [结合 Sentinel 专栏谈谈我的源码阅读方法](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484793&idx=1&sn=9c7a68579cd8a05f7f5f264eb6dc7726&scene=19#wechat_redirect)

##### 3.4 源码分析Dubbo专栏
本系列文章主要针对Dubbo2.6.2(dubbox2.8.4)版本，从源码的角度分析Dubbo内部的实现细节，加深对Dubbo的各配置参数底层实现原理的理解，更好的指导Dubbo实践。



1. [寻找注册中心、服务提供者、服务消费者功能入口](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483903&idx=1&sn=24b670b2d5aa6f2553916d0169637b2c&scene=19#wechat_redirect)
2. [源码分析Dubbo服务提供者启动流程-上篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483911&idx=1&sn=5fe373eb639d4e4648bc4ada41c2b871&scene=19#wechat_redirect)
3. [源码分析Dubbo服务提供者启动流程-下篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483912&idx=1&sn=030f685179c53a84fac970080607b2b8&scene=19#wechat_redirect)
4. [源码分析Dubbo消费端启动流程](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483913&idx=1&sn=1269fe4d94c435bcb38b787e09503a7a&scene=19#wechat_redirect)
5. [服务发现、集群、负载均衡、路由体系](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483999&idx=1&sn=482e699d5cd9036bc0f945dcf261f210&scene=19#wechat_redirect)
6. [源码分析Dubbo服务注册与发现机制RegistryDirectory)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484015&idx=1&sn=7e173392339f4a995ba53fdced0043fd&scene=19#wechat_redirect)
7. [源码分析Dubbo override实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484060&idx=1&sn=a032f1175c6e95d46e1b3bd6333d0b15&scene=19#wechat_redirect)
8. [Dubbo路由机制概述](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484085&idx=1&sn=578babdd2da9419b45efbc68f38b3443&scene=19#wechat_redirect)
9. [源码分析Dubbo负载算法](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484086&idx=1&sn=1b7839ea17ec110a539aed437e576946&scene=19#wechat_redirect)
10. [源码分析Dubbo集群策略](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484087&idx=1&sn=cb3700aa7b2600933fdb1b14c2408ed7&scene=19#wechat_redirectt)
11. [Dubbo网络通讯篇概述](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484088&idx=1&sn=1c19285c4d0a672f68603de5bf4b6e3e&scene=19#wechat_redirect)
12. [源码分析Dubbo事件派发机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484089&idx=1&sn=929dbd778bd5037dc917c54efac56f90&scene=19#wechat_redirect)
13. [源码分析Dubbo线程池实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484090&idx=1&sn=b8af93f037fc9466d925a70a7b1513f6&scene=19#wechat_redirect)
14. [源码分析Dubbo NettyServer与HeaderExchangeServer](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484098&idx=1&sn=2fa90adac8d4d3b92ac4dcdf6ab14ca1&scene=19#wechat_redirect)
15. [源码分析Dubbo网络通信NettyClient实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484099&idx=1&sn=0381117995a4de9c68589d2a0f5bac99&scene=19#wechat_redirect)
16. [源码分析Dubbo编码解码实现原理(Dubbo协议)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484100&idx=1&sn=4334ff29a6888634cecccae90d30940d&scene=19#wechat_redirect)
17. [Dubbo序列化概述](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484107&idx=1&sn=837af396c959ca8f40be4c6354a4e29e&scene=19#wechat_redirect)
18. [源码分析kryo对java基础数据类型与Stirng类型的序列化反序列化机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484115&idx=1&sn=25d4c8f66c1aee5b3b53d67dfabc5a4b&scene=19#wechat_redirect)
19. [源码分析kryo对象序列化实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484127&idx=1&sn=36f4f08425ec0b452c3927c52a5b945e&scene=19#wechat_redirect)
20. [源码分析Dubbo服务调用-服务提供者如何处理请求命令与再谈Invoker](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484133&idx=1&sn=2ee74e1a8fd4c1538a0ea4b8283cd43f&scene=19#wechat_redirect)
21. [Dubbo Filter机制概述](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484135&idx=1&sn=4c1e5877455c548c53954d5b9e9a9105&scene=19#wechat_redirect)
22. [源码分析Dubbo监控中心实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484170&idx=1&sn=85d98d10f91fa46699d936ec2aa96c44&scene=19#wechat_redirect)
23. [源码分析Dubbo异步调用与事件回调机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484171&idx=1&sn=c79a57ef4e836dcbd80d790a61829b4c&scene=19#wechat_redirect)
24. [源码分析Dubbo服务调用日志(accesslog参数)实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484172&idx=1&sn=03dcadb29dbf79c54ab046834cda9be1&scene=19#wechat_redirect)
25. [源码分析Dubbo服务提供者、服务消费者并发度控制机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484179&idx=1&sn=c032f4ade9b72e3a81212d66491232a6&scene=19#wechat_redirect)
26. [源码分析Dubbo tps过滤器器实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484182&idx=1&sn=afd57adca4772f63a9725438481c3e4a&scene=19#wechat_redirect)
27. [源码分析Dubbo 泛化调用与泛化实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484183&idx=1&sn=7003199bc56d51fa1ce6d240441c7351&scene=19#wechat_redirect)
28. [Dubbo服务治理之灰度发布方案（版本发布控制影响范围）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484189&idx=1&sn=17c82d8ca5cd64cb66eb31e9a63ed190&scene=19#wechat_redirect)

##### 3.5 ElasticSearch专栏
本专栏是对官方文档的完善与补充，立足与实战。

1. [ElasticSearch Client详解](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483658&idx=1&sn=37ba910f3507c1266554bfbaa8f589d8&scene=19#wechat_redirect)

2. [Elasticsearch文档读写模型实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483683&idx=1&sn=2c6d7890b8c6cdea5211d96abc09533d&scene=19#wechat_redirect)

3. [Elasticsearch Document Index API详解、原理与示例](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483701&idx=1&sn=cce1891469945f69da143ae990b39a9f&scene=19#wechat_redirect)

4. [Elasticsearch Document Get API详解、原理与示例](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483709&idx=1&sn=1f3290a74fd0ca862d68bc4a5d04f32d&scene=19#wechat_redirect)

5. [Elasticsearch Document Delete API详解、原理与示例](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483715&idx=1&sn=abbee430b15337b28688a8c8a17b9712&scene=19#wechat_redirect)

6. [Elasticsearch Document Update API详解、原理与示例](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483723&idx=1&sn=aa59db2822b9a7079a3047b11baeed2f&scene=19#wechat_redirect)

7. [Elasticsearch Multi Get、 Bulk API详解、原理与示例](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483731&idx=1&sn=f8d176cbd0467b2a1eba2ceb0dde8b25&scene=19#wechat_redirect)

8. [Elasticsearch Query DSL概述与查询、过滤上下文](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483736&idx=1&sn=617704431d38e80285687f46c53d226d&scene=19#wechat_redirect)

9. [Elasticsearch Query DSL之全文检索(Full text queries)上篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483744&idx=1&sn=750e72b7298ef05c1596914b0b902e57&scene=19#wechat_redirect)

10. [Elasticsearch Query DSL之全文检索(Full text queries)下篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483750&idx=1&sn=5dfd09d23f58d76ad1a87df349f8fc35&scene=19#wechat_redirect)

11. [Elasticsearch Query DSL之Term level queries](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483755&idx=1&sn=81077fa477ee10e3439f016edbea2136&scene=19#wechat_redirect)

12. [Elasticsearch Query DSL之Compound queries（复合查询）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483760&idx=1&sn=c52646e4501fe0b0f7ecdf9c3fe55657&scene=19#wechat_redirect)

13. [Elasticsearch Mapping类型映射概述与元字段详解](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483765&idx=1&sn=6f152ccc9d266adfed554c5bab1146cc&scene=19#wechat_redirect)

14. [Elasticsearch Mapping parameters（主要参数一览）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483770&idx=1&sn=7f63952b50f16b1e8932fce6e2797cd6&scene=19#wechat_redirect)

15. [Elasticsearch Mapping之字段类型（field datatypes）](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483779&idx=1&sn=0b35ce957f1645992e001beb5d08cbcf&scene=19#wechat_redirect)

16. [Elasticsearch Dynamic Mapping(动态映射机制)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483780&idx=1&sn=acb4e06499091cb2056790db474eca00&scene=19#wechat_redirect)

17. [Elasticsearch Search API 概述与URI Search](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483799&idx=1&sn=101d7b8ca717d4313cb2452e198ef06b&scene=19#wechat_redirect)

18. [Elasticsearch Search API之(Request Body Search 查询主体)-上篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483843&idx=1&sn=bbcd74689699fc079615fa487cef8041&scene=19#wechat_redirect)

19. [Elasticsearch Search API之搜索模板(search Template)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483864&idx=1&sn=46d6632de96860cc88a4fdf5f646f5df&scene=19#wechat_redirect)

20. [ES度量聚合(ElasticSearch Metric Aggregations)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484106&idx=1&sn=fc4c3d0b86c54b93693b24c5718d4f21&scene=19#wechat_redirect)

21. [elasticsearch使用指南之桶聚合(Bucket)上篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484112&idx=1&sn=cc2e0eed006a9d887bd04bd9c926da18&scene=19#wechat_redirect)

22. [Es Bucket聚合(桶聚合) Terms Aggregation与Significant Terms Aggregation](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484126&idx=1&sn=884bff95dac71fd2f81f2f301c9e5fca&scene=19#wechat_redirect)

23. [ES Pipeline Aggregation(管道聚合)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484132&idx=1&sn=e8179c8ceeffa133ec7cbb0a660c05bf&scene=19#wechat_redirect)

24. [Elasticsearch Search API之(Request Body Search 查询主体)-下篇](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484134&idx=1&sn=7564e9494f2bcd7c62bfa6ba43fa2e9f&scene=19#wechat_redirect)

25. [Elasticsearch索引监控之Indices Segments API与Indices Shard Stores](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484232&idx=1&sn=1f73b17647c35e84ff997ca8485d8408&scene=19#wechat_redirect)

26. [Elasticsearch Index Monitoring(索引监控)之Index Stats API详解](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484227&idx=1&sn=8e815f35ba21dede1d9db981977ac9b2&scene=19#wechat_redirect)

27. [Elasticsearch之索引管理API(Index management)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484220&idx=1&sn=31037dde0badb437043f3226ff31fd73&scene=19#wechat_redirect)

28. [Elasticsearch Index Templates(索引模板)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484213&idx=1&sn=c13d804ef2b267428ea13a2d5e032ea0&scene=19#wechat_redirect)

29. [Elasticsearch Index Aliases详解](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484208&idx=1&sn=9437fcdf22960d8ae19f3ff7cbdb3a71&scene=19#wechat_redirect)

30. [Elasticsearch Index Setting一览表](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484194&idx=1&sn=6363c521fff73b48a595da3c36ccffbc&scene=19#wechat_redirect)



##### 3.6 ElasticJob专栏
源码分析ElasticJob研究系列主要要两个学习目标：

- 了解分布式调度平台ElasticJob的实现原理
- 掌握curator开源框架操作ZK

1. [源码分析ElasticJob前置篇之自定义Spring命名空间](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483786&idx=1&sn=f9b8a4116f3ad7b04f22d924425a6faa&scene=19#wechat_redirect)

2. [源码分析ElasticJob启动流程(基于Spring)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483810&idx=1&sn=0097ee0ff743c10a7d50361c572ba009&scene=19#wechat_redirect)

3. [源码分析ElasticJob选主实现原理](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483811&idx=1&sn=f6334f3257d904f24f841af5ebb8479a&scene=19#wechat_redirect)

4. [源码分析ElasticJob分片机制](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483820&idx=1&sn=e2d451f583ef5d76eaea5f8e5b193493&scene=19#wechat_redirect)

5. [源码分析ElasticJob故障失效转移](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483826&idx=1&sn=9ffeef8a4d688bdd730bc7a641025cf7&scene=19#wechat_redirect)

6. [源码分析ElasticJob任务错过机制(misfire)与幂等性](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483849&idx=1&sn=604b539a00d5d41a708a920a5964d4e6&scene=19#wechat_redirect)

7. [源码分析ElasticJob事件监听器](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247483855&idx=1&sn=4211b70eacaff8af96241cfc9164c7d3&scene=19#wechat_redirect)




# 版权说明
本项目可以鼓励以学习目的进行分享传播，但未授权任何商业机构等任何商业行文。


