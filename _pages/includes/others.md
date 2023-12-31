
# 💻 Projects
- *2021.12 - 2022.05*， [**LeetCode 梳理**](https://github.com/fuyunwang/Algorithm-LC)，对LeetCode上 Hot100题、前1500题进行系列梳理，按数据结构、DP、贪心等相关类型进行总结整理，并在[B站](https://www.bilibili.com/video/BV1ta411a7UK/?spm_id_from=333.999.0.0)、[掘金](https://juejin.cn/post/7093007060840742920)分享总结，持续进行中...
- *2020.10 - 2021.05*， [**Chuoyue**](https://github.com/fuyunwang/video_surveillance2021)，**独立完成**企业级通用PAAS平台基架，[**Cloud Native**](https://mp.weixin.qq.com/s/1eR4rF9e3gTMLK6f015Z1w)实践。基于SpringCloud Hoxton + Spring Cloud Alibaba构建微服务架构基础（技术栈包括：Spring Boot 2.3.6.RELEASE、Spring Cloud Hoxton.SR9、Spring Cloud Alibaba、Spring Cloud Security、Spring Cloud Oauth2、Spring Cloud OpenFeign、Spring Cloud Alibaba Nacos、Spring Cloud Alibaba Sentinel、Spring Boot Admin、Spring Cloud Bus、MyBatis-Plus、消息中间件（RocketMQ，Kafka）、定时任务（Xxl-Job）、分布式事务（Seata）、分库分表（ShardingSphere）、分布式文件存储（FastDFS + OSS）、服务器（Tomcat、Jetty、Nginx + OpenResty + Lua）、数据库（MySQL、Redis、MongoDB、ElasticSearch））,基于TypeScript + [Vben](https://doc.vvbin.cn/)构建前端界面；构建 日志处理（ELK） + 链路追踪（Skywalking APM） + 监控告警（Prometheus + Grafana） 一体化监控平台；基于Jenkins + Docker + Kubernetes实现持续集成和持续部署
- *2020.05 - 2020.08*， **山东兆物网络技术股份有限公司**，**研发工程师**，参与智慧社区平台的开发，维护社区内人员及车辆在不同场景的行为信息，以供相关部门调查取证。使用 Spring Cloud Zuul+Spring Security 实现基于 RBAC 权限模型的分布式授权中心；使用策略模式优化代码，实现对不同类型的数据进行相应的处理流程
- *2020.01 - 2020.05*， **分布式任务调度平台**，**独立完成**基于Golang实现的分布式任务调度平台。基于master-worker架构实现，master接收任务调度请求并提供前端界面，worker进行多任务调度和任务并发执行；基于etcd实现服务注册与发现、任务存储，基于go channel完成任务分发；基于etcd实现分布式锁避免任务并发执行；采用mongodb存储任务调度产生的日志并提供前端可视化日志界面；搭建master节点集群，基于Nginx实现反向代理和负载均衡
- *2019.06 - 2019.09*， [**RpcInfra**](https://github.com/fuyunwang/RpcInfra)，**独立完成**基于Netty实现高性能RPC框架。基于 Netty 实现长连接RPC，自定义协议封装并基于协议长度字段解决粘包拆包问题；基于 Zookeeper 实现分布式服务注册与发现，并基于一致性哈希算法实现负载均衡策略；客户端与服务端定期进行心跳检测和空闲连接管理以维持应用健康状态；服务提供者采用 Reactor 线程模式并自定义线程池完成业务逻辑处理；项目采用模块化设计并使用 SpringBoot 提供的 SPI 机制实现动态加载
- *2017.07 - 2018.06*， **校园班车预约平台\|教育应用**，针对山东师范大学校园班车进行预约，主要提供本部到长清校区班车场次查询，班车预约、支付、退款等功能。采用 Spring Security 实现网关统一认证与鉴权，缓解了认证授权服务因业务服务数量多带来请求压力问题；采用本地 Guava 缓存 + Redis 集中式缓存策略，缓存班车场次列表，使用 JMeter 进行压测，可以达到5000QPS；缓存更新需要获取基于 Redisson 设计的分布式锁，避免缓存击穿，此外，未获得锁的请求睡眠后重试，保证了系统响应速度，降低了内存
消耗；针对不存在的班车列次，缓存null值，避免缓存穿透；使用 Redis 缓存过期时间策略实现基于请求参数的接口幂等性校验；采用 RabbitMQ 进行异步预约下单，消息消费方以订单号作为去重的依据，避免消息的重复消费；基于 Sentinel 实现分布式限流，对于单个服务内部，采用 Guava 提供的 RateLimiter 进行令牌桶算法的本地限流；采用雪花算法实现分布式 ID 生成，避免订单号冲突；MySQL 数据库基于主从复制实现读写分离，提升数据存取效率
- *2016.04 - 2017.02*， **智慧山师\|教育应用**，学校科研团队项目（包括天气服务、一卡通服务、图书馆预约、数读山师等功能），担任Android端负责人，负责Android APP的设计与研发



# 🧑‍ Student Cadre
- *2023.09 - 今*, 南京理工大学计算机科学与工程学院 学生
- *2020.09 - 2023.06*, 山东师范大学信息科学与工程学院2020级软件工程班 班长


# 📖 Educations
- *2023.09 - 今*, 南京理工大学
- *2020.09 - 2023.06*, 山东师范大学
- *2015.09 - 2019.06*, 山东师范大学


