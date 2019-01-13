#java-must-know

**Java must know for java developers**

> 关于Java平台   
1.0 Java平台有哪些特性
安全
高效
易于分发
自动内存管理
可移植性
1.1 GC 关于垃圾自动回收 
不用关注内存分配
回收机制：
分代算法：新生代，老年代，永久带

引用计数法
可达性分析

1.2 Write once, run everywhere 关于虚拟机，性能问题 Java 一般被认为解释型语言，不同于编译语言。.java文件首先是被编译为类文件（.class文件），然后由不同平台的虚拟机来解释执行。 

1.3 java 程序执行机制 
javac-----(java)----class
类加载（加载--》链接--》初始化）


1.3.1 类加载器有哪些？
Bootstrap
ExtClassLoader
AppClassLoader

1.3.2 Java有哪些基本的数据类型？

byte,int,double,char,boolean

包装类型：
Integer,Double,Boolean



1.4 java内存模型 

堆： 给程序员的对象的用的内存池

栈：虚拟机栈，创建线程时创建，线程私有

JVM内存：
PC 寄存器

###2 Java多线程设计模式

###3 JDK 有哪些工具，怎么使用？ 

	3.1 jstat 查看堆内存
	
	jstat -gc垃圾回收统计
	
		
	

	3.2 jmaps &&jhat
	堆栈信息
	3.3 jstack 线程快照

##4. Java 的生态 

4.1 Web 开发 
Java最主要是作为web应用的后端语言，拥有丰富的生态和工具

4.1.1 Spring Framework,Spring Boot

Spring Core: 
Spring容器:Bean Factory
依赖注入(dependency injection)/控制反转(control inversion)

把组装对象的任务交给容器来完成。

###4.1.2 JDBC, 连接池

C3P0,DRUID

###4.1.3 MVC

web应用设计模式


###4.1.4 ORM框架 

Mybatis,Hibernate,JPA,JdbcTemplate
对象关系映射
Mybatis:sql 映射框架
Hibernate:ORM 框架

##SQL 5.1 

basics 

** basic data type基本数据类型

int char varchar text date time datetime float blob json 

** create/alter/drop database, table add column rename table

** add constraint 增加约束

add primary key auto-increment add foreign key() reference () add check unique not null ** select from

** join/left join/right join链接

**union/union all联合

** subquery子查询

** where clause and,or,not,in ** aggregation group by ** function函数

** delete from

** view视图

** temperary table临时表

5.2 数据库管理 

mysqladmin mysqldump 

grant priviledges on <..> to <..>

导出到外部文件
select <...> into outfile create table from select <...>

5.3 SQL 优化 

index建立索引 

** unique,primary fulltext explain limit offset,count limit count

分布式计算 

Spring Cloud基于Spring Boot
fast-failover 负载均衡 横向扩展 监控，熔断

API 网关 注册 中心 Mesage Broker

函数式编程，Scala, 流式计算API Java 8
什么是scala,有哪些特性？lamda 表达式，高阶函数 8. 大数据 hdfs,mapreduce hadoop, spark storm,flume hbase,hive

9 软件架构
