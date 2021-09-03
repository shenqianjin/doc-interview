# doc-interview

[位运算](./base/bit-operation.md)


---

## 设计模式

- 单例：
  - [单例模式的三种实现 以及各自的优缺点](https://blog.csdn.net/YECrazy/article/details/79481964)
  - [单例模式－－反射－－防止序列化破坏单例模式](https://www.cnblogs.com/ttylinux/p/6498822.html)


  - [23种常见设计模式](https://github.com/xingshaocheng/architect-awesome/blob/master/README.md#%E5%BA%94%E7%94%A8%E5%9C%BA%E6%99%AF)
  - 


- [Kubernetes中文社区 | 中文文档](http://docs.kubernetes.org.cn/)

- [互联网公司常用框架源码赏析](https://github.com/doocs/source-code-hunter)

[Spring RMI](https://github.com/doocs/source-code-hunter/blob/main/docs/Spring/RMI/Spring-RMI.md)

### Netty
[Netty实战入门详解——让你彻底记住什么是Netty（看不懂你来找我）](https://www.cnblogs.com/nanaheidebk/p/11025362.html)

- OAuth

[OAuth 2.0 的一个简单解释](https://www.ruanyifeng.com/blog/2019/04/oauth_design.html)

[OAuth 2.0 的四种方式](https://www.ruanyifeng.com/blog/2019/04/oauth-grant-types.html)

[GitHub OAuth 第三方登录示例教程](https://www.ruanyifeng.com/blog/2019/04/github-oauth.html)



[TCP状态转换图详解](https://blog.csdn.net/wenqian1991/article/details/40110703)




思路：因为有16瓶水，让找出至少14瓶，所以两瓶为一组，那就是8组，只要小白鼠的状态能出现8种不同的结果，那么就能确定有毒的在哪一组里，因为2的3次方等于8，所以需要3只小白鼠。我相信这个思路实际上也提供了一种算法，应该是最简的了。
具体步骤：
将16瓶水两瓶为一组，组号标为A1-A8，三只小白鼠分别标号为b1、b2、b3，A1组水只让b1喝，A2组只让b2喝，A3组只让b3喝，A4组让b1、b2喝，A5组让b1、b3喝，A6组让b2、b3喝，A7组让b1、b2、b3喝，A8组不喝。如果只有b1死了，b2、b3都活着，那么有毒的水在A1组里，剩下的14瓶无毒；如果只有b2死了，b1、b3都活着，则A2组有毒；如果只有b3死了，b1、b2都活着，则A3组有毒；如果b1、b2死，b3活，则A4组有毒；如果b1、b3死，b2活，则A5有毒；如果b2、b3死，b1活，则A6有毒；如果三只全死，A7组有毒；如果三只全活，A8有毒。


[git 打tag](https://www.jianshu.com/p/cdd80dd15593)


latency numbers:
https://dev.to/sahilrajput/how-latency-numbers-changes-from-1990-to-2020-173n
https://github.com/colin-scott/interactive_latencies
https://www.jianshu.com/p/c926e0674f01
https://www.jianshu.com/p/cdd80dd15593

不可重复读 VS 幻读
不可重复读：事务 A 多次读取同一数据，事务 B 在事务A多次读取的过程中，对数据作了更新并提交，导致事务A多次读取同一数据时，结果不一致。幻读：系统管理员A将数据库中所有学生的成绩从具体分数改为ABCDE等级，但是系统管理员B就在这个时候插入了一条具体分数的记录，当系统管理员A改结束后发现还有一条记录没有改过来，就好像发生了幻觉一样，这就叫幻读。小结：不可重复读的和幻读很容易混淆，不可重复读侧重于修改，幻读侧重于新增或删除。解决不可重复读的问题只需锁住满足条件的行，解决幻读需要锁表
链接：https://www.zhihu.com/question/38507762/answer/1152793284

[MySQL的可重复读级别能解决幻读吗](https://www.cnblogs.com/liyus/p/10556563.html)

[为什么MySQL分页用limit会越来越慢](https://www.jb51.net/article/218042.htm)


---
[Markdown 代码块与语法高亮](https://www.jianshu.com/p/65ab196bef04)

[技术文档写作规范(Markdown)](https://www.jianshu.com/p/3b638180e42c)

[为什么要用ETL](https://zhuanlan.zhihu.com/p/337994072)

[Mybatis简介以及工作原理](https://www.cnblogs.com/leduo-zuul/p/10679367.html)




-----------
#### 
[Alan - 数据分析、挖掘、机器学习](https://www.zhihu.com/people/ou-min-yang-38)
- [推荐系统（1）-业界推荐系统架构](https://zhuanlan.zhihu.com/p/93183929)

[《面试八股文》系列大全](https://mp.weixin.qq.com/s/xxd_bxgVWIgfB5QIVPfZsQ)
- [《面试八股文》之Dubbo17卷](https://mp.weixin.qq.com/s?__biz=Mzk0MjA4ODcxNQ==&mid=2247498926&idx=1&sn=da6c9a5185fd77b642967f046e85ae4b&chksm=c2cacbcaf5bd42dc66dfed29f35d6ce4bf1a57d3726277143dfffa039d5f3e6aa9809b96f45c&scene=21#wechat_redirect)
- [《面试八股文》之Zookeeper12卷](https://mp.weixin.qq.com/s?__biz=Mzk0MjA4ODcxNQ==&mid=2247499180&idx=1&sn=3574f2c29ab7fa1d8a827761d3769199&chksm=c2cacac8f5bd43dec28430e86a6f22411890d6e4c49bdd68f484eb499d84f1fd102aa21351c5&scene=21#wechat_redirect)

