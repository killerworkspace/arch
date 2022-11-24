# 知识体系梳理

### 操作系统(服务器) 

1. Tomcat(Selvlet容量)，Jetty
2. Nginx/Tengine(Web应用服务器)
3. 磁盘、IO、网络、CPU

### 计算机基础 

计算机组成原理、编译原理 

### 网络 

1. 互联网协议
2. TCP/IP(TCP/IP协议簇)
3. HTTP1.1/2/0
4. HTTPS
5. OAuth 2.0
6. REST

### Java编程 

**IDE：** 

1. Eclipse 
2. Intellij IDEA

**版本控制：** 

1. Git
2. SVN

**Java基础：** 

1. 基础语法和面向对象
2. 标识符合保留字
3. 数据类型
4. 流程控制
5. OO:封装、继承、多态

**网络编程** 

1. 网络基础知识
2. inetaddress
3. tcp
4. udp
5. socket
6. netty
7. servlet、jsp

### 框架 

**集合框架** 

1. collection
2. list
3. map
4. collections
5. arrays

**IO框架**

字节流、字符流、缓存流、处理流、转换流 

**多线程编程** 

1. 线程、进程、程序
2. thread 和 runnable
3. 线程的生命周期
4. 线程的同步与加锁
5. 线程池
6. lambda表达式
7. stream API
8. 自定义注解

**http协议** 

1. Tomcat服务器
2. servlet实现原理
3. jstl和EL表达式
4. 监听器和过滤器
5. jsp相关知识

**Spring** 

1. Spring的IOC
2. spring的AOP
3. Spring的设计模式
4. Spring的事务处理
5. Spring的动态处理
6. Spring的基础源码

**SpringMVC** 

1. SpringMVC的实现原理
2. 视图处理器
3. 数据校验
4. 拦截器
5. 基础源码

**mybatis** 

1. 实现原理
2. 映射文件
3. 动态SQL
4. 缓存机制
5. 基础源码
6. mybatis-plus 的应用

**SpringBoot** 

1. 基本使用
2. 数据源的配置
3. 配置文件
4. web开发
5. 模板引擎的使用
6. 自动装配原理

### 基础语法 

**JDK8(java核心技术卷1)** 

集合框架 

List 

ArrayList 

LinkedList 

Set 

HashSet 

TreeSet 

Map 

HashMap 

TreeMap 

ConcurrentHashMap 

BitMap 

Queue 

ConcurrentLinkedQueue 

Stack 

Collections的synchronized方法 

**工具类** 

Google guava（推荐） 

Apache common lang /BeanUtils/Connections/IO 

JSON 

fastjson 

gson 

jackson 

JavaEE开发 

JSP/Servlet 3.x 

Session/Cookie 

jstl/EL 

**框架** 

Spring 

IOC 

AOP 

SpringMVC 

Mybatis 

Shiro 

Netty 

**高级特性** 

泛型 

多态的实现原理 

Lambda 

**并发****编程** 

Excutor框架 

happen-before 

线程池 

线程状态 

原子操作类 

并发工具类 

**网络编程** 

Socket 

基本案例实现 

#### IO 

BIO 

NIO 

AIO 

#### 序列化 

JDK自带 

Google protobuf(性能非常高) 

#### 远程调用 

RMI 

Thrift 

Dubbo(Dubbox) 

服务治理,也可以作为微服务 

gPRC 

#### 构建 

Maven(推荐Maven实战) 

Gradle 

### 安全 

**单项散列算法** 

MD5 

SHA 

**对称加密** 

DES 

**非对称加密** 

RSA 

HTTPS 

**Web安全**

跨站脚本

SQL注入

## JVM 

认识Java虚拟机(默认Hotspot实现) 

类加载机制(知道双亲委派机制) 

内存模型 

GC 

**调优** 

工具 

jconsole 

jstack 

jmap 

### 软件工程 

**运维** 

持续集成 

jenkins 

TDD 

**原则** 

DRY 

单一职责 

开闭原则 

## 设计原则和模式 

**基本设计原则** 

1. 单一职责的原则
2. 里氏替换原则
3. 依赖倒置原则
4. 接口隔离原则
5. 迪米特原则
6. 开闭原则

**设计模式** 

**基本设计模式** 

**创建型模式 4 **

