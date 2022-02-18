

# SpringCloud

https://www.springcloud.cc/spring-cloud-greenwich.html

xxl-job:     https://baijiahao.baidu.com/s?id=1681035278234207562&wfr=spider&for=pc

​                  https://github.com/yehongzhi/learningSummary



### 微服务的4个核心问题

```
1。服务很多，客户端改如何访问？
2。这么多的服务， 服务之间如何通信？
3。 这么多服务，如何治理？
4。服务挂了，怎么办？
```

### 1.常见面试题：

```
什么是微服务
微服务之间是如何独立通信的
springcloud和dubbo有哪些区别
springboot和springcloud，请你谈谈对他们的理解
什么是服务熔断？什么是服务降级
微服务的优缺点分别是什么，说下你在项目开发中遇到的坑
你所知道的微服务技术栈有哪些，请列举一二
eureka和zookeeper都可以提供服务注册和发现的功能，请说说两个的区别
```

![1644477705](.\image\1644477705.jpg)

## 2.主要技术

![image-20220210153403673](.\image\image-20220210153403673.png)

![image-20220210155021290](.\image\image-20220210155021290.png)

## 3.本次环境

![image-20220210155136440](.\image\image-20220210155136440.png)

![image-20220210155521441](.\image\image-20220210155521441.png)

## 4.技术重点

<img src=".\image\image-20220210164220179.png" alt="image-20220210164220179" style="zoom:150%;" />

## 5.服务注册中心

### 5.1 Eureka

![image-20220212141726307](.\image\image-20220212141726307.png)

####  5.1.1 Eureka 单机版

![image-20220212150244742](.\image\image-20220212150244742.png)

#### 5.1.2  集群Eureka 

##### 原理

![image-20220212151142285](.\image\image-20220212151142285.png)

##### 注册中心集群，ServiceProvider集群

![image-20220212155738164](.\image\image-20220212155738164.png)

### 5.2 zookeper

### 5.3 Consul

启动命令：    consul agent -dev

访问地址：   http://localhost:8500/