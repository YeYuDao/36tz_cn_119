# 36tz_cn_119
Spark + ElasticSearch 构建电商用户标签系统
Spark + ElasticSearch 构建电商用户标签系统
👇👇👇👇👇👇👇👇点击下载地址👇👇👇👇👇👇👇
[![download](https://51xueit.vip/muke_img/5fce0fd30984257405400304.jpg "下载地址")](http://www.36tz.cn "下载地址")
### 第1章 课程介绍与学习指南 

#### 本章中将向大家介绍课程能学到什么、解决什么实际问题、项目成果展示，课程整体安排以及如何学习更高效。
1-1 课程导学 (11:46)

1-2 如何更好的使用慕课平台


### 第2章 开发环境与技术栈介绍 

#### 本章主要针对课程中应用的开发环境以及技术栈进行相关介绍。本课中会使用，虚拟化技术： virtualbox + vagrant，容器化技术：docker + docker-compose。技术栈涉及spark，Hadoop，hive等。
2-1 开发环境---virtualbox介绍 (02:36)

2-2 开发环境---docker介绍 (06:48)

2-3 开发环境---虚拟机与docker容器技术的对比 (04:16)

2-4 开发环境---vagrant介绍 (04:09)

2-5 itag项目的技术栈介绍 (02:49)

2-6 【讨论题】docker容器技术会彻底取代虚拟机吗？


### 第3章 大数据环境搭建 

#### 本章主要讲解开发环境的搭建，虚拟机与docker的安装。针对没有docker基础的同学，我们也会涵盖部分基础知识，从而实现轻松上手。针对容器化的开发环境，我们会详细演示，如何去解决访问和数据持久化。本次环境搭建会配合详细操作文档，方便同学们本地复现。...
3-1 作业讲解 (03:51)

3-2 virtualbox , vagrant 你安装好了吗？

3-3 virtualbox安装ubuntu (06:08)

3-4 ubuntu系统的启动与验证 (04:52)

3-5 vagrant创建虚拟机环境 (08:44)

3-6 用vagrantfile进行详细设置 (11:26)

3-7 ubuntu安装docker、 docker-compose (06:29)

3-8 Docker安装以及使用的小贴士

3-9 老师，为什么我的docker-compose启动不了呢？

3-10 zsh shell辅助软件安装与配置 (11:26)

3-11 docker 和 docker-compose 小试牛刀 (15:30)

3-12 大数据环境安装 (10:46)

3-13 大数据环境验证与测试 (14:16)

3-14 docker-compose.yml讲解 (09:33)

3-15 本章作业 (03:56)

3-16 【问答补充】事先用docker建立es_network网络 (05:38)

3-17 【技巧补充】docker pull 速度太慢？配个镜像加速吧！

3-18 【讨论题】真程序员，用Linux命令行为何如此受追捧？


### 第4章 itag用户标签系统介绍

#### 相较于现有业务的局限性，这章中我们会来共同来探讨标签系统的设计理念。通过UI初步讲解标签的数据含义，结合mysql数据库表结构，去理解业务和标签的实现算法，更为详细的标签算法及ETL清洗逻辑在后续章节会做详细讲解。...
4-1 前章作业重难点回顾及问题答疑 (03:40)

4-2 现有业务介绍 (04:24)

4-3 花三分钟聊一下用户画像 (02:46)

4-4 主要数据库及表结构介绍 (11:29)

4-5 itag系统介绍、用它来干什么？ (05:18)

4-6 【讨论题】所谓的大数据用户画像，真的准吗？

4-7 本章作业 (03:16)


### 第5章 数据同步

#### 针对数据同步技术，本章中会介绍一些常用的数据同步中间件，以及实际项目中数据库同步至大数据集群的架构迭代（画图）。随后会演示利用sqoop导入数据到hive中。并学习如何对hive进行实际操作。
5-1 作业答疑、本章内容大纲介绍 (02:15)

5-2 sqoop简单介绍 (03:13)

5-3 数据同步架构的1.0版本 (03:58)

5-4 数据同步架构2.0及两个拓展问题的解决 (14:27)

5-5 Hive简介及架构 (13:36)

5-6 Hive实操（一）及docker 文件拷贝 (14:27)

5-7 Hive实操（二）及面试题讲解 (10:43)

5-8 Hive外部表介绍 (09:21)

5-9 sqoop 安装与配置 (12:55)

5-10 sqoop 安装及mysql 数据导入脚本

5-11 hiver-server中安装sqoop，替换apt源

5-12 sqoop 将mysql数据导入到hive (14:12)

5-13 【讨论题】数据同步框架需要解决那些问题？


### 第6章 数据清洗

#### 本章中主要讲解大数据项目中数据与业务的关系，数据血缘，数据平台，数仓等相关概念。讲解如何利用spark进行数据操作。分别从spark java，spark scala以及spark sql 三种不同实现方式进行代码演示与对比。
6-1 数据平台是什么？包含哪些节点 (10:14)

6-2 数据血缘有什么用？如何保证？ (04:05)

6-3 数据分层的原因、规划以及真实项目经验分享 (13:53)

6-4 准备测试数据 (06:27)

6-5 Spark Java代码准备及docker网络打通 (16:05)

6-6 我的笔记本如何访问虚拟机中的docker网络？

6-7 Spark 清洗任务的JAVA实现 (13:48)

6-8 准备scala开发环境 (07:14)

6-9 Spark 清洗任务的Scala实现 (17:07)

6-10 老师，我的代码本地运行报错，winutils.exe 找不到

6-11 Spark SQL 处理ETL任务及本章作业 (19:00)

6-12 【讨论题】你真的了解ETL吗？


### 第7章 指标算法及标签ETL

#### 本章中将根据产品文档，利用spark sql + spark scala 的方式实现标签ETL。会讲述ES mapping 的设计，演示如何利用spark操作ES，并最终对全流程数据做验证与复盘。
7-1 内容介绍及虚拟环境的管理 (12:33)

7-2 指标算法说明及环境准备 (04:59)

7-3 数据大盘算法指标

7-4 会员性别指标算法及ETL结果的ORM操作 (12:39)

7-5 注册渠道、是否关注指标实现及IF函数的用法 (17:35)

7-6 用户热度指标实现及crossjoin的一些思考 (20:13)

7-7 环比指标的实现 (20:06)

7-8 提醒类指标实现 (16:49)

7-9 折现图指标实现、JOIN实现、GMV指标算法（上） (16:05)

7-10 折现图指标实现、JOIN实现、GMV指标算法（下） (15:08)

7-11 漏斗指标实现思路及指标算法的测试验证 (20:27)

7-12 ES环境创建及Spark操作ES演示（上） (13:10)

7-13 ES环境创建及Spark操作ES演示（下） (15:15)

7-14 ES mapping 设计思路及JavaBean实现 (09:10)

7-15 ES 操作及命令

7-16 标签ETL代码实现 (24:23)

7-17 ES数据查询及ETL结果验证 (08:01)

7-18 标签清洗算法


### 第8章 itag UI

#### 本章中将介绍如何应用springboot + vue 实现项目的前端UI。用户选择特定标签后，ES背后的查询逻辑。对于查询的结果，标签清洗结果，数据库原始结果做一个验证。并最终将UI项目通过docker容器的方式部署起来。
8-1 本章介绍 (04:22)

8-2 springboot及项目结构介绍 (05:44)

8-3 DSL查询语句演练 (22:46)

8-4 标签页面前端技术介绍及数据结构推导 (05:10)

8-5 前端代码实现思路及演示 (20:12)

8-6 后端DSL代码拼接及文件下载实现（上） (17:33)

8-7 后端DSL代码拼接及文件下载实现（下） (17:37)

8-8 DSL语句验证和标签管理功能的思路 (08:18)

8-9 springboot 多环境配置项指定及ETL结果存储的思路 (14:16)

8-10 springboot项目的Docker 启动方式 (10:58)


### 第9章 课程总结

#### 本章会进行课程回顾与总结，再次圈重点，敲黑板。并对后续的一个学习线路做规划。
9-1 docker补充及数仓topic分享 (11:02)

9-2 订单宽表及hive视图的作用 (10:26)

9-3 spark 执行过程分析-logical plan (19:50)

9-4 利用logicalplan 采集元数据信息 (10:11)

9-5 简短的课程总结 (04:10)


[下载地址](http://www.36tz.cn "下载地址")