1. 1. 工厂方法模式（Factory Method） 动态生成对象，子类决定实例化
2. 1. 抽象工厂模式（Abstract Factory） 生产成系列对象，抽象接口
3. 1. 构建器模式（Builder）    复杂对象构造，类和构造分离
4. 1. 原型模式（Prototype）克隆对象，原型事例，拷贝
5. 1. 单例模式（Singleton）单实例，唯一实例

**结构型模式 7**

1. 适配器模式（Adapter）转换、兼容接口
2. 桥接模式（Bridge） 继承树拆分，抽象和实现分离, 将类的抽象部分和实现部分分开
3. 组合模式（Composite）整体-部分，树形目录结构
4. 装饰模式(Decorator)   动态附加职责
5. 外观模式（Facade） 对外统一接口
6. 享元模式（Flyweight） 汉字编码，细粒度，共享
7. 代理模式（Proxy）  快捷方式，代理控制

**行为模式  12**

1. 责任链模式（Chain of Responsibility） 传递职责，请求，链接
2. 命令模式（Command） 日志记录，可撤销
3. 迭代器（Iterator） 数据集，顺序访问，不暴露内部
4. 中介者模式（Mediator）不直接引用
5. 备忘录模式（Memento） 游戏存档，保存，恢复
6. 观察者模式（Observer）订阅、广播、联动，通知，自动更新
7. 状态模式（State） 状态变成类
8. 策略模式（Strategy）多方案切换
9. 模板方法模式（Template Method）框架
10. 访问者模式（Visitor）数据与操作分离
11. 解释器模式（Interpreter） 虚拟机的机制，解释器

**并发型模式** 

**云设计模式** 

1. **Ambassador(代表模式)** 可用于以一种与语言无关的方式卸载常见客户端连接任务，如监视、记录、路由、安全（如 TLS）。
2. **Anti-corruption layer (防损层模式)** 实现了新旧应用程序之间的外观，以确保新应用程序的设计不受遗留系统依赖性的限制。使用此模式可确保应用程序的设计不受限于对外部子系统的依赖。 此模式最先由 Eric Evans 在 Domain-Driven Design（域驱动的设计）中描述。
3. **Backends for Frontends (用于前端的后端模式)** 创建单独的后端服务，供特定的前端应用程序或接口使用。 要避免为多个接口自定义一个后端时，此模式十分有用。后端为不同类型的客户端（如桌面和移动设备）创建单独的后端服务。这样，单个后端服务不需要处理各种客户端类型的冲突要求。通过分离客户特定的问题，这种模式可以帮助保持每个微服务的简单性。
4. **Bulkhead（隔舱模式**）之所以称为“隔舱”(Bulkhead)，是因为它类似于船体的分段区。 如果船体受到破坏，只有受损的分段才会进水，从而可以防止船只下沉。为每个工作负载或服务隔离关键资源，例如连接池，内存和CPU。通过使用隔板，单个工作负载（或服务）无法消耗所有资源，使其他资源匮乏。此模式通过防止由一个服务引起的级联故障来提高系统的弹性。
5. **Gateway Aggregation（网关聚合模式）**使用网关可将多个单独请求聚合成一个请求。 当客户端必须向不同的后端系统发出多个调用来执行某项操作时，此模式非常有用使用网关可将多个单独请求聚合成一个请求。 当客户端必须向不同的后端系统发出多个调用来执行某项操作时，此模式非常有用。
6. **Gateway Offloading（网关卸载方式）**将共享或专用服务功能卸载到网关代理。 此模式可以通过将共享服务功能（如 SSL 证书的使用）从应用程序的其他部分移动到网关，简化应用程序开发。
7. **Gateway Routing（网关路由模式）**使用单个终结点将请求路由到多个服务。 如果希望在单个终结点上公开多个服务，并根据请求路由到适当的服务，则此模式非常有用。
8. **Sidecar（挎斗模式 ）**将应用程序的帮助程序组件部署为单独的容器或进程，以提供隔离和封装。使用此模式还可以使用异构组件和技术来构建应用程序。
9. **Strangler（绞杀者模式）**通过将特定的功能片断逐渐取代为新的应用程序和服务，逐步迁移旧系统。 随着旧系统的功能被替换，新系统最终将取代旧系统的所有功能，抑制旧系统并使其停用。通过逐步用新服务替换特定功能来支持增量迁移。

