# JavaCake
Java后端知识总结
目录(善用Ctrl+F)
---
- Java基础
- JVM
- 数据结构及算法
- MySQL
- Redis
- 设计模式
- 计算机网络
- 操作系统
- 框架与中间件

Java基础
---

- 集合
  - [List子类](http://note.youdao.com/noteshare?id=f19b1a1b1d0cc47583691b1a8cff62b1&sub=87AEAAD8C1A048EC845EF079E10267CA)
  - [Map子类](http://note.youdao.com/noteshare?id=ce6307e614ff1e8f6735a5547844bf14&sub=246962494C1B4D0F85573E9D898A8AC3)
  - Set子类(底层就是Map，只不过Value部分的值为 new Object() 对象)
  - [线程安全的集合](http://note.youdao.com/noteshare?id=15a2959b7ceeea386edb8d0e8bf82e7e&sub=902B0C47BB17493EB03D6AD07453C648)
- 多线程
  - [线程基本概念及相关API](http://note.youdao.com/noteshare?id=50a24de673cb13a2306b8767873dd948&sub=DA266E0674174638BCBF1A216462972F)
  - synchronized
  - Reetrentlock
  - valotile
  - 线程池
  - ThreadLocal
- 其他
  - String、StringBuilder、StringBuffer
  - finally、final、finalize
  - equals和==

JVM
---
  
参考书本 《深入理解Java虚拟机-周志明》

- Java内存区域

- 类加载

- 对象创建过程

- 垃圾回收机制

数据结构及算法
---

题目均来源于 LeetCode ，参考LeetCode英文版、中文版精品题解

- [二叉树相关](http://note.youdao.com/noteshare?id=5acc43f80b3eba112bc544fbf62d0fc8&sub=84AF318114D6475988B1EBE9C4689B31)

- [链表相关](http://note.youdao.com/noteshare?id=4d33db9918200566ff5cc371df5e0613&sub=FE5287D0056749A1B11BF5D3AAF8F941)

- 动态规划

- [深搜广搜](http://note.youdao.com/noteshare?id=b283e09cb0f3cb9fced81e48d7035d25&sub=39326FE2F0904471888FF3067DB9B5EF)

- 回溯

- [并查集模板](http://note.youdao.com/noteshare?id=aa9e76273c31b512f49ec550e910d988&sub=84610963E4E34AF580D15DFB4AE26982)

- [排序相关](http://note.youdao.com/noteshare?id=71bcf6af60bda61fd207d0794bd0d910&sub=D344BBB25D2E4C938852EA1AEF8D23B3)

- [双指针及滑动窗口](http://note.youdao.com/noteshare?id=a01a0edfca7bfcec4ab35d884540cdd0&sub=796CC0AB5E7445D7ACF26FB92F504CE2)

- [LRU](http://note.youdao.com/noteshare?id=142928d8047bc5ef5575fff892023b97&sub=28E949704D5E4113B29135B355BA524B)

MySQL
---
MySQL学习推荐看《从根上理解MySQL》

- [InnoDB的B+树索引(需要清楚数据页结构)](http://note.youdao.com/noteshare?id=c1ab299c970454610ff6f4f8539ca6fd&sub=8B2B21390E0E48AD8585B83A81FDA171)

- [InnoDB中各种索引](https://blog.csdn.net/weixin_43871956/article/details/109788443)

- [连接原理Join](http://note.youdao.com/noteshare?id=ba685563d8dc2250a5dac9c9f8a5b43f&sub=4054FB002C2F4D329894F20F28E76D9A)

- [Explain主要字段](http://note.youdao.com/noteshare?id=7183761ef7ebfec7d9ef3c1a22e00035&sub=7A9BFF895FAD4858B47EAA81229F2357)

- [Buffer Pool](http://note.youdao.com/noteshare?id=095eb704511d6c4d7a036727a1a8f6fb&sub=532EDE690A81465AB3B9BDBDB0657F48)

- [MySQL事务及MVCC](http://note.youdao.com/noteshare?id=9bc0f6cd0ff42ace4f40d1275a7096df&sub=A025D1792C4A401584BB6B9A3AC01E6A)

- [Redo日志 和 Undo日志(了解)](http://note.youdao.com/noteshare?id=3eb6289ac2f349e3c186989fc0571df4&sub=AABD211B72DA4651B16A2DE8B2B63488)

- 锁

Redis
---

参考书本 《Redis设计与实现》

- [Redis的基本操作](http://note.youdao.com/noteshare?id=a52777330ee415d783c1d5c4f4fa99af&sub=404CD968E38D489885E2B009F73D8FA1)

- [基本数据类型的原理(SDS、List、quickList...)](http://note.youdao.com/noteshare?id=ba68d728d359a9710d71b16c9e7906bf&sub=6403F3FFB17D46B9AC32974CE71E44E5)

- [持久化及性能保障](http://note.youdao.com/noteshare?id=46278ef69a23b8a24a302efd77f5f14c&sub=CC8EB02E5CD041EA822A5636093FC4BD)

- [Redis为什么这么快](http://note.youdao.com/noteshare?id=872cf5559f7dbfaa169b98cb8b683b4b&sub=2F8F9A021DEE4F93B370E9901AD25979)

- [缓存穿透、雪崩、击穿](http://note.youdao.com/noteshare?id=b52f5db013f625e42d8e69de1f6cd3f3&sub=713D7413903043F9BAA2ABDE54E229E5)

设计模式
---

- 单例模式

- 原型模式

- 工厂模式
  - 工厂方法
  - 抽象工厂

- 代理模式
  - JDK
  - Cglib

计算机网络
---
计算机网络推荐看wx公众号——小林Coding

- [输入URL到页面显示发送了什么](http://note.youdao.com/noteshare?id=c1070c44c08769ebc755418d5fd306df&sub=3B0F7FEB8A914EA9AE1301A08AEE5394)

- [Cookie和Session](http://note.youdao.com/noteshare?id=9106fdbaf8f8cc5df236900431bb9825&sub=87A6C0DD7DB44089843BAF71D663BD9F)

- [GET和POST的区别](http://note.youdao.com/noteshare?id=59248c82ff69f8c8dd020c78d7a6e086&sub=F1832C7907F4433E991A678032E118D5)

- [HTTP演变及HTTPS的握手过程](http://note.youdao.com/noteshare?id=cda67d2f122be5f0a1062c6f4c425353&sub=A24280C128354BC1A419E2E3D56FEF8A)

- [对称加密和非对称加密](http://note.youdao.com/noteshare?id=4a33f35265e8a14f46781e4731f9044d&sub=F9570F8C683E49099A91993F62D90885)

- [TCP和UDP](http://note.youdao.com/noteshare?id=f38c2c84d14f64834955af6eff54bed0&sub=CC708637BD784363BD97C952472CA404)

- TCP重传、滑动窗口、流量控制、拥塞控制

- [TCP三次握手详解](http://note.youdao.com/noteshare?id=feb04ab447424fd26149b41f702c9fda&sub=C0E2F5E740D349A5A465D76435043E3A)

- [TCP四次挥手详解](http://note.youdao.com/noteshare?id=8ebb2e93ce54000e545b12955b579c0c&sub=3C0FF111D46843C2A3E1C064530C15C8)

- [TCP传输数据的性能提升](http://note.youdao.com/noteshare?id=c160f645697336cfe0c017619328baeb&sub=D72253BCBD6846E3828BBFC9F761921F)

操作系统
---

推荐看wx公众号——小林Coding  操作系统教科书


- [内存管理](http://note.youdao.com/noteshare?id=911d274e64fdf966f941bae7a5c27ac5&sub=897C1A7020174E69A2771587C88F01B9)
  - [写时复制技术](http://note.youdao.com/noteshare?id=e9fb06a522117dbb296f381e40e6ca85&sub=F7F4FAA7A6F349ACBF744002D522982B)

- 进线程管理
  - [进程](http://note.youdao.com/noteshare?id=ca51e537d59c67553f3159287969ca9a&sub=EC94DB0D3E954BFCBAB450D6944379D3)
  - [进程间通信](http://note.youdao.com/noteshare?id=29df6e0063081c244ff3c1fff7a077e0&sub=ED3AA81B18C343DE99502C93F3C672E8)
  - [线程、协程](http://note.youdao.com/noteshare?id=dd4144292a4a23bf04e693fb94bbbb83&sub=B2E19C7510B2423BA57EAF0675DDD3C9)
  - [调度算法](http://note.youdao.com/noteshare?id=30083e84a8c61e82408adb3199f97230&sub=18CC2B7BB915446C96915814B1E2C91D)

- 文件系统管理

- 输入输出设备管理

框架与中间件
---

- SpringIOC及AOP

- SpringMVC

- Mybatis

- Nginx

- RabbitMQ
