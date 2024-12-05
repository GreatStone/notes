调研数据湖仓相关的需求，读这篇综述主要求解两个问题：1. 数据湖的最佳实践模式，2. 元信息的集成和管理模式

总结部分用一张图表达了综述内容，可以分为三个大块：
1. 架构：
	1. zone arch
	2. functional x maturity arch
2. 元信息管理：
	1. 建模：graph models/data vault model
	2. 分类：structural/functional
3. 技术
	1. Data ingestion
	2. Data storage
	3. Data procesing
	4. Data access
# 综述
数据湖是什么
- 数据湖是一个巨大的数据仓库
- 存储和管理各种原始数据（raw data）
- 包容任何格式
本文讨论不同的设计数据湖的实践方式，着眼于架构设计和元信息管理，这两点决定了一个数据湖设计是否成功