**设计工具使用** 

1. starUML
2. powerdesigner
3. Processon
4. gitMind

**UML建模：**

UML图：类图、对象图、构件图、组合结构图、用例图、顺序图、通信图、定时图、状态图、活动图、部署图、制品图、包图、交互概览图。

（1）类图：描述一组类、接口、协作和他们之间的关系，是最常见的图

（2）对象图：描述一组对象及他们之间的关系。描述了在类图中所建立的事物实例的静态快照。

（3）构件图：描述一个封装的类和它的接口、端口、以及由内嵌的构件和连接件构成的内部结构。

（4）组合结构图：描述结构化类的内部结构，包括结构化类与系统其余部分的交互点。组合结构图用于画出结构化类的内部内容。

（5）用例图：展示系统的功能，描述一组用例、参与者及它们之间的关系。以图形化的方式描述系统与外部系统及用户的交互，描述用户需求，包括基于基本流程的角色关系等。

（6）顺序图（也称序列图），是一种交互图，交互图展现了一种交互，它由一组对象或参与者以及他们之间可能发送的消息构成。

（7）通信图：也是一种交互图，它强调收发消息的对象或参与者的结构组织，通信图强调的是对象之间的组织结构。

（8）定时图：（也称计时图），是一种交互图，它强调消息跨越不同对象或参与者的实际时间，而不仅仅关心消息的相对顺序。

（9）状态图：描述一个状态机，它由状态、转移、事件和活动组成，强调事件导致的对象行为。（运行状态、维护状态、停站状态）

（10）活动图：将进程或其他计算结构展示为计算内部一步步的控制流和数据流，是一种动态视图，强调对象之间的控制流程。

（11）部署图：描述对运行时的处理节点及在其中生存的构件的配置。

（12）制品图：描述计算机中一个系统的物理结构。制品包括文件、数据库和类似的物理比特集合。

（13）包图：包图描述由模型本身分解而成的组织单元，以及他们之间的依赖关系。

（14）交互概览图：交互概览图是活动图和顺序图的混合物。

**项目设计流程** 

需求设计 

系统设计 

接口设计 

原型设计 

**数据库的设计** 

数据字典设计 

逻辑结构设计 

物理结构设计 

数据表设计 

## Linux 

#### 发行版(Server) 

Ubuntu 

Redhat 

CentOS 

#### 数据 

##### NoSQL 

MongoDB 

ELK 

文档模型 

#### 分片 

分布式缓存 

Memocached 

Redis(重要) 

#### 关系型数据库 

MySQL 

引擎 

分库分表 

SQL优化 

SQL注入 

事务隔离级别 

锁 

数据库设计 

其它 

#### 搜索引擎 

Solr 

Elastic Search 

#### 大数据 

Hadoop 

Hbase 

Spark 

Storm/jStorm 

### 算法与数据结构 

#### 必备数据结构 

线性表 

数组 

链表 

队列 

栈 

#### 树 

二叉树 

BST 

AVL树 

红黑树 

B树 

B+树 

#### 堆 

二叉堆 

小顶堆 

大顶堆 

#### 图 

有向图 

无向图 

简单图 

完全无向图 

有向完全图 

有向无环图 

#### 散列表 

函数构造 

冲突处理 

命中查找 

### 字符串 

查找匹配 

正则 

数组 

链表 

栈 

队列 

### 树 

二叉树 

B Tree/B+ Tree 

红黑树 

### 哈希 

哈希冲突 

K-V 

### 图 

BFS 

DFS 

### 排序 

#### 内部排序 

插入排序 

直接插入排序 

希尔排序 

#### 选择排序 

简单选择排序 

堆排序 

#### 交换排序 

冒泡排序 

快速排序 

归并排序 

基数排序 

桶排序 

外部排序 

### 排序算法 

冒泡 

选择 

插入 

归并 

快速 

希尔 

### 贪心算法 

分金条问题 

IPO问题 

路灯问题 

字典序问题 

NIM博弈 

### 暴力算法 

汉诺塔问题 

八皇后问题 

牛吃草问题 

扑克牌问题 

字符串全排 

### 动态规划 

背包类问题 

顺序尝试题 

区间划分题 

业务限制题 

样本对应题 

斐波那契题 

树形DP题 

数位DP题 

