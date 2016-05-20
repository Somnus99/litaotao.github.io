---
category: books-2016
published: false
layout: post
title: 『 读书笔记 』5月读书总结｜博文推荐
description: the more you read, the more you think, better you'll be.
---

## 写在前面

计划是每月读 5-10 本书，书籍类型大概是三个方面的：金融，技术，管理。之所以选择这三个方面，一方面是因为自己对这三个方面都很有兴趣，其次是被 linkedin 创始人 Hoffman 的 [ABZ 理论](http://techcrunch.com/2012/02/14/in-startups-and-life-you-need-plan-a-b-and-z/) 深度影响。建议大家都看看 abz 理论那篇文章，如果我有空，也会整理一些常用的这类理论模型到博客里的。

月底读书总结的形式都很简单，只是简单的一个列表和简单的书评，对觉得比较好的书会有单独的读书笔记。另外推荐大家用 excel 来做一些简单的工作管理，我现在就用 google docs 来做工作安排和读书计划，个人感觉比一些常用的神马协同软件强大太多了，简单，够用，就行了。工作中见过太多人把时间都花到使用那些协同软件上去，不得不说避重就轻了，适得其反，哈哈。

下面是一张我用 google docs 来做本月读书安排的截图，不同颜色代表不同类别的数据，清晰明了实用。

![book-reading-04.png](../images/book-reading-04.png)

本月看了 11 本书，其中第十本是一些研报的合集，就当是一本了；第十一本是 coursera 上的一门公开课 *Successful Negotiation: Essential Strategies and Skills*，也当是一本书了。其中有电子书版的都放到亲爱的[度娘云](http://pan.baidu.com/s/1boRIG5T)里了，个人觉得不错的书都是纸板的，不知道有没有电子版的，推荐好书都看纸版的。

ps: 我对好书的定义很简单：

- 给自己有所启发的
- 高质量的，专业的教程类书籍
- 后期会再度回首的书
- 看完后会打算赠送给盆友看的书
- 留着给儿子看的书 [好吧，目前我只有个宝贝侄儿，哈哈]
- 最后一条，印刷质量要好

上月读书总结：[『 读书笔记 』3月读书总结和推荐](../books-recommend-and-summarize-on-mar-2016)


## 1. 读书总结

### 1.1 [Docker 全攻略](https://www.amazon.cn/Docker%E5%85%A8%E6%94%BB%E7%95%A5-%E5%BC%A0%E6%B6%9B/dp/B01DURNAG0/ref=sr_1_1?ie=UTF8&qid=1462330582&sr=8-1&keywords=Docker+%E5%85%A8%E6%94%BB%E7%95%A5)

随着虚拟化技术的流行，最近两年 docker 也开始变得越来越火，我也看好这个趋势的发展，它的 `Build, Ship, and Run Any App, Anywhere` 的理念很吸引我，这对与初创起来来说是非常可取的一个早期方案［当然后期也可以］。于是准备最近一两个月系统的了解了解 docker 以及它的生态圈，恰逢公司刚刚新购一批书，里面有一本讲docker的书，就拿来看了。总的来说，这本书让我大失所望，通篇80%的内容都是介绍docker的命令用法，参数说明以及一些多余的口舌去了，太过于铺张浪费。通读下来应该感觉都是那种出版社编辑在 qq，微信群里找一些所谓的技术大拿写的［这还是好的，甚至有的出版社编辑直接找大学生写书了；我大三的时候还有一个叫源智天下的出版社找我写单片机的书］。真是不明白为什么有的人会写这种书，说实话，就算是七拼八凑，那性价比也是很低的。一本 500 页的书，顶多能拿个 2～3w 的稿酬，真心没必要。

书籍内容：全书 534 页，其中 28-467 页全是讲 docker 命令，而且都是官方文档

最后问了下公司的 docker 大神，他推荐直接官网 ＋ [http://dockone.io/](http://dockone.io/) 这个 docker 社区。

总结：如果你闲得蛋疼的话，来读这本书吧。

推荐指数：


### 1.2 [Advanced Analytics with Spark](https://www.amazon.cn/Spark%E9%AB%98%E7%BA%A7%E6%95%B0%E6%8D%AE%E5%88%86%E6%9E%90-%E9%87%8C%E6%89%8E/dp/B015VTKN5Q/ref=sr_1_1?ie=UTF8&qid=1462618411&sr=8-1&keywords=advanced+spark)

选好书：orelly，preface，content，author，safaribooksonline，github repo for code


总结：

推荐指数：`* * * * *`


### 1.3 [Hadoop权威指南(第3版)(修订版)](https://www.amazon.cn/Hadoop%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97-%E6%80%80%E7%89%B9/dp/B00OUFXPDA/ref=sr_1_1?s=books&ie=UTF8&qid=1463474378&sr=1-1&keywords=hadoop+%E6%9D%83%E5%A8%81%E6%8C%87%E5%8D%97)

之所以要看这本书，是因为最近一直在看一些 spark 的资料，而大多数 spark 应用都把数据存储在 hdfs 上，而且也有同事问过 hadoop 上 datanode 和 namenode 的一些问题，当时我也只能按照自己的理解来回答他。这迫使我相信，要想用好 spark，对 hadoop 以及 hadoop 的生态需要有一定的了解和掌握，这是促使我安排这本书的核心原因。

这本书讲得比较全，推荐大家看中文第三版修订版或者第四版影音版的，因为涵盖了大多成熟的 hadoop 生态里的其他开源项目，能对 hadoop 及其生态有一个比较简单的了解。

总结：第三版修订版或第四版影印版值得阅读，对了解 hadoop 的基本原理，运行流程，使用方法很有帮助，还能了解 hadoop 生态系统里的其他开源项目。

推荐指数：`* * * *`


### 1.4 [急救手册](https://www.amazon.cn/gp/product/B00B2FHTOM/ref=oh_aui_detailpage_o00_s00?ie=UTF8&psc=1)

很久之前就想看这样一本书，因为现实生活中遇到过这样一件事：在公交车上遇到一个突发癫痫的老人，当时我就离那个老人不远，但老人倒地，发抖，口吐白沫的时候我突然觉得好像周围都静止了，整个人都惊呆了，因为自己完全不知道该怎么办，好像这种事情就永远不会发生在自己身边一样。现在工作了，思想渐渐成熟，满满发现这些学校里面不会传授的知识在生活中的重要性，于是特地选了这本书来学习急救技能。

就本书来说，内容对我这种门外汗来说完全够用了，书籍本身印刷质量非常高，铜纸版印刷的，有很多详细的彩色插图介绍，很值得。

总结：虽然不想承认，但现在人们的健康情况却是越来越差了，掌握一些基础的急救技能真的很有必要，不仅是为了路人，更是为了家人。

推荐指数：`* * * * *`


### 

总结：

推荐指数：`* * * *`


### 

总结：

推荐指数：`* * * *`


### 

总结：

推荐指数：`* * * *`



## 2. 博文推荐 

- [对话：一个工程师在蘑菇街4年的架构感悟](http://mp.weixin.qq.com/s?__biz=MzAwMDU1MTE1OQ==&mid=2653547068&idx=1&sn=910e345a35383e9d440d8a41695ccb10&scene=1&srcid=0504Wzmtyh8LNqrTo2XrP1my&from=groupmessage&isappinstalled=0#wechat_redirect)
- [如果有人问你数据库的原理，叫他看这篇文章](http://blog.jobbole.com/100349/)

>>
这篇文章是真的不错。

- [日请求量过亿，谈陌陌的Feed服务优化之路](http://mp.weixin.qq.com/s?__biz=MzA5Nzc4OTA1Mw==&mid=2659597071&idx=1&sn=cd8df9f8c52dfbfb54e65adbe19fae27&scene=0#wechat_redirect)
- [支付宝架构师：从工程师到架构师的成长之路](http://www.scalerstalk.com/838-architect)
- [向Spark开炮：1.6版本问题总结与趟坑](http://geek.csdn.net/news/detail/70162)
- [你应该知道的HTTP基础知识](http://www.jianshu.com/p/e544b7a76dac)
- [HTTP CODE 常用对照表](http://tool.oschina.net/commons?type=5)

- [博客推荐系统——物料准备 (第一部分)](http://www.infoq.com/cn/articles/blog-recommendation-system-part01)
- [博客推荐系统: 基于内容相似性的推荐 ( 第二部分)](http://www.infoq.com/cn/articles/blog-recommendation-system-part02)

>>
这两篇文章写得简单易懂，可以帮助新手了解一个简单的推荐系统的结构。


- [小公司的前端应该怎么做？](http://www.cnblogs.com/yexiaochai/p/5311712.html)
- [如何更有效的处理数据检索缓存](https://mp.weixin.qq.com/s?__biz=MzIzNDE0NjMzOQ==&mid=2653923761&idx=1&sn=6af678b749b02aa19b947dcb1c58593a&scene=0&key=b28b03434249256ba48b934c509118b6073fefc76610faa0c26ecce439f484c51d19dcfc83c4a3a7378de329a6739ae2&ascene=0&uin=MTAzNTc2NzM4Mg%3D%3D&devicetype=iMac+MacBookAir6%2C2+OSX+OSX+10.10.5+build(14F1713)&version=11020201&pass_ticket=fHxj4QiBJX6%2FngUiCgKPGZz8WHBOrnfOUJgjiQhkTd7CpYCzpY3KoVuHVZxrf88X)

- [独立开发者必知的一些总结](http://godcoder.me/2016/04/25/%E8%B5%9A%E9%92%B1%E5%BF%85%E7%9C%8B%EF%BC%9A%E7%8B%AC%E7%AB%8B%E5%BC%80%E5%8F%91%E8%80%85%E5%BF%85%E7%9F%A5%E7%9A%84%E4%B8%80%E4%BA%9B%E6%80%BB%E7%BB%93/)
- [面试官如何面试程序员](http://blog.jobbole.com/100702/)
- [Spark性能优化指南——基础篇](http://tech.meituan.com/spark-tuning-basic.html)
- [Spark性能优化指南——高级篇](http://tech.meituan.com/spark-tuning-pro.html)
- [如何在72小时之内快速搞懂一个陌生行业？](https://mp.weixin.qq.com/s?__biz=MjAzNzMzNTkyMQ==&mid=2653749258&idx=1&sn=82d5929393932fbf1cb97d9acbdd41b5&scene=1&srcid=05188fOCSKGwfCzJfI73ssBE&key=8d8120cb97983fad7f2968069d314547f9679b9bbb4497c084f9246b67b6f6f81d90b0cdb2e55a81153d93e2d75b7a89&ascene=0&uin=MTAzNTc2NzM4Mg%3D%3D&devicetype=iMac+MacBookAir6%2C2+OSX+OSX+10.10.5+build(14F1713)&version=11020201&pass_ticket=CSAsHNzivWgVTZBKGOYlRae9cr0HEYP6s8AVn13yrEYAGDoNhBI7SNSv3teBBk4L)
- [数据化解析Term Sheet十大核心条款，关于融资的干货都在这儿了](https://mp.weixin.qq.com/s?__biz=MjAzNzMzNTkyMQ==&mid=2653749289&idx=4&sn=a3e57e4400cde387f330e7ea8429d30a&scene=1&srcid=0518elOD5oMp6TNMP4Z9nPxD&key=8d8120cb97983fade74366a3f02b2ceb18dd53e99524441327fe1192e109cf6d1d532b144cd29ce82f208e9e65a7bcc0&ascene=0&uin=MTAzNTc2NzM4Mg%3D%3D&devicetype=iMac+MacBookAir6%2C2+OSX+OSX+10.10.5+build(14F1713)&version=11020201&pass_ticket=CSAsHNzivWgVTZBKGOYlRae9cr0HEYP6s8AVn13yrEYAGDoNhBI7SNSv3teBBk4L)
- [优秀配色方案的探索过程](http://colachan.com/post/3502)
- [知乎上的48条神回复，针针见血，看完整个人都通透多了](https://mp.weixin.qq.com/s?__biz=MzA4NjAzNDg4NA==&mid=2656366443&idx=3&sn=19091f8ca1bd18a1cba55fc88402a7fd&scene=1&srcid=0515hXptbhIi1JhXUGtyqI5r&key=8d8120cb97983fad3adcf075795d583f5889e72bfd0a1874e4d968c4478a422244e16d191be3b8c1c5010484537b5e4f&ascene=0&uin=MTAzNTc2NzM4Mg%3D%3D&devicetype=iMac+MacBookAir6%2C2+OSX+OSX+10.10.5+build(14F1713)&version=11020201&pass_ticket=CSAsHNzivWgVTZBKGOYlRae9cr0HEYP6s8AVn13yrEYAGDoNhBI7SNSv3teBBk4L)

> 哈哈，轻松一下

- [几种一致性模型的分析](http://mp.weixin.qq.com/s?__biz=MzAwMjgwMTEzNw==&mid=2652227239&idx=1&sn=fdc9cd6fad120594426a9fe4b80b438c&scene=2&srcid=0514jA1Y6iz4kUl721PEWR6k&from=timeline&isappinstalled=0#wechat_redirect)

- []()
- []()



## 3. 读书总结系列

- [『 读书笔记 』3月读书总结和推荐](../books-recommend-and-summarize-on-mar-2016)
- [『 读书笔记 』4月读书总结｜博文推荐](../books-recommend-and-summarize-on-apr-2016)
- [『 读书笔记 』5月读书总结｜博文推荐](../books-recommend-and-summarize-on-May-2016)