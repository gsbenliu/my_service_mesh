
# [A highly-available key value store for shared configuration and service discovery.]
# * etcd是一个高可用的键值存储系统，主要用于共享配置和服务发现。etcd是由CoreOS开发并维护的，灵感来自于 ZooKeeper 和 Doozer，它使用Go语言编写，并通过Raft一致性算法处理日志复制以保证强一致性。Raft是一个新的一致性算法，适用于分布式系统的日志复制，Raft通过选举的方式来实现一致性。Google的容器集群管理系统Kubernetes、开源PaaS平台Cloud Foundry和CoreOS的Fleet都广泛使用了etcd。在分布式系统中，如何管理节点间的状态一直是一个难题，etcd像是专门为集群环境的服务发现和注册而设计，它提供了数据TTL失效、数据改变监视、多值、目录监听、分布式锁原子操作等功能，可以方便的跟踪并管理集群节点的状态。

# * etcd的特性如下：

## 简单: 支持curl方式的用户API（HTTP+JSON）
## 安全: 可选的SSL客户端证书认证
## 快速: 单实例每秒 1000 次写操作
## 可靠: 使用Raft保证一致性
