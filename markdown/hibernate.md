## hibernate
hibernate是一个开源的对象关联关系映射框架，它对JDBC做了轻量级的对象封装，它将POJO与数据库中的表建立映射关系；是一个全自动ORM框架。它的核心思想是：使用Java的面向对象的思想操作数据库；

```
graph TD
应用程序-->Configuration
xxx.cfg.xml-->Configuration
xxx.hbt.xml-->xxx.cfg.xml
Configuration-->SessionFactory
SessionFactory-->Session
Session-->开启事物
```
