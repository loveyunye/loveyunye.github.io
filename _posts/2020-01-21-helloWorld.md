---
layout:     post   				    # 使用的布局（不需要改）
title:      redis				# 标题 
subtitle:   no-sql #副标题
date:       2020-01-21 				# 时间
author:     卡不通 						# 作者
header-img: img/post-bg-2015.jpg 	#这篇文章标题背景图片
catalog: true 						# 是否归档
tags:								#标签
    - redis
---

#### redis

##### 简介
Redis 是完全开源免费的，遵守BSD协议，是一个高性能的key-value数据库。

Redis 与其他 key - value 缓存产品有以下三个特点：

1. Redis支持数据的持久化，可以将内存中的数据保存在磁盘中，重启的时候可以再次加载进行使用。
2. Redis不仅仅支持简单的key-value类型的数据，同时还提供list，set，zset，hash等数据结构的存储。
3. Redis支持数据的备份，即master-slave模式的数据备份。

##### 安装
[博客](https://www.cnblogs.com/wdliu/p/9360286.html)
安装稳定版本

##### 使用

启动 /etc/init.d/redis start
停止 /etc/init.d/redis stop
查看配置项 vi /etc/redis/6379.conf
##### 
