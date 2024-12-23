
# 💻 Projects
- *2021.12 - 2022.05*, [**LeetCode**](https://github.com/fuyunwang/Algorithm-LC), sorted out the Hot 100 and top 1500 questions on LeetCode, summarized and sorted them according to data structure, DP, greedy and other related types, and shared the summary on [Bilibili](https://www.bilibili.com/video/BV1ta411a7UK/?spm_id_from=333.999.0.0) and [Juejin](https://juejin.cn/post/7093007060840742920), which is ongoing...
- *2020.10 - 2021.05*,  [**Chuoyue**](https://github.com/fuyunwang/video_surveillance2021): **Independently developed** an enterprise-grade general-purpose PAAS platform foundation, leveraging [**Cloud Native**](https://mp.weixin.qq.com/s/1eR4rF9e3gTMLK6f015Z1w) practices.  
  
  ### Key Features and Technical Implementations:  
  
  1. **Microservice Architecture**:  
     - Built on **SpringCloud Hoxton** and **Spring Cloud Alibaba**.  
     - Core tech stack:  
       - **Backend**: Spring Boot 2.3.6.RELEASE, Spring Cloud Hoxton.SR9, Spring Cloud Alibaba (Nacos, Sentinel), Spring Cloud Security, OAuth2, OpenFeign, Spring Cloud Bus, MyBatis-Plus.  
       - **Middleware**: RocketMQ, Kafka, XXL-Job for scheduling, Seata for distributed transactions, ShardingSphere for database sharding.  
       - **Storage**: FastDFS + OSS for distributed file storage.  
       - **Server**: Tomcat, Jetty, Nginx + OpenResty + Lua.  
       - **Databases**: MySQL, Redis, MongoDB, ElasticSearch.  
  
  2. **Frontend**:  
     - Developed with **TypeScript** and **Vben Admin** for a modern, responsive user interface.  
  
  3. **Integrated Monitoring Platform**:  
     - **Logging**: ELK stack (Elasticsearch, Logstash, Kibana).  
     - **Tracing**: Skywalking APM for distributed tracing.  
     - **Monitoring and Alerts**: Prometheus + Grafana.  
  
  4. **CI/CD Pipeline**:  
     - Implemented continuous integration and deployment with **Jenkins**, **Docker**, and **Kubernetes**.  
  

- *2020.05 - 2020.08*, **Shandong Zhaowu Network Technology Co., Ltd.**: **Software Engineer**  

    Participated in the development of a Smart Community Platform, focusing on maintaining behavior data of residents and vehicles across various scenarios to assist relevant departments in investigation and evidence collection.  
    
    Key responsibilities and technical implementations:  
    1. **Distributed Authorization Center**:  
       - Implemented using **Spring Cloud Zuul** and **Spring Security** based on the RBAC (Role-Based Access Control) model.  
       - Ensured secure and efficient distributed authorization across services.  
    
    2. **Code Optimization with Strategy Pattern**:  
       - Applied the **Strategy Pattern** to streamline code structure.  
       - Enabled dynamic processing workflows for handling various types of data efficiently.  

- *2020.01 - 2020.05*, **Distributed Task Scheduling Platform**: **Independently developed** a distributed task scheduling platform using Golang.  

    Key features and technical implementations:  
    
    1. **Master-Worker Architecture**:  
       - Master node handles task scheduling requests and provides a web-based frontend interface.  
       - Worker nodes perform multi-task scheduling and concurrent task execution.  
    
    2. **Service Registration and Task Storage**:  
       - Utilized **etcd** for service registration, discovery, and task storage.  
       - Leveraged **Go channels** for efficient task distribution.  
    
    3. **Concurrency Management**:  
       - Implemented distributed locking with **etcd** to prevent concurrent execution of the same task.  
    
    4. **Log Management**:  
       - Stored task execution logs in **MongoDB**.  
       - Provided a frontend interface for visualizing logs in real-time.  
    
    5. **Cluster Setup**:  
       - Deployed a master node cluster.  
       - Used **Nginx** for reverse proxy and load balancing to distribute requests efficiently.  

- *2019.06 - 2019.09*, [**RpcInfra**](https://github.com/fuyunwang/RpcInfra): **Independently developed** a high-performance RPC framework based on Netty.  

    Key features and technical implementations:  
    1. **Long-Connection RPC with Netty**:  
       - Implemented custom protocol packaging.  
       - Resolved sticky and half-packet issues using a length-based protocol field.  
    2. **Distributed Service Registration and Discovery**:  
       - Utilized Zookeeper for service registry and discovery.  
       - Implemented load balancing using a consistent hashing algorithm.  
    3. **Health Monitoring**:  
       - Established periodic heartbeat detection and idle connection management between client and server to ensure application health.  
    4. **Reactor Threading Model**:  
       - Designed the service provider using a Reactor threading model.  
       - Employed a custom thread pool for efficient business logic processing.  
    5. **Modular Design**:  
       - Adopted a modular architecture.  
       - Integrated Spring Boot's SPI mechanism for dynamic module loading.  
    

- *2017.07 - 2018.06*, **Campus Shuttle Reservation Platform \| Educational Application**
    A platform for booking campus shuttles at Shandong Normal University, primarily providing features such as checking shuttle schedules between the main campus and Changqing campus, shuttle reservations, payment, and refunds.

    Key technical highlights:
  
    1. Unified Authentication and Authorization: Implemented via Spring Security at the gateway level, alleviating request pressure caused by numerous business services.
    2. Efficient Caching: Adopted a hybrid caching strategy using local Guava cache combined with centralized Redis, caching shuttle schedule lists. Load testing with JMeter achieved a throughput of 5000 QPS.
    Used Redisson-based distributed locks to ensure cache consistency and avoid cache stampede. Requests failing to acquire locks are put to sleep and retried, ensuring system responsiveness and reduced memory consumption.
    Cached null values for non-existent schedules to prevent cache penetration. Idempotency: Achieved via Redis cache expiration strategy based on request parameters.
    3. Asynchronous Reservation: Leveraged RabbitMQ for asynchronous order placement, with the consumer side ensuring deduplication based on order numbers to prevent repeated message consumption.
    4. Distributed Rate Limiting:
    Used Sentinel for global rate limiting across distributed services.
    Applied Guava's RateLimiter for local rate limiting using the token bucket algorithm.
    Unique ID Generation: Snowflake algorithm ensured unique, conflict-free order IDs.
    5. Database Optimization:
    Achieved read-write separation through MySQL master-slave replication, improving data access efficiency.
  

- *2016.04 - 2017.02*， **Smart SDNU \| Educational Application**, A school research team project providing services such as weather updates, campus card services, library reservations, and Shanshi data insights. Served as the Android lead, responsible for the design and development of the Android app.



# 🧑‍ Student Cadre
- *2023.09 - *, Student at the School of Computer Science and Engineering, Nanjing University of Science and Technology
- *2020.09 - 2023.06*, Class President of the 2020 Software Engineering Class, School of Information Science and Engineering, Shandong Normal University


# 📖 Educations
- *2023.09 - *, Nanjing University of Science and Technology
- *2020.09 - 2023.06*, Shandong Normal University
- *2015.09 - 2019.06*, Shandong Normal University


