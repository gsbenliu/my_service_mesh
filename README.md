# MY_SERVICE_MESH
  Service Mesh的核心是提供统一的、全局的方法来控制和测量应用程序或服务之间的所有请求流量(用数据中心的话说，就是“east-west”流量)。对于采用了微服务的公司来说，这种请求流量在运行时行为中扮演着关键角色。因为服务通过响应传入请求和发出传出请求来工作，所以请求流成为应用程序在运行时行为的关键决定因素。因此，标准化流量管理成为标准化应用程序运行时的工具。
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
