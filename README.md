# 漠雪数据库分享

## 个人简介

于巍（花名漠雪）13年数据库内核开发和架构设计经验，从无到有参与阿里云PolarDB、华为GaussDB等多款数据库系列产品的内核架构设计和开发，作为数据库工具、安全首席架构，从无到有主导多款数据库运维工具（性能、故障、IDE、备份、安全）架构设计，多年美国、以色列等海外研发经验。目前主要负责横向拉通阿里云数据库各产品通用技术和架构演进，标准化，开源技术等工作。


## 一、PostgreSQL 内核解读系列课程

面向DBA、高校学生、内核爱好者，介绍PG内核架构、各模块基本原理、用法、代码实现。希望通过课程学习，让没有内核经验的同学和DBA，也可以进行简单的特性开发，更深入理解PG配置和运行原理。本课程包含15个章节，系统化介绍PG架构、SQL引擎、执行引擎、存储引擎、并发控制、HA、分布式等核心技术原理和代码实现。

1、PG数据库内核解读 - 第一节 系统概述 
[视频链接](https://www.bilibili.com/video/BV1gV4y147D7?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) 
[演讲材料](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-01/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-1.%E7%B3%BB%E7%BB%9F%E6%A6%82%E8%BF%B0.pdf) 
[相关命令](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-01/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-1.%E7%B3%BB%E7%BB%9F%E6%A6%82%E8%BF%B0%E7%9B%B8%E5%85%B3%E5%91%BD%E4%BB%A4.txt)

2、PG数据库内核解读 - 第二节 体系架构 [视频链接](https://www.bilibili.com/video/BV1VV4y1s7i7?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-02/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-2.%E4%BD%93%E7%B3%BB%E6%9E%B6%E6%9E%84.pdf) [相关命令](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-02/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-2.%E4%BD%93%E7%B3%BB%E6%9E%B6%E6%9E%84%E7%9B%B8%E5%85%B3%E5%91%BD%E4%BB%A4.txt)

3、PG数据库内核解读 - 第三节 存储管理1 [视频链接](https://www.bilibili.com/video/BV12B4y167Wa?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-03/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-3.%E5%AD%98%E5%82%A8%E7%AE%A1%E7%90%861.pdf)

4、PG数据库内核解读 - 第四节 存储管理2 [视频链接](https://www.bilibili.com/video/BV11T411w788?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-04/PG%E6%95%B0%E6%8D%AE%E5%BA%93%E5%86%85%E6%A0%B8%E8%A7%A3%E8%AF%BB-4.%E5%AD%98%E5%82%A8%E7%AE%A1%E7%90%862.pdf)

5、PG数据库内核解读 - 第五节 索引1 [视频链接](https://www.bilibili.com/video/BV1hB4y1B7xh?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-05/5.%E7%B4%A2%E5%BC%951.pdf) [相关命令](https://github.com/moxuedb/blog/blob/main/PostgresKernel/Chapter-05/%E7%AC%AC5%E8%8A%82%E7%B4%A2%E5%BC%951%E7%9B%B8%E5%85%B3%E5%91%BD%E4%BB%A4.txt)


## 二、数据库架构、技术趋势、运维解读

数据库架构、技术趋势、运维、性能、安全等分享

1、数据库在云原生时代的架构演进@CSDN在线峰会—新数据库时代 [视频链接](https://www.bilibili.com/video/BV1qB4y1B75W?spm_id_from=333.999.0.0) [演讲材料](https://github.com/moxuedb/blog/blob/main/DatabaseArchitect/%E6%95%B0%E6%8D%AE%E5%BA%93%E5%9C%A8%E4%BA%91%E5%8E%9F%E7%94%9F%E6%97%B6%E4%BB%A3%E7%9A%84%E6%9E%B6%E6%9E%84%E6%BC%94%E8%BF%9Bv2-CSDN%E7%BA%BF%E4%B8%8A%E5%B3%B0%E4%BC%9A.pdf)

2、阿里云数据库性能测试及优化实践@信通院性能工具发布会 [视频链接](https://www.bilibili.com/video/BV1Ed4y1o7SE?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/DatabaseArchitect/%E9%98%BF%E9%87%8C%E4%BA%91%E6%95%B0%E6%8D%AE%E5%BA%93%E6%80%A7%E8%83%BD%E6%B5%8B%E8%AF%95%E5%8F%8A%E4%BC%98%E5%8C%96%E5%AE%9E%E8%B7%B5-%E4%BF%A1%E9%80%9A%E9%99%A2%E6%80%A7%E8%83%BD%E5%B7%A5%E5%85%B7%E5%8F%91%E5%B8%83%E4%BC%9A.pdf)

3、加密技术及阿里云数据库加密实践@信通院数安Talk  [视频链接](https://www.bilibili.com/video/BV1zG4y1a7Ca?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/DatabaseArchitect/%E6%95%B0%E6%8D%AE%E5%BA%93%E5%8A%A0%E5%AF%86%E6%8A%80%E6%9C%AF%E5%8F%8A%E9%98%BF%E9%87%8C%E4%BA%91%E6%95%B0%E6%8D%AE%E5%BA%93%E5%AE%9E%E8%B7%B5-%E4%BF%A1%E9%80%9A%E9%99%A2%E6%95%B0%E5%AE%89Talk.pdf)

4、数据库架构概述和技术演进趋势@专利代理师培训 [视频链接](https://www.bilibili.com/video/BV1zG4y1a7Ca?spm_id_from=333.999.0.0&vd_source=70bd93807a27926fda1db56ec32ef895) [演讲材料](https://github.com/moxuedb/blog/blob/main/DatabaseArchitect/%E6%95%B0%E6%8D%AE%E5%BA%93%E6%9E%B6%E6%9E%84%E6%A6%82%E8%BF%B0%E5%92%8C%E6%8A%80%E6%9C%AF%E6%BC%94%E8%BF%9B%E8%B6%8B%E5%8A%BF-%E4%B8%93%E5%88%A9%E4%BB%A3%E7%90%86%E5%B8%88%E5%9F%B9%E8%AE%AD.pdf)


## 三、国际主流数据库架构解读

国际主流OLTP、OLAP、NOSQL数据库架构、原理分享。待更新，[视频链接](https://space.bilibili.com/471917871)


## 四、程序员的海外经历和趣闻

视频分享我在2015~2018年外派美国、以色列期间的趣闻轶事，展示和讲解拍摄的大量图片、视频及个人感受。待更新，[视频链接](https://space.bilibili.com/471917871)

1、主要涉及地区: 美国（旧金山、圣何塞、洛杉矶、拉斯维加斯、圣地亚哥、芝加哥、萨克拉门托等）、以色列、加拿大、约旦、土耳其、印度等

2、主要涉及经历: 人文、地理、旅游、硅谷公司（Oracle、Google、Apple、AWS、IBM、Linkedin、Twitter等）、Startup公司、硅谷码工、高校（斯坦福、Beckley、UCLA、UIUC、芝加哥大学、以色列希伯来大学）、博物馆（洛杉矶盖蒂博物馆、电脑博物馆、火车博物馆、斯坦福博物馆、以色列艺术博物馆等）、美国以色列各城市租房和买房价格及流程、华人、Meetup（PG社区、教会、排球、Hiking、汽车、天文）、美食、美国以色列各种节日等。



加入 PolarDB 技术推广组钉钉群:
![polardb_group](https://github.com/moxuedb/blog/blob/main/polardb_group.png)

微信加好友：
![漠雪的微信](https://github.com/moxuedb/blog/blob/main/moxue_wechat.png) 

