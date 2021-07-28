目录
=================

* [DDD书籍推荐](#ddd书籍推荐)
* [DDD课程](#ddd课程)
* [DDD社区](#ddd社区)
* [DDD实战相关](#ddd实战相关)
   * [实践项目](#实践项目)
   * [开发工具](#开发工具)
      * [仓储快照工具](#仓储快照工具)
      * [JavaBean映射工具](#javabean映射工具)
* [优秀DDD博客](#优秀ddd博客)
   * [DDD原理相关](#ddd原理相关)
   * [事件风暴实战](#事件风暴实战)
   * [DDD项目实战](#ddd项目实战)
   * [常见DDD概念解释](#常见ddd概念解释)
* [FAQ](#faq)

# DDD书籍推荐

[《领域驱动设计 - 软件核心复杂性应对之道》](https://book.douban.com/subject/26819666/) — Eric Evans

[《实现领域驱动设计》](https://book.douban.com/subject/25844633/) — Vaughn Vernon，这本书又被称作IDDD

[《领域驱动设计精粹》](https://book.douban.com/subject/30333944/) — Vaughn Vernon

*这本书推荐新手先学习，很薄，整体概念都有，可以理解成是IDDD这本书的的简化版*

# DDD课程

极客时间[《DDD实战课》](https://time.geekbang.org/column/intro/238?code=Dq5EPat2lNV4uAWZZZXDh1XwkFhfbSyCQCJd4UDnlfQ%3D) — 欧创新

*入门的时候可以看看*

# DDD社区

* 官方DDD社区（看起来已经很久不维护了）：https://dddcommunity.org/
* 领域驱动设计峰会（有视频回放）：http://www.ddd-china.com/
  * [2017年在线视频](https://www.itdks.com/Home/Act/apply?mUid=3049982&id=1790)、PPT：链接:https://pan.baidu.com/s/1tD-SwWXcwQcUOMRHEyB-NA  密码:8nhk
  * [2018年在线视频](https://www.itdks.com/index.php/Act/apply_upgrade/id/2638/mUid/0/tpl/tpltwo.html#dingbu)、PPT：链接:https://pan.baidu.com/s/154fEwF1NK1AiMAO6qq_I7g  密码:sqmi
  * [2019年在线视频](https://www.itdks.com/Act/apply?id=3188&from=search)、PPT：链接:https://pan.baidu.com/s/19fx09707_yw02Cs-pkuA5A  密码:qc88

*宝藏网站，全部都是聊DDD的，相关PPT和视频在网站里都有*

# DDD实战相关

## 实践项目

* [ddd-cargo](https://github.com/citerus/dddsample-core)

《领域驱动设计 - 软件核心复杂性应对之道》书里对应的航运的例子

* [ddd-saasovation](https://github.com/VaughnVernon/IDDD_Samples)

《实现领域驱动设计》书里协同办公软件的例子

* [leave-sample](https://github.com/ouchuangxin/leave-sample)

极客时间《DDD实战课》里的一个基于DDD分析设计的在线请假考勤项目

## 开发工具

### 仓储快照工具

* [aggregate-persistence](https://github.com/meixuesong/aggregate-persistence) ：DDD仓储快照工具，方便进行仓储按需更新

### JavaBean映射工具

* [MapStruct](https://github.com/mapstruct/mapstruct)：数据映射工具，方便DO（Data Object），Domain Object，DTO（Data Transfer Object）之间的转换

# 优秀DDD博客

## DDD原理相关

* 殷浩谈DDD系列（这系列强烈推荐，整体思路很清晰，实操性比较强）
  * [殷浩详解DDD系列 第一讲 - Domain Primitive](https://mp.weixin.qq.com/s/kpXklmidsidZEiHNw57QAQ)
  * [殷浩详解DDD系列 第二讲 - 应用架构](https://mp.weixin.qq.com/s/MU1rqpQ1aA1p7OtXqVVwxQ)
  * [殷浩详解DDD系列 第三讲 - Repository模式](https://mp.weixin.qq.com/s/1bcymUcjCkOdvVygunShmw)
  * [殷浩详解DDD系列 第四讲 - 领域层设计规范](https://mp.weixin.qq.com/s/w1zqhWGuDPsCayiOgfxk6w)
  * [殷浩详解DDD系列 第五讲 - 聊聊如何避免写流水账代码](https://mp.weixin.qq.com/s/1rdnkROdcNw5ro4ct99SqQ)

## 事件风暴实战

* [记一次Event Storming实战经历](https://www.jianshu.com/p/ba85d2a9a9d8)

## DDD项目实战

* [如何一步一步用DDD设计一个电商网站](https://www.cnblogs.com/Zachary-Fan/p/5991674.html)

## 常见DDD概念解释

* 领域和限界上下文的区别？
  * [当Subdomain遇见Bounded Context](https://insights.thoughtworks.cn/subdomain-and-bounded-context/)

# FAQ

本人目前实践DDD也有1年多实践了，也看了很多DDD相关的代码和表现形式，大家的理解都有一些偏差，之后准备出点博客讲讲自己的理解。

读者如果有相关概念或者实施的疑问欢迎提Issue，大家一起探讨

