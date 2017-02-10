# ChatScript文档整理

ChatScript（下文简称CS）是一个使用C语言开发的，基于脚本的对话引擎，其代码高效，优雅。本项目用来收集[ChatScript](https://github.com/bwilcox-1234/ChatScript)的文档，以遍开发者快速上手，文档大多是英文，也有少部分是中文。

## 说明

1. 一个讲解CS原理的PPT，深入浅出，大力推荐：[Slides](./ChatScript Training.pdf)

2. 用手手册，非常详细长达63页: [手册](./ChatScript User Manual.pdf)

3. ChatScript官网所给的文档，原路径是：[wiki](https://github.com/bwilcox-1234/ChatScript/tree/master/WIKI)；如果不存在了，或者想集中管理，在本项目的[wiki文件夹](./wiki/)中也有已下载好的备份

4. ChatScript系统函数文档，大约37页，[ChatScript System Functions Manual](./ChatScript System Functions Manual.pdf)

5. ChatScript高级用户手册：[手册](./ChatScript Advanced User Manual.pdf)

6. [ChatScript Engine and Private Code Manual](./ChatScript Engine and Private Code Manual.pdf)
<br>How the internals of the engine work and how to extend it with private code.

7. ChatScript使用JSON格式数据文档，7页: [ChatScript JSON](./ChatScript JSON.pdf)
<br>这个文档主要讲述了，以JSON格式表示的事实(Facts)，如何用ChatScript操控。
<br>更详细的一个文档，13页，见：[详细JSON](./ChatScript-Json.pdf)

8. [Chatbot Creation Options](./Chatbot Creation Options.pdf)
<br>这是一篇论文，比较了AIML和ChatScript脚本语言各自的优缺点，总结而言：


 |语言 | AIML| ChatScript|
 | :------- | :---- | :--- |
 | 优点| 简单| 增强模式匹配能力  |
 ||容易学|功能强、弹性灵活、高效|
 ||容易实现|文档优秀|
 ||存在一些预先编好的set|证实商业应用可行|
 |||无需外在服务，可离线化|
 ||||
 | 缺点|模式匹配能力弱| 难学 |
 ||耗时多，不好维护|无现成服务提供方，需自己集成其他组件|
 ||一个健壮bot需大量categories|网页端集成难|
 ||有限实施备选方案 ||

9. 一些ChatScript .top脚本示例：

 |文件|说明|
 | :------- | :---- | :--- |
 |[tutorial - v0.1.top](./examples/tutorial - v0.1.top)|订票bot，使用%issue|
 |[tutorial.top](./examples/tutorial.top)|订票bot，使用^respond|
 
10. 我们根据ChatScript提供的英文文档，整合形成了更为简洁通顺的中文文档，一方面进行知识梳理，同时便于形成体系：
<br> 入门介绍：[ChatScript 对话引擎](./ChatScript对话引擎（基础版）_v1.0.pdf)
<br> 高级特性：[ChatScript 对话引擎高级特性](./ChatScript对话引擎（高级版）.pdf)
<br>*注意：*上述两个中文文档，我们保留翻译版权，转载使用引用等，需注明出处，谢谢

11. [Writing a Chatbot For UC Berkeley's Center for: New Media ChatScript Hackathon](./Writing a Chatbot For UC Berkeley's Center for New Media ChatScript Hackathon.pdf)
<br>本文不是讲一些非常细的细节，而是之讲常用知识，从设计角度出发，让你可以快速上手开发bots。主要内容可概括为：
 
 开发bot的流程是：1. 明确bot目标，能做什么；2. 面用什么用户；3. bot属性画像；4. 由proto script到chat script code的编写；
 
12. [Bot Harry - basic bot](./Bot Harry - basic bot.pdf)
<br>本文2页内容，讲述如何对harry做一些简单修改，以便实现自己的第一个bot

13. [Winning the Loebner's](./Winning.pdf)
<br>满满的技巧，大力推荐

14. [MAKING IT REAL: LOEBNERWINNING CHATBOT DESIGN](./ARBOR.pdf)
<br>一篇2013年的论文，简单描述了ChatScript

## Version

最初整理此文档时，ChatScript所处的release版本是：

[CS 7.111](https://github.com/bwilcox-1234/ChatScript/archive/7.111.tar.gz)

自2017-02-05之后，整理与更新的文档对应的ChatScript版本是：

[CS 7.12](https://github.com/bwilcox-1234/ChatScript/archive/7.12.tar.gz)

## 联系

何云超 (yunchaohe@gmail.com)