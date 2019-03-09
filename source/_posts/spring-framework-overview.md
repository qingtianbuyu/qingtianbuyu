---
title: spring-framework 概览
date: 2019-03-09 22:05:16
tags:
categories: Spring
---

### 序言

今天开始探索Spring的第一天,五年来它每天都在IDE里面守候,看着它从指间码过,可从来没有认真看过一眼。。。。
好吧，直入主题,首先从spring-framework的[官库](https://spring.io/projects/spring-framework) fork 一份到自己的仓库,然后就可以愉快的调试啦
本系列代码地址:https://github.com/qingtianbuyu/spring-framework
Branch:[master](https://github.com/qingtianbuyu/spring-framework/tree/master)
运行环境如下:

> JDK版本: 1.8+
> Spring版本: > 5.1.3.RELEASE


Spring Framework 模块图

![avatar](https://docs.spring.io/spring/docs/5.0.0.M5/spring-framework-reference/html/images/spring-overview.png)

### 核心技术
####The  IOC Container
IOC: 控制反转,由Spring IOC容器来管理对象的生命周期和对象之间的关系
DI: 是IOC的实现方式,