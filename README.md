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

1. [踩坑记：rocketmq-console 消费TPS为0，但消息积压数却在降低是个什么“鬼”](http://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484537&idx=1&sn=42922fc2b8713a75a2a0d2a97d570724&scene=19#wechat_redirect)
2. [RocketMQ msgId与offsetMsgId释疑(实战篇)](https://mp.weixin.qq.com/mp/homepage?__biz=MzIzNzgyMjYxOQ==&hid=7&sn=01e061bb781e13c0433218a798498a37)
3. [RocketMQ 一行代码造成大量消息丢失](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484718&idx=1&sn=de898f6efec78890e699eb02d8d1ee74&scene=19#wechat_redirect)
4. [我的另一种参与 RocketMQ 开源社区的方式](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484822&idx=1&sn=ecaada01b1bcf73b3a9fb750872b8e9d&scene=19#wechat_redirect)
5. [RocketMQ消息发送常见错误与解决方案](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485278&idx=1&sn=f05b5a8544db0e6d5605ba2638c59c05&scene=19#wechat_redirect)
6. [RocketMQ学习环境搭建(RocketMQ安装与IDEA Debug环境搭建)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485300&idx=1&sn=065c3106340c91117bce1ec8dce9e6eb&scene=19#wechat_redirect)












