---
title: ETCD入门
catalog: true
date: 2019-01-29 15:59:11
subtitle:
header-img:
tags:
- etcd
---
#### 一、etcd介绍
##### 1.什么是etcd
- 一个高可用的分布式键值存储系统。
- 内部使用raft协议作为一致性算法
- 基于Go语言实现

##### 2.etcd特点
&emsp;&emsp;简单、安全、快速、可靠

##### 3.etcd用途
&emsp;&emsp;常用于服务发现、服务注册、以及配置中心

#### 二、etcd基本使用 
##### 1.etcd安装和启动
- 选择合适的[发行版本](https://github.com/etcd-io/etcd/releases)下载
- 将解压文件夹下的etcd和etcdctl移动到'/usr/local/bin/'路径下
- 终端执行**etcd**：
![result](ETCD入门/result.png)