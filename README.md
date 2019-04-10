# Spring MVC 4.2.4.RELEASE 中文文档 [![][Badges: Travis CI]][Links: Travis CI] [![][Badges: Github Issues Open]][Links: Github Issues Open] [![][Badges: Github Issues Closed]][Links: Github Issues Closed]

![Spring Logo](./spring-logo.png)

本项目翻译的是[Spring MVC官方4.2.4.RELEASE版本的文档][Origin documentation]，包含原文档第21章Spring MVC部分的全部内容。译文尽力于准确传达原意，其次兼顾译文的流畅自然。至于风格和质感，则仍在努力。希望它能为读者带来查阅、学习的价值，自己时不时翻之，仍有收获。

目前多数章节的翻译已完成，剩余部分章节仍在进行。文档仍在维护状态，主要还有译文细化、术语定义、翻译规范、内容、主页修缮、自动化部署等工作可做，[issues这里][Issues link]有一些有意思的idea。翻译过程中遇到值得探讨的翻译问题、取舍及最终解决方案，读者可见[翻译注记](NOTES.md)。

本翻译初始只是自我学习需要，逐渐完善后才有坚持完成的执念。陈丹青在《木心谈木心》的后记中，讲到他犹豫于出版木心先生这本私房话的心境。为本译文做推广、宣传伊始，我也开始面对我的读者，读之，感觉真挚感动。不敢自比木心，我在我的风中等消息。

——2016年6月28 交房租日，8月28日 完成自动化部署后补稿

## 中文文档地址

