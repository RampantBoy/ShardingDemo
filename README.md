优点:

1.基于java的ORM框架,如:JPA、Hibernate、Mybatis、Spring JDBC Template,或直接使用JDBC。
2.可基于任何第三方的数据库连接池,如:DBCP、C3P0、Durid等
3.支持多表多库insert、select、delete、update、left join、count等语句。
4.SQL解析功能完善,支持聚合、分组、排序、limit、or、where in等查询,并支持Binding Table以及笛卡尔积表查询。
5.支持Transactional事务。
6、支持读写分离。


缺点：

1. 不支持动态分表分库，需进行代码改造。
2.维护会比较麻烦，需要逐个项目的修改配置。
3.在扩展数据库服务器时需要考虑一致性哈希问题，或者采用分片键局部取模方式。
