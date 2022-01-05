# BackgroundDesignCake
后端知识总结
目录(善用Ctrl+F)
---
- Java基础
- JVM
- Golang开发相关
- 数据结构及算法
- MySQL
- Redis
- 设计模式
- 计算机网络
- 操作系统
- 设计数据密集型应用
- 领域驱动设计
- 框架与中间件
- 后端其他
- 技术底蕴

Java基础
---

- 集合
  - [List子类](http://note.youdao.com/noteshare?id=f19b1a1b1d0cc47583691b1a8cff62b1&sub=87AEAAD8C1A048EC845EF079E10267CA)
  - [Map子类](http://note.youdao.com/noteshare?id=ce6307e614ff1e8f6735a5547844bf14&sub=246962494C1B4D0F85573E9D898A8AC3)
  - [红黑树与平衡二叉树](http://note.youdao.com/noteshare?id=f47a338b40a7e0250abb89fea1791939&sub=C7C8B62509A840B9853C74C2B4AADF68)
  - Set子类(底层就是Map，只不过Value部分的值为 new Object() 对象)
  - [线程安全的集合](http://note.youdao.com/noteshare?id=15a2959b7ceeea386edb8d0e8bf82e7e&sub=902B0C47BB17493EB03D6AD07453C648)
- 其他
  - [String、StringBuilder、StringBuffer](http://note.youdao.com/noteshare?id=87a284eaf82cfc5fb6a89ac6c15f26a3&sub=EE08EBB5430943F89D713F92F4C2C777)
  - [finally、final、finalize](http://note.youdao.com/noteshare?id=8fb9e26886cb760549a520fbfb897b6e&sub=DC1E9E6FC0ED4FD3A4FDEF3994F11266)
  - [泛型](http://note.youdao.com/noteshare?id=798e92ae0ac22bf88bfb30ee22af55be&sub=D8751235BD1F47F6A07FFF10CCBB68D5)
  - [IO](http://note.youdao.com/noteshare?id=a6fa8933c5909614ae99e60cf032dcd7&sub=706E283A3F9046EAA1E0878D4F86076D)
  - [序列化方式](http://note.youdao.com/noteshare?id=cda176263eddc57deca4e3815a2a2778&sub=E0DEE271E2BF470F8F2F5386C6D24EE8)
  - [其他](http://note.youdao.com/noteshare?id=5d10a449dc0a917c1237771ad0ed6420&sub=WEB371c147fc86496c33e09cbd588cc720b)
- 并发编程（参考 Doug Lea 《Java并发编程实战》 和 方腾飞 《Java并发编程的艺术》）
  - [线程基本概念及相关API](http://note.youdao.com/noteshare?id=50a24de673cb13a2306b8767873dd948&sub=DA266E0674174638BCBF1A216462972F)
  - [synchronized 和 ReentrantLock](http://note.youdao.com/noteshare?id=397dfcefe841c48c349363324ba3bef3&sub=75FA85E7859F4413970FF663F400C822)
  - [AQS和CAS](http://note.youdao.com/noteshare?id=53b25cc87cf0fc5801de69860bfe8209&sub=339E33698D6542F6975ED886FBE796B1)
  - [valotile(需要前置知识：内存屏障、缓存一致性协议)](http://note.youdao.com/noteshare?id=adefbb92d62f8d53607415614bdfef2f&sub=0C924E4CB65F46B5BE5321426AC2E6FA)
  - [线程池](http://note.youdao.com/noteshare?id=4b79d967e1126beabb34c715c6b6a847&sub=E06931F8AFAC424DB279A420243DEA52)
  - [ThreadLocal](http://note.youdao.com/noteshare?id=9899c0563661deccd7a2cb75339b3ffe&sub=927743ADBE634E4F9D2C20D11CEDA3F9)
  - [Java内存模型](http://note.youdao.com/noteshare?id=0418b539d2316384425726bb5eab6dc9&sub=BA48EAB3DDC241518751A7F4996F72C1)
  - [CountDownLatch](http://note.youdao.com/noteshare?id=53f7e12296acc283c25ee01608df8c32&sub=132B44BA1D1346078882E96B907AA453)

JVM
---
  
参考书本 《深入理解Java虚拟机-周志明》

- [运行时内存区域](http://note.youdao.com/noteshare?id=ea87fb8d0901aad3fa4028dec01f85e6&sub=6DB852539776454ABFAEEA12824938D6)

- [类加载](http://note.youdao.com/noteshare?id=3dfba624da6b69858af7996070f9a8bf&sub=FAF814190FD74947B747AC327A4F7DA2)

- [对象创建过程](http://note.youdao.com/noteshare?id=2bb249795bb4219f80ac64426850cb9e&sub=284A71D2083D4529B30EEBABD6FEECCF)

- [垃圾回收机制](http://note.youdao.com/noteshare?id=cfd36d4437b1c24671f54f4e3ad3706d&sub=D36F75175A6D4808B5FEC0AE985D64F1)

- [OOM排查专题](http://note.youdao.com/noteshare?id=2babf03390530614a0181b7b92616749&sub=03C95485714946E4BA099C84F101F32F)

- [Full GC处理专题](http://note.youdao.com/noteshare?id=7f8bdbae9b6b68ce82dbca21f43a813a&sub=98FA0B68B8164BFF8972A4458406A97D)

Golang开发相关
---

- GMP调度模型

- 单核并发

- 多核并行

- 协程泄漏

- 数据竞争

数据结构及算法
---

题目均来源于 LeetCode ，参考LeetCode英文版、中文版精品题解

- [二叉树相关](http://note.youdao.com/noteshare?id=5acc43f80b3eba112bc544fbf62d0fc8&sub=84AF318114D6475988B1EBE9C4689B31)

- [链表相关](http://note.youdao.com/noteshare?id=4d33db9918200566ff5cc371df5e0613&sub=FE5287D0056749A1B11BF5D3AAF8F941)

- [前缀和](http://note.youdao.com/noteshare?id=4a36671e9d57158fa4b2f5314148708e&sub=C9534B9CD53C49A7AE63DB339F0A021B)

- [动态规划](http://note.youdao.com/noteshare?id=74a3c0d6e03ae7117d5ae37342ab3d1b&sub=50958F11F8984A22A3E8130D73B3CE62)

- [深搜(回溯)广搜](http://note.youdao.com/noteshare?id=b283e09cb0f3cb9fced81e48d7035d25&sub=39326FE2F0904471888FF3067DB9B5EF)

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

- [Redo Log、 Undo Log、 Bing Log](http://note.youdao.com/noteshare?id=3eb6289ac2f349e3c186989fc0571df4&sub=AABD211B72DA4651B16A2DE8B2B63488)

- [锁](http://note.youdao.com/noteshare?id=9c447fa17f8681a00b0d423fb2917c65&sub=DD91F3D9F47C48968E460CE073ABC981)

- [B树和B+树](http://note.youdao.com/noteshare?id=e03c2e316dfb0bcc64781fe831d1f9f9&sub=DA6968A28DFF4FE0AAE82F34C51F338C)

- [慢查询相关](http://note.youdao.com/noteshare?id=0a4a4b6560385bc5e0a46bfd540b9e27&sub=87BC4AF34A6641A190F96F77B26549AF)

- [数据是怎么插入的](http://note.youdao.com/noteshare?id=c7a9caac23183aeb52bf33bf9c7c4b5b&sub=09F0295A4F874560A5524228F524E7AF)


Redis
---

参考书本 《Redis设计与实现》

- [Redis的基本操作](http://note.youdao.com/noteshare?id=a52777330ee415d783c1d5c4f4fa99af&sub=404CD968E38D489885E2B009F73D8FA1)

- [基本数据类型的原理(SDS、List、quickList...)](http://note.youdao.com/noteshare?id=5a6978ffd508e94444e1867c8730297c&sub=4F2CCE3B0B724EDDA84230D1B5D5D4A9)

- [持久化及性能保障](http://note.youdao.com/noteshare?id=46278ef69a23b8a24a302efd77f5f14c&sub=CC8EB02E5CD041EA822A5636093FC4BD)

- [Redis为什么这么快](http://note.youdao.com/noteshare?id=872cf5559f7dbfaa169b98cb8b683b4b&sub=2F8F9A021DEE4F93B370E9901AD25979)

- [缓存穿透、雪崩、击穿](http://note.youdao.com/noteshare?id=b52f5db013f625e42d8e69de1f6cd3f3&sub=713D7413903043F9BAA2ABDE54E229E5)

- [Redis分布式锁](http://note.youdao.com/noteshare?id=5f07ec8909ac1f3db9f5518e2ad2fd92&sub=FB651C3878BA479EAA317519542B956D)

- [缓存一致性问题集合](http://note.youdao.com/noteshare?id=809ae0072f4b5fe76ee25bc594e11edc&sub=F8578BA9587947AC8A9D88EA8C82AB86)

- [淘汰策略](http://note.youdao.com/noteshare?id=bfde5b17dcaa03e6aa45d71dc81f4c84&sub=01A29709DF8E4E1DA51033C89B65C03A)

- 主从复制

- [集群相关](http://note.youdao.com/noteshare?id=751a16189885ad9ca2f9ebd5ce8dbd0f&sub=E69640F0C67E45BCB3925CE53C4C6753)

- [Redis延迟高专题](http://note.youdao.com/noteshare?id=0ab2d0e1d766609decd19dd5c796ebc7&sub=D8CC93C603164747BAB0BC24D956EA5D)

- [Redis相关问题专题](http://note.youdao.com/noteshare?id=81c72951242361c957a6ebf8a47acaf5&sub=86F995736C4E4F5BA3244C132A94B760)

设计模式
---

- [单例模式](http://note.youdao.com/noteshare?id=3f937267bc3184e2b630ade9cae4e0f6&sub=720C03EF1F244114B71CBC1515633373)

- [代理模式](http://note.youdao.com/noteshare?id=eab271e55944180f86ddcd9aa35899c5&sub=3226573455A749BD8F6F68E553596CDE)

- [原型模式](http://note.youdao.com/noteshare?id=ab8dad20d80b4eccffe6edd50655a89a&sub=4E35652F9BAD45F1A9DB142D9C591454)

- [工厂模式](http://note.youdao.com/noteshare?id=974dc1c049c3aca81b6ee42cface1d03&sub=FE07EC3AC21A4D7685E5ACE5E36FE1CC)

计算机网络
---
计算机网络推荐看wx公众号——小林Coding

- [输入URL到页面显示发送了什么](http://note.youdao.com/noteshare?id=c1070c44c08769ebc755418d5fd306df&sub=3B0F7FEB8A914EA9AE1301A08AEE5394)

- [Cookie和Session](http://note.youdao.com/noteshare?id=9106fdbaf8f8cc5df236900431bb9825&sub=87A6C0DD7DB44089843BAF71D663BD9F)

- [GET和POST的区别](http://note.youdao.com/noteshare?id=59248c82ff69f8c8dd020c78d7a6e086&sub=F1832C7907F4433E991A678032E118D5)

- [HTTP演变及HTTPS的握手过程](http://note.youdao.com/noteshare?id=cda67d2f122be5f0a1062c6f4c425353&sub=A24280C128354BC1A419E2E3D56FEF8A)

- [HTTP2优势详解](http://note.youdao.com/noteshare?id=641ff564db009944b33f91d3e64be4f6&sub=C76CF072583F451D8739F539907581AE)

- [对称加密和非对称加密](http://note.youdao.com/noteshare?id=4a33f35265e8a14f46781e4731f9044d&sub=F9570F8C683E49099A91993F62D90885)

- [TCP和UDP](http://note.youdao.com/noteshare?id=f38c2c84d14f64834955af6eff54bed0&sub=CC708637BD784363BD97C952472CA404)

- [TCP重传、滑动窗口、流量控制、拥塞控制](http://note.youdao.com/noteshare?id=793d30a109f82f9dfe13c7aea6c1e2f0&sub=9FF8FC98F5B04CA78D78556E44DAEF67)

- [TCP三次握手详解](http://note.youdao.com/noteshare?id=feb04ab447424fd26149b41f702c9fda&sub=C0E2F5E740D349A5A465D76435043E3A)

- [TCP四次挥手详解](http://note.youdao.com/noteshare?id=8ebb2e93ce54000e545b12955b579c0c&sub=3C0FF111D46843C2A3E1C064530C15C8)

- [TCP的疑难杂症(持续补充)](http://note.youdao.com/noteshare?id=4a49e822e3bdedda8fedefae2fadf085&sub=EAA3AEF769944B0CB7AE0FF90966DF45)

- [TCP传输数据的性能提升](http://note.youdao.com/noteshare?id=c160f645697336cfe0c017619328baeb&sub=D72253BCBD6846E3828BBFC9F761921F)

- [TCP面向字节流及UDP面向报文](http://note.youdao.com/noteshare?id=99d8f86bd9cc7218a9bf428cc594a058&sub=9B1CF61528764263BE2F045CF678C80B)

- [QUIC技术扫盲](http://note.youdao.com/noteshare?id=b667d02e47548e5d298883f9e19f2c33&sub=4D9564D6868F45F2ADE7F4EFD7DEE15F)

- [应用层KeepAlive和传输层KeepAlive](http://note.youdao.com/noteshare?id=720d7699067e922a12e254d46a73d38b&sub=FF1B4EB334DD4851A7D5A5E07FD44689)

- [ARP协议](http://note.youdao.com/noteshare?id=09047abe27cc49c589fd27f0764527b7&sub=F9FB9CE1CACC495993BF8B4CE214F0B4)

- [IP及数据链路](http://note.youdao.com/noteshare?id=5f5f014a26af28c358721085ed79e44e&sub=83B287C25C2540FCA2ACF28831707027)

- [网络IO的发展](http://note.youdao.com/noteshare?id=59529011eff2c35da455b440e4fa69f9&sub=972F1ACE09F744AFB8D0256FE6134F80)

- [队头阻塞专题](http://note.youdao.com/noteshare?id=7206f29992cb1dfebaf1f2f352e61aaa&sub=3354E9B97EBE44F690328A7B321A89BE)

- 直播SRT及RTMP推流协议

操作系统
---

推荐看wx公众号——小林Coding  操作系统第9版


- [内存管理](http://note.youdao.com/noteshare?id=911d274e64fdf966f941bae7a5c27ac5&sub=897C1A7020174E69A2771587C88F01B9)
  - [写时复制技术](http://note.youdao.com/noteshare?id=e9fb06a522117dbb296f381e40e6ca85&sub=F7F4FAA7A6F349ACBF744002D522982B)

- 进线程管理
  - [进程](http://note.youdao.com/noteshare?id=ca51e537d59c67553f3159287969ca9a&sub=EC94DB0D3E954BFCBAB450D6944379D3)
  - [进程间通信](http://note.youdao.com/noteshare?id=29df6e0063081c244ff3c1fff7a077e0&sub=ED3AA81B18C343DE99502C93F3C672E8)
  - [线程间通信 以Java和Golang程序为例](http://note.youdao.com/noteshare?id=0a0f0f1182c96b1746939b4930609381&sub=B9242132E3B04E97AD6C5234617AC361)
  - [线程、协程](http://note.youdao.com/noteshare?id=dd4144292a4a23bf04e693fb94bbbb83&sub=B2E19C7510B2423BA57EAF0675DDD3C9)
  - [调度算法](http://note.youdao.com/noteshare?id=30083e84a8c61e82408adb3199f97230&sub=18CC2B7BB915446C96915814B1E2C91D)
  - [死锁及死锁处理](http://note.youdao.com/noteshare?id=fbd767806bbc9e90d8f742b77834b833&sub=A6022EE7BEA54B18B866C1D81954C1A4)
  - [深入浅出 进程](http://note.youdao.com/noteshare?id=d5a24be83c744c03c1fba1a12a8b9e78&sub=BD8591965F9D4D9F8E1088EB178AC4AE)
  
- [输入输出设备管理](http://note.youdao.com/noteshare?id=813b27d7660e5a40211a023b15920002&sub=B8ECC5823A4341AABAE4D4F28523C462)

- [硬连接 软连接](http://note.youdao.com/noteshare?id=3b1e37dbb54cac6039181aaa66c8a8ae&sub=A3CCC11B823645C29DDED87D1E79C469)

- [其他](http://note.youdao.com/noteshare?id=bd3915f99705133d37408936712777c7&sub=D0FBC47B293747438A5623B782B79CE3) 

- [Reactor 和 Proactor](http://note.youdao.com/noteshare?id=33915258ed94a6896670c7a838d6531a&sub=0A30ED3A2FEB4FAD8D13B77FEF3FCF6C)


设计数据密集型应用
---
学习书本 [ddia](https://github.com/Vonng/ddia)
 - [可靠性、可伸缩性、可维护性](http://note.youdao.com/noteshare?id=165b2ca6305f13d181464065ffcb1261&sub=5780AED853DC46709F38B6D25065CEBD)
 
 - [存储与检索](http://note.youdao.com/noteshare?id=f58d203fc32b867ed190a6d7421af6a2&sub=10F68FF010F7449FB348E973F3C53643)

 - 复制与分区

 - 分布式系统的麻烦

 - 一致性与共识

 - 数据库分拆
 
领域驱动设计
---
[ddd](https://github.com/TanDawn1/Domain-Driven-Design-zh)

- 绑定模型及实现


框架与中间件
---

- [SpringIOC及AOP](http://note.youdao.com/noteshare?id=43c82776f9cfabb8d0f6d04702e21ac6&sub=854050B6269E48BD84109ABE5ECA227E)

- [SpringMVC请求处理过程](http://note.youdao.com/noteshare?id=d0c4f8d8a39482a7a113a1f37261bd1f&sub=1B2BCD3561BC46F090EF987C59001891)

- [Spring相关面试题](http://note.youdao.com/noteshare?id=10c4929b70abd54f2062a7ab4a6f7f65&sub=165596C33DD74E1C9638032AB00E1DF9)

- [SpringBoot](http://note.youdao.com/noteshare?id=9dbf7fe1fcdb3108ade024f7e6812bde&sub=163EF6A1B4D14CFA9CF93EF17DEB5986)

- [Netty](http://note.youdao.com/noteshare?id=2a96a446dbce8a4c97fb2b8aed107e35&sub=B11B5423EC4E42D9B89FE5D078FBBCDA)

- Nginx

- MQ消息队列

- Zookeeper

后端其他
---

- [一致性Hash原理](http://note.youdao.com/noteshare?id=1f6202c01ec269a8bb9ee191e99eea9d&sub=0E87A1B3D9ED49A0B739126267F1A28B)

- 内存屏障及缓存一致性协议

- [RedLock有趣的讨论](http://note.youdao.com/noteshare?id=f6a1335b3694b071c127d993776abac7&sub=2EA3D049D911473EB07D0A38113E2199)

- [电商高并发系统的架构设计](http://note.youdao.com/noteshare?id=29f17d1a3c656eeac681399291a06189&sub=8E679729126E4381BD97BF7453FCF789)

- [内容分发网络加速技术——CDN](http://note.youdao.com/noteshare?id=fd8db7958342531c0c3cfef971ab157d&sub=F9F50F510BC44567B95D457C55F7A84F)

- WebRTC 低延时音视频技术

- 从0到1实现直播弹幕系统

- WebSocket支持百万级长连接的实践


技术底蕴
---
站在巨人的肩膀上学习
随缘看了...

- Linux源码学习 2.4.31为基准
  - [源码网址](http://elixir.bootlin.com/)
  - 网络 net/ipv4

- MySQL源码学习

- Redis源码学习

- Raft源码学习

- MediaSoup源码学习
