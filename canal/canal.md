Canal，在互联网数据异构设计方案中起着举足轻重的作用，通常用于实现将MySQL数据库中的数据增量同步到其他数据源，例如es,oracle,hbase等，本专栏尝试以源码为手段，深入分析Canal。


1. [数据异构重器之 Canal 初探](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484854&idx=1&sn=b027e3a993c1322b6233d11fa1741901&scene=19#wechat_redirect)
2. [一文详解 Canal Instance 设计理念与定制开发思路](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484870&idx=1&sn=d538d1c21dd586d09bcd958a7f535f9e&scene=19#wechat_redirect)
3. [探究 Canal EventParser 的设计与实现奥妙](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484914&idx=1&sn=93f9b34de726fac5c323875d43863f98&scene=19#wechat_redirect)
4. [Canal 如何保证数据库库事务的一致性](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484943&idx=1&sn=cccacadd3a212a303c280843741045f6&scene=19#wechat_redirect)
5. [Canal 初次启动时如何定位同步位点(文末附流程图)](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484976&idx=1&sn=13a55aab9db8628d314dabd338f7491d&scene=19#wechat_redirect)
6. [Canal binlog 日志管理器与GTID简介](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247484990&idx=1&sn=34456da66ec97f7e79ea2c257be43b43&scene=19#wechat_redirect)
7. [Canal binlog 日志 Dump 流程分析](https://mp.weixin.qq.com/s?__biz=MzIzNzgyMjYxOQ==&mid=2247485035&idx=1&sn=2f878fbf473601b68cedb5f096a5f93f&scene=19#wechat_redirect)
