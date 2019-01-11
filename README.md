# java-must-know
Java must know for java developers


1. 关于Java平台
1.1 GC 关于垃圾自动回收
Java语言不需要显示申请内存空间，释放内存空间，这些都交给GC 来完成。 他是后台默默帮你做这些。
1.2 Write once, run everywhere 关于虚拟机，性能问题
Java 一般被认为解释型语言，不同于编译语言。.java文件首先是被编译为类文件（.class文件），然后由不同平台的虚拟机来解释执行。
1.3 java 程序执行机制
  1.3.1 类加载器有哪些？
  
  1.3.2 Java有哪些基本的数据类型？
  
  
1.4 java内存模型
堆：
栈：


2. Java多线程设计模式

3. JDK 有哪些工具，怎么使用？
  3.1 jstat
  
  3.2 jmaps
4. Java 的生态
  4.1 Web 开发
    4.1.1 Spring Framework,Spring Boot
    
    4.1.2 JDBC, 连接池
    C3P0,DRUID
    4.1.3 MVC
    web应用web层设计模式
    
    4.1.4 ORM框架 Mybatis,Hibernate,JPA,JdbcTemplate
    Mybatis:sql 映射框架
    Hibernate:ORM 框架
5. SQL
  5.1 basics
  ** basic data type
  int
  char
  varchar
  text
  date
  time
  datetime
  float
  blob
  json
  ** create/alter/drop database, table
  add column
  rename table
  
  ** add constraint
  add primary key auto-increment
  add foreign key(<column>) reference <parent-table>(<column>)
  add check 
  unique
  not null
  ** select from
  
  ** join/left join/right join
  
  **union/union all
  
  ** subquery
  
  ** where clause
  and,or,not,in 
  ** aggregation
  group by
  ** function
  
  ** delete from
  
  **  view
  
  ** temperary table
  
  
  5.2 数据库管理
  mysqladmin 
  mysqldump
  grant priviledges on <..> to <..>
  
  select <...> into outfile <filename>
  create table from select <...>
  
  
 
  5.3 SQL 优化
  index建立索引
  ** unique,primary
  fulltext
  explain
  limit offset,count
  limit count
  
  
  
  6. 分布式计算
  Spring Cloud基于Spring Boot
  
  fast-failover
  负载均衡
  横向扩展
  监控，熔断
  
  
  API 网关 
 注册 
 中心 
 Mesage Broker
 
  7. 函数式编程，Scala, 流式计算API
  Java 8
  
  什么是scala,有哪些特性？lamda 表达式，高阶函数
  8. 大数据
  hdfs,mapreduce
  hadoop, spark
  storm,flume
  hbase,hive
  
 9 软件架构
  
