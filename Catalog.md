- APM(Application Performance Monitor) for server

1. APM的前世今生
   1. 什么是APM
   1. APM的类型
   1. APM for server的市场现状
1. CNCF OpenTracing
   1. OpenTracing的由来和发展
   1. OpenTracing的运用
   1. OpenTracing的语义
      1. Trace
      1. Span
      1. Span#Tag
      1. Span#Log
      1. Context#Inject和Context#Extract
   1. OpenTracing的生态
1. VM Container与探针
   1. 探针通用原理
      1. 上下文传递
      1. AOP
      1. 如何保证探针的高性能
   1. Skywalking Java探针揭秘
      1. 字节码技术
      1. 和ClassLoader共舞
      1. 异步与同步
      1. 话外：如果不想接触底层，我们有什么选择？
         1. OpenTracing Bridge
         1. Spring AOP埋点
   1. PHPTrace/Molten PHP探针揭秘
      1. （邀请其他作者完成）
1. 如何APM进行监控和性能诊断
   1. 微服务下的应用依赖关系
   1. 微服务下的服务依赖以及灰度发布
   1. 服务KPI考核，慢Trace
   1. Top N Traces，从明细分析低频事件原因
   1. SQL N + 1
   1. Cache高频访问
   1. GC、内存与TPS波动
   1. Trace Profile
      1. 什么是Trace Profile
      1. Trace Profile的基本理论
         1. 理论基础
         1. 优点
         1. 缺点与误差
      1. 利用Trace Profile诊断本地方法效率
1. Service Mesh与APM
   1. 什么是Service Mesh
   1. Linkerd简介
   1. 使用APM监控Service Mesh集群
