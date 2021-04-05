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









