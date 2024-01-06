文档参考：https://spring.io/guides

# Building a RESTful的web简单服务 Web Service
* 描述了如何构建一个RESTful的web简单服务
*  @SpringBootApplication 注解代替了多个字注解，可以了解一下。

# Scheduling Tasks
* @Scheduled  可以使用 cron 表达式
* 《动态改变cron表达式的值》：https://blog.csdn.net/fdisk_all/article/details/25965725
* 《spring动态配置cron表达式，不需要停服》：https://www.jianshu.com/p/6f58415b5734
* 《Spring之@Scheduled原理》：https://www.jianshu.com/p/b2dbe92876f2
* 《springboot集成schedule（深度理解）》: https://www.cnblogs.com/skychenjiajun/p/9057379.html?utm_source=tuicool&utm_medium=referral

# Consuming a RESTful Web Service
* 使用 RestTemplate 通过 restful 接口获取数据

# Accessing Relational Data using JDBC with Spring
* 使用 JdbcTemplate 执行SQL

# Uploading Files
* 上传文件，展示文件列表，下载文件。部分动态渲染。单元测试。

# Authenticating a User with LDAP
* 使用 Spring Security 和 LDAP 数据服务，构造一个权限校验的Demo.
* 《Spring Security》: http://www.mossle.com/docs/springsecurity3/html/springsecurity.html
* 《LDAP》: https://baike.baidu.com/item/LDAP/2875565?fr=aladdin

# Messaging with Redis
* 一个简单地基于模板使用 Redis 的Demo

# Messaging with RabbitMQ
* RabbitMQ 服务demo及基于 RabbitTemplate 交互消息。

# Accessing Data with Neo4j
* 一个简单介绍如何与图数据库Neo4集成的Demon
* 《Spring Data Neo4J》：https://spring.io/projects/spring-data-neo4j
* 《Neo4J 图数据库》: https://www.w3cschool.cn/neo4j/neo4j_need_for_graph_databses.html
* 《Spring DATA Neo4J - 简介》：https://www.w3cschool.cn/neo4j/neo4j_spring_data_introduction.html

# Validating Form Input
* 介绍如何在web服务中使用注解进行参数校验
* 《spring boot项目使用（2）-- javax.validation》：https://www.jianshu.com/p/71f70766d165
* 《使用javax.validation.constraints包的注解实现校验》：https://blog.csdn.net/lovequanquqn/article/details/82725258

# Building a RESTful Web Service with Spring Boot Actuator
* 介绍了提供一个RESTful服务，同时包含健康检查
* 《Springboot监控之一：SpringBoot四大神器之Actuator》：https://www.cnblogs.com/duanxz/p/3503094.html

# Messaging with JMS
* 介绍了如何使用通过 `JmsTemplate` 和 `@JmsListener` 实现消息的发送和监听。
* 《深入浅出JMS(一)--JMS基本概念》：https://blog.csdn.net/jiuqiyuliang/article/details/46701559

# Creating a Batch Service
* 介绍了Spring中批批处理逻辑，输入接口 -> 处理接口 -> 输出接口， 再进行配置。
* 批处理过程中可以考虑一些通用的接口，如：读文件工具类。

# Securing a Web Application
* 介绍使用 Spring Security 保护部分页面安全的Demo。
* 可以与 “Authenticating a User with LDAP” 一起看。

# Building a Hypermedia-Driven RESTful Web Service
* 介绍一种超媒体驱动的RESTful服务Demo, 可理解为获取资源的同时同时带上资源的地址。
* 相关介绍可以参考《使用 Spring HATEOAS 开发 REST 服务》：https://www.ibm.com/developerworks/cn/java/j-lo-SpringHATEOAS/

# Accessing Data in Pivotal GemFire
* 介绍使用 Pivotal GemFire 的Demo
* GemFire可里解为一个增强版的Redis。《GemFire 入门篇1：GemFire 是什么？》：https://www.cnblogs.com/doubletree/p/4198970.html
* 《GemFire vs. Redis》：http://vschart.com/compare/gemfire/vs/redis-database

# Integrating Data
* 介绍了如何使用 Spring Integration 快速搭建一个拉取feed流，并进行处理和存储的Demon.
* 《Spring integration学习总结》：https://blog.csdn.net/takeiteasy2009/article/details/8556394

# Caching Data with Pivotal GemFire
* 介绍如何使用 `@Cacheable`、`@CachePut`这些注解，以及如何配置 Pivotal GemFire 的缓存。

# Managing Transactions
* 使用 `@Transactional` 注解实现很少侵入的事务实现。
* 底层实现《Using Transactions》：https://docs.oracle.com/javase/tutorial/jdbc/basics/transactions.html#commit_transactions
