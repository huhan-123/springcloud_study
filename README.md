# springcloud-study

## 介绍

该项目是我学习springcloud做的一个demo，过程中踩了很多坑，因此我把它传到GitHub供自己和其他小伙伴一起学习。现在还只是一个小demo，以后有时间会慢慢完善功能。该项目暂时有如下模块：1.订单服务；2.商品服务；3.日志服务；4.注册中心；5.网关；6.监控中心（监控中心分为三个小模块：（1）admin监控服务的健康状况 （2）zipkin链路追踪 （3）turbine聚合hystrix实时监控）。如果要访问订单服务或者商品服务，需要统一走网关。订单服务调用商品服务，调用之前，会调用日志服务记录操作日志，监控中心会监控整个请求过程。