* 主站：[https://spring-mvc.linesh.tw/](https://spring-mvc.linesh.tw/)
* [国外Gitbook原站](https://linesh.gitbooks.io/spring-mvc-documentation-linesh-translation/content/)

## 原文地址

[Spring MVC 4.2.4.RELEASE Documentation][Origin documentation]

## 其他相关翻译项目

为了对目前Spring MVC部分文档翻译现状有个大致的了解，可以“Spring MVC 中文 文档 翻译”作为关键词，浏览其在google和baidu上前6页的搜索结果。其中以下项目值得留意，前两个均或完全或部分地翻译了Spring MVC部的内容，可供参考；后面三个项目未涉及Spring MVC部分的翻译。

| 项目 | 作者 | 项目Github | 描述 |
| :---: | :---: | :---: | --- |
| [Spring框架参考文档](http://spring.cndocs.ml) | [一个团队](http://blog.csdn.net/isea533/article/details/50450289) | [Github](http://git.oschina.net/free/spring-framework-reference) | 该项目规模较大、参与人数较多。翻译内容是Spring 4.1.3.RELEASE版本全部文档，其中MVC部分的文档也翻译了一大半。其项目主页保留了与原生Spring文档较一致的样式，很不错 |
| [Spring Framework 2.5翻译计划](http://shouce.jb51.net/spring/) | [满江红机构](http://javasalatu.iteye.com/blog/1212618) | - | 感谢[dsliu]()在gitbook上给我提供此版译本链接。译本是整个MVC 2.5.2版的全部文档，其中MVC的部分同样齐全 |
| [Spring Framework 4.x参考文档](https://waylau.gitbooks.io/spring-framework-4-reference/content/) | [waylau](https://github.com/waylau) | [Github](https://github.com/waylau/spring-framework-4-reference) | 翻译了Spring文档的简介、新特性和容器IOC部分 |
| [Spring Framework 4.x中文翻译](https://sunrh.gitbooks.io/spring4-reference-chinese/content/) | [sunrh](https://github.com/sunrh) | [Github](https://github.com/sunrh/spring-reference-chinese) | 翻译了Spring文档的简介、新特性和容器IOC部分 |
| [Spring 中文文档3.1](https://wizardforcel.gitbooks.io/spring-doc-3x/content/) | [wizardforcel](https://github.com/wizardforcel) | - | 主页已标记废弃的项目。楼主BIO是专注单身二十年，言语间竟有一种大学宿友~~不是说我的宿友~~的即视感 |

## 友情链接

这个译本我在国内的多个站点均发表过一篇相同的推广文章，如OSC/CSDN/Iteye/博客园/掘金/v2ex/segmentfault/Githuber等。除了交付的译文本身外，还聊~~瞎扯~~了一些其他的东西。同时，关于这个翻译文档的创始、管理及自动化部署等方面，我也已将其总结成为文章。此二篇文章是对这个项目的完整记录，均发布在我的博客上，有兴趣的读者可以前往阅读。后来我又做了一些主页样式上的迁移、自动化了一些构建前文档预处理的工作，还有一些代码的重构。这部分未做记录，但代码和部署构架方面我十分满意，其精华在[`package.json`](https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation/blob/master/package.json)和[构建脚本](https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation/tree/master/build)中。

* [Spring MVC官方文档翻译稿发布](http://blog.linesh.tw/#/posts/2016-06-23-spring-mvc-documentation-reference)
* [我是如何进行Spring MVC文档翻译项目的环境搭建、项目管理及自动化构建工作的](http://blog.linesh.tw/#/posts/2016-06-26-auto-deploy-translation-to-production-using-jenkins-and-qiniu)

## 联系方式

阅读过程中的任何想法、建议、吐槽、强迫症~~不给译者狂点100个赞就浑身不舒服~~、觉得赞、觉得不赞，无论关于翻译、技术、样式等，对我来说很有意义~~啊我这文风竟有一种安妮宝贝般的性冷淡感~~！你可以通过以下的方式联系作者我：

* 来Github点赞 ~~被消费一个~~ [![][Badges: Github Stars]][Links: Github Stars]
* 在Gitbook讨论里 [给我留言](https://www.gitbook.com/book/linesh/spring-mvc-documentation-linesh-translation/discussions)
* 给这个项目提 [issue][Badges: Github Issues Open]
* 给这个项目提 [pull request](https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation/pulls)
* **邮箱**：linesh.simpcity@gmail.com

## License

MIT License

## 贡献者 Contributor

感谢那些让这个项目变得更好的人们。

![](https://avatars0.githubusercontent.com/u/4997466?v=3&s=20)[ 吕立青](https://github.com/JimmyLv)
![](https://avatars0.githubusercontent.com/u/2171071?v=3&s=20)[ Sun](https://github.com/yaming116)
![](https://avatars0.githubusercontent.com/u/7877752?v=3&s=20)[ SongWang](https://github.com/aCoder2013)
![](https://avatars3.githubusercontent.com/u/1506425?v=3&s=20)[ 易枭寒](https://github.com/Yixiaohan)
![](https://avatars1.githubusercontent.com/u/5453359?v=3&s=20)[ xcatliu](https://github.com/xcatliu)
![](https://avatars3.githubusercontent.com/u/8402502?v=3&s=20)[ HeartUnchange](https://github.com/HeartUnchange)
![](https://avatars3.githubusercontent.com/u/15180122?v=3&s=20)[ HeartUnchange](https://github.com/houbaron)



[Issues link]: https://github.com/linesh-simplicity/gitbook-translation-spring-mvc-documentation/issues
[Origin documentation]: http://docs.spring.io/spring-framework/docs/4.2.4.RELEASE/spring-framework-reference/html/mvc.html
[Badges: Travis CI]: https://img.shields.io/travis/linesh-simplicity/translation-spring-mvc-4-documentation.svg?maxAge=2592000
[Links: Travis CI]: https://travis-ci.org/linesh-simplicity/translation-spring-mvc-4-documentation
[Badges: Github Issues Open]: https://img.shields.io/github/issues/linesh-simplicity/translation-spring-mvc-4-documentation.svg?maxAge=2592000
[Links: Github Issues Open]: https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation/issues#boards?notFullScreen=false&repos=50039903&showClosed=false
[Badges: Github Issues Closed]: https://img.shields.io/github/issues-closed/linesh-simplicity/translation-spring-mvc-4-documentation.svg?maxAge=2592000
[Links: Github Issues Closed]: https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation/issues?q=is%3Aissue+is%3Aclosed
[Badges: Github Stars]: https://img.shields.io/github/stars/linesh-simplicity/translation-spring-mvc-4-documentation.svg?style=social&label=Star&maxAge=2592000
[Links: Github Stars]: https://github.com/linesh-simplicity/translation-spring-mvc-4-documentation