## 分布式系统 

从集中式到分布式 

分布式事务 

#### 分布式Session 

Session复制 

Session绑定 

Session服务器 

#### 分布式缓存 

Redis 

一致性 

## 数据库 

读写分离 

主从热备 

分库 

分表 

一致性 

分布式事务 

CAP 

BASE 

2PS/3PC 

Paxos 

### Mysql 

#### 基础语法 

DDL（数据定义语言） 

DML（数据操纵语言） 

DCL（数据控制语言） 

#### 数据库表设计 

视图 

约束 

#### 索引机制 

索引的实现机制 

索引的数据结构 

索引的分类 

索引与存储引擎 

索引的设计 

索引的优化 

#### 事务机制 

ACLD 

事务的实现原理 

undo log 

redo log 

binlog 

mvcc 和二阶段提交 

#### 锁机制 

共享锁 

独占锁 

排它锁 

自增锁 

间隙锁 

临键锁 

#### JDBC 

SPl 

connection 

statement 

preparestatement 

resultset 

反射 

### 分布式锁 

Redisson 

### 负载均衡 

硬件:F5 

软件:LVS 

### 消息队列 

ZeroMQ 

RabbitMQ 

ActiveMQ 

Kafka 

### 服务化 

服务注册与发现 

Zookeeper 

架构 

### 微服务 

Spring Boot 

Dubbo 

RPC 

SOA 

### 虚拟化 

Docker 

计算平台 

实时 

离线 

容灾,异地多活 

## 项目管理 

角色 

成果 

思路 

技术栈 

### 项目保障工具 

#### 开发规范 

1. 编程规约
2. 异常日志

#### 安全规约 

MySQL数据库规约 

1. 工程结构
2. 设计规约

#### 日志集成 

1. slf4j
2. logback
3. log4j
4. commons logging

#### 单元测试 

1. junit
2. Mock

#### 集成测试 

#### 代码检查 

1. sonarqube
2. findbugs

#### 持续集成 

#### jenkins 

## 阅读源码能力 

### 基础源码阅读能力 

1. JDK源码
2. ArrayList源码
3. HasHset源码
4. HashMap源码
5. ConcurrentHashMap源码

### 线程池源码 

1. Spring源码
2. IOC源码
3. AOP源码
4. 后置处理器源码
5. 多播器监听器源码

### SpringMVC 源码 

1. Dispatcherserlet源码
2. 请求处理器源码
3. 适配器源码
4. 拦截器源码

### MyBatis 源码 

配置文件加载源码 

MapperProxy创建源码 

executor源码 

### SpringBoot 源码 

springboot启动流程源码 

自动装配源码 

整合Tomcat源码 

 

## 前端技术 

### HTML 和 html5 

网络传输三大基石 

HTML的标准结构 

HTML 的基本标签 

HTML 的多媒体标签 

HTML5的新特性 

### CSS3 

CSS 的书写方式 

CSS的基本选择器 

CSS的关系选择器 

CSS的属性选择器 

CSS的浮动和定位 

CSS的盒子模型 

### Javascript 

JavaScript的基本语法 

JavaScript的函数 

JavaScript的事件绑定 

JavaScript的DOM操作 

### Jquery 

jQuery的基本语法 

jQuery的轮播图 

### Ajax 

Ajax的基本原理 

Ajax的使用方式 

Ajax的接受数据方式 

Ajax的三级联动

### vue 

1. VUE的介绍和使用
2. vue的调色板和函数
3. vue的生命周期
4. vue的组件使用
5. vue的属性监听
6. vue的高阶使用

## 性能 

全链路延时，每个系统的链路延时 

性能调优 

## **第三方对接** 

企业微信 

微信 

银企直联 

## DevOps 

容器化 

 

## 测试 

单元测试 

集成测试 

确认测试 

回归测试 

自动化测试 

压力和容量测试 

测试用例 

白盒 

黑盒 

junit 

Spring Test 

CmdExcetor 

## 分布式 

分布式事务

监控

DDD



 

## 中间件 

MQ 
ES 


## 软技能 

沟通

周报

## 工具 

### 笔记 

1. Evernote
2. 有道云笔记
3. 插件
4. Chrome Evernote

### 通用框架处理 

1. 异常处理 
2. SSO和跨域登录
3. 数据变更历史