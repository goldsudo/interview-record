## 18年6月份至9月份期间面试过程中遇到的问题总结
从6月份至今，我一共参加了15家公司的20+场面试，受益匪浅，也深深认识到了自己的不足。<br>

我一直有记录面试过程的习惯，因此每场面试的题目我都大致的记录在了手机上的备忘录中。<br>

目前面试过的公司有：<br>
redapple,国睿,华为,天猫,帆软,赫智,汇智,清能互联,虎牙,有赞,yy,shein,东方网力,全知,polyv <br>

有电面（天猫，帆软，清能，赫智，有赞，yy，全知）<br>
有笔试（polyv，虎牙）<br>
有远程代码面（天猫）<br>
也有现场的多轮复面（国睿，yy，shein，东方网力等）<br>
当然还有性格测试（华为，shein）<br>

最后除了天猫和虎牙外的面试都基本过了，其中有些公司因为不太感兴趣或者有更好的选择了，就没继续参加后续的面试。<br>

这三个月下来，就一个感觉“知道的越多，就知道自己知道得越少”。放在it行业简直不能再正确了，每一轮面试都能发现自己很多知识点都不清楚，回来后自己去各种恶补，然后再参加下一个面试。<br>

现在拿到满意的offer了，就不想再折腾了，一直动嘴皮子的感觉其实很糟糕，还是写代码的时候心里踏实，将来希望自己能沉下心来持续进步。<br>

这个仓库用来记录一下这三个月来的面试题汇总，我写了部分问题的回答，请参见“我给出的答案（部分）.txt”，或者各个技术分类的题目文件，我会陆续地把这些问题的答案更新上来。<br>

另外，部分问题虽然在面试过程中没有被问到，但是我认为是可能会被衍生出来的子问题，所以我也将这些问题整理出来了。

## 面试题汇总
1.java：
```
java8有哪些新特性?lamda与stream了解吗？
介绍下java的nio？
io中缓冲区的作用?为什么缓冲区可以加块读取速度？
介绍下netty？
了解java的深拷贝与浅拷贝？
详细描述下java中的hashmap实现原理（附加：jdk1.8之前与1.8之后，hashmap的实现有什么区别）？
hashmap中的loadFactor的取值大小对hashmap有什么影响？
hashmap中put一万个元素应该怎么做？
hashmap、hashtable、concurrenthashmap的区别？（附加：concurrenthashmap的实现原理）？
treemap、linkedhashmap的作用？
hashset的实现原理？
arraylist、linkedlist、vector的区别？
如何判断一个对象是否可被gc？
jvm内存结构？
jvm的gc原理，每个内存区域使用什么gc算法？
java的new关键字在jvm层面都做了哪些事？
知道哪些jvm垃圾收集器？
java内存模型？（注意与jvm内存结构不是一回事）
jvm是如何实现一次编译到处运行的?
十个线程同时++i会出现什么问题？为什么？如何解决?
automicinteger的实现原理？
如何在运行时估算一个java对象的大小？
有哪些可以监控jvm内存使用情况的工具?这些工具的实现原理？
线程和进程的区别？
java创建一个线程的几种方式？（Thread、Runnable、Callable、ExecutorService线程池）
悲观锁、乐观锁、自旋锁？
独占锁、共享锁？读写锁？
偏向锁、轻量级锁、重量级锁？
公平锁/非公平锁？
介绍下volatile与synchronized关键字的作用？
tomcat的实现原理？
序列化和反序列化？（protostuff可以减小对象序列化后的大小）
线程有哪些状态？
线程阻塞分为哪几种情况？
有哪些类型的线程池构造方法？
线程池有哪些重要的配置？
线程池中的线程数量达到最大值后会怎样？
业务高峰过后，线程池中的线程数量多余的话会怎样？
线程池容量能不能动态调整？
```
2.spring：
```
servlet与springmvc有什么区别？
springboot与springmvc的比较大的区别，从使用者的角度来说？
springmvc中，要删除一个cookie，要用什么方式来操作？
日常springmvc或springboot项目开发中，有采取过什么样子的方法来防止引起的安全问题？举个例子？
spring的事务隔离级别?
spring的ioc初始化过程？
spring的ioc与aop的实现原理？
spring cloud了解吗？
```

3.mybatis：
```
mybatis的优缺点？
jdbc与mybatis的区别？
mybatis如何实现表间关联查询？
mybatis如何实现分页？
```

4.设计模式：
```
单例模式有哪些实现方式，是否线程安全？
代理模式和装饰器模式的区别？
工作中用过哪些设计模式？（工厂、策略、建造者）
```

5.网络：
```
cookie和session的联系是什么？
session一致性问题？
http的get与post的区别？
TCP的三次握手与四次挥手？
TCP滑动窗口、拥塞控制、慢启动？
TCP连接的本质是什么?
IP路由过程中，上一个包刚被当前路由器转发后，当前路由器挂了，之后会发生什么？TCP链路断了吗？
```

6.数据库：
```
mysql的事务隔离级别？
mysql的索引实现原理？hash，二叉搜索树，b树，b+树的区别？
什么时候应该使用索引？
什么场景会导致索引无效?
mysql中如何利用sql进行分页查询？
oracle中如何利用sql进行分页查询？
会写mysql存储过程吗？
oracle中的over partition by（分析聚合函数）会用吗?
join、left join、right join的区别？
介绍下数据库分库与分表？
oracle表分区了解吗？
有没有sql优化的经验？有哪些sql优化的技巧？
```

7.redis：
```
redis中有多少种数据结构？
redis是单线程的吗？
为什么redis很快？
redis的RDB与AOF两种持久化机制的区别？
如何利用redis实现分布式锁？
如何利用redis实现客户端恶意脚本批量请求的防攻击检测？
如何利用一致性hash实现redis集群？
如何用redis实现消息队列？
redis缓存击穿怎么办？
redis与memcached的区别？
redis从哪个版本开始支持集群？
redis集群怎么部署？
```

8.web安全：
```
防止sql注入的方法是什么？
sql预编译为什么可以防范注入？
了解CSRF吗，常见的解决方法是？
了解XSS吗，常见的解决方法是？
了解DDOS吗？
SYN FLOOD呢？
NTP FLOOD呢？
```

9.算法与数据结构：
```
一致性哈希算法的实现原理？
一致性hash与普通hash有什么区别？
如何判断一个单链表是否有环？如何找到环的入口？
如何判断两个单链表是否相交？
如何求一颗平衡二叉树的高度和宽度？
如何实现一个O(1)时间求最小值的栈？
两个栈实现一个队列？
两个队列实现一个栈?
bitmap（位图索引）？如何利用bitmap实现快速数据查询？
希尔、快排、归并、堆排？
如何镜像翻转一颗二叉树？
如何求最长连续递增子序列？
如何求报数问题？（n个人围坐一圈报数，凡是报到m的人出队，问最后剩下的人的序号）
```

10.javascript:
```
javascript中的浅拷贝与深拷贝？
javascript的闭包是什么？
javascript的作用域、作用域链、执行环境、上下文这些概念的区别与联系？
javascript的原型链？
javascript中有几种遍历数组的方法？
javascript中如何删除数组中指定下标的元素？
javascript是单线程的吗？
javascript如何实现异步（比如setTimeout）？
```

11.vue：
```
vue可以用来做什么？
vue双向绑定的实现原理？
了解vue的virtual dom吗？
介绍下vue的生命周期？
介绍下vue-router？
vue的子路由嵌套？
vue的如何watch一个对象中的属性值的变动？
vue如何使得数组中的某一个对象的属性值变更时触发双向绑定？
```
