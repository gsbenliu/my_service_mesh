# MY_SERVICE_MESH
  Service Mesh的核心是提供统一的、全局的方法来控制和测量应用程序或服务之间的所有请求流量(用数据中心的话说，就是“east-west”流量)。对于采用了微服务的公司来说，这种请求流量在运行时行为中扮演着关键角色。因为服务通过响应传入请求和发出传出请求来工作，所以请求流成为应用程序在运行时行为的关键决定因素。因此，标准化流量管理成为标准化应用程序运行时的工具。
  Service mesh 又译作 “服务网格”，作为服务间通信的基础设施层。Buoyant 公司的 CEO Willian Morgan 在他的这篇文章 WHAT’S A SERVICE MESH? AND WHY DO I NEED ONE? 中解释了什么是 Service Mesh，为什么云原生应用需要 Service Mesh。

下面是 Willian Morgan 对 Service Mesh 的解释。

A service mesh is a dedicated infrastructure layer for handling service-to-service communication. It’s responsible for the reliable delivery of requests through the complex topology of services that comprise a modern, cloud native application. In practice, the service mesh is typically implemented as an array of lightweight network proxies that are deployed alongside application code, without the application needing to be aware.
### Service mesh的特点
Service mesh 有如下几个特点：

* 应用程序间通讯的中间层
* 轻量级网络代理
* 应用程序无感知
* 解耦应用程序的重试/超时、监控、追踪和服务发现
* 目前两款流行的 service mesh 开源软件 Istio 和 Linkerd 都可以直接在 kubernetes 中集成，其中 Linkerd 已经成为 CNCF 成员。
## 服务发现
  ### * [ZOOKEEPER]
  ### * [QURATOR]
  ### * [EUREKA]
  ### * [REDIS]
  ### * [CONSUL]
## 负载均衡
  ### * [DUBBO]
  ### * [KONG]
  ### * [RIBBON]
## 服务网关
  ### * [NGINX]
  ### * [KONG]
  ### * [ZUUL]
  ### * [OPENRESTRY]
  ### * [SPRING CLOUD GATEWAY]
## 分布式配置
  ### * [ZOOKEEPER]
  ### * [GIT]
  ### * [ETCD]
  ### * [CONSUL]
  ### * [JAVA JDBC]
## 服务熔断
  ### * [DUBBO]
  ### * [KONG]
  ### * [HYSTRIX]
## 跟踪
  ### * [ZIPKIN]]
  ### * [OPENTRACING]
  ### * [JAEGER]
## 监控
  ### * [OPENTSDB]
  ### * [HBASE]
  ### * [PROMETHEUS]
  ### * [GRAFANA]
  ### * [ELASTIC]
  ### * [PINPOINT]   
         https://www.cnblogs.com/yyhh/p/6106472.html
         https://blog.csdn.net/heyeqingquan/article/details/74456591
         https://skyao.io/learning-pinpoint/design/technical_overview.html
         Pinpoint的特点如下:

          分布式事务跟踪，跟踪跨分布式应用的消息
          自动检测应用拓扑，帮助你搞清楚应用的架构
          水平扩展以便支持大规模服务器集群
          提供代码级别的可见性以便轻松定位失败点和瓶颈
          使用字节码增强技术，添加新功能而无需修改代码
