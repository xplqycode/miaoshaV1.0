# 秒杀项目
该项目主要模拟网购时商品的秒杀
技术栈：基于Spring、SpringMVC、Mybatis、MySQL、Redis、Tomcat



### 实现的功能以及做出的优化：

- 秒杀业务逻辑的实现，包括秒杀地址隐藏、秒杀执行、记录订单减库存
- 对链接暴露、恶意抢购、重复秒杀、Redis的缓存雪崩等问题进行解决
- 利用乐观锁、Redis缓存、前端限流进行并发优化
- 调整秒杀业务逻辑减少行级锁占有时间进行并发优化
