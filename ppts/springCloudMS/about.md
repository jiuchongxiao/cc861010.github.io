## 一：背景
去年发布了一系列spring boot为基础的项目
包括：

     wk-spring-boot-dubbo-start
     wk-spring-boot-mysql-start
     wk-spring-boot-redis-start
     wk-spring-boot-etcd-start
     
基本上spring boot这种快速方法的开发规范已经成了我们事实上的标准  

今年在spring boot的基础上发布了spring cloud系列的例子和最佳实践，配合运维自动化
提供了构建分布式应用开发的另一个选择

## 二：组成
spring cloud 主要由：
1. feign    服务接口定义
2. rabbin   客户端负载均衡
3. hystrix  错误熔断
4. zuul     微服务组网关
5. etcd     服务注册发现

## 三：作用
在保证性能，稳定性的前提下，用于各种传统服务和微服务的快速开发，快速迭代

## demo:
http://192.168.1.40/cc/wk-ms-cloud.git

## ppt:
http://cc861010.github.io/
