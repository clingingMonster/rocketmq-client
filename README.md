# RocketMQ-Spring [![Build Status](https://travis-ci.org/apache/rocketmq-spring.svg?branch=master)](https://travis-ci.org/apache/rocketmq-spring) [![Coverage Status](https://coveralls.io/repos/github/apache/rocketmq-spring/badge.svg?branch=master)](https://coveralls.io/github/apache/rocketmq-spring?branch=master)

[![Maven Central](https://maven-badges.herokuapp.com/maven-central/org.apache.rocketmq/rocketmq-spring-all/badge.svg)](https://search.maven.org/search?q=g:org.apache.rocketmq%20AND%20a:rocketmq-spring-all)
[![GitHub release](https://img.shields.io/badge/release-download-orange.svg)](https://github.com/apache/rocketmq-spring/releases)
[![License](https://img.shields.io/badge/license-Apache%202-4EB1BA.svg)](https://www.apache.org/licenses/LICENSE-2.0.html)
[![Average time to resolve an issue](http://isitmaintained.com/badge/resolution/apache/rocketmq-spring.svg)](http://isitmaintained.com/project/apache/rocketmq-spring "Average time to resolve an issue")
[![Percentage of issues still open](http://isitmaintained.com/badge/open/apache/rocketmq-spring.svg)](http://isitmaintained.com/project/apache/rocketmq-spring "Percentage of issues still open")

This project aims to help developers quickly integrate [RocketMQ](http://rocketmq.apache.org/) with [Spring Boot](http://projects.spring.io/spring-boot/). 

## 特性
和官方apache rocketMq-client 使用方法一样
我还特意添加了两个事务mq的方法,当适用事务消息时可以监听本地事务，
在提交事务消息，减少一个和mq交互次数（当然不喜欢可以去掉）



## 版本要求
- JDK 1.8 以上
- Spring Boot 1.5 以上

## Usage

Add a dependency using maven:

```xml
<!--add dependency in pom.xml-->
<dependency>
    <groupId>org.apache.rocketmq</groupId>
    <artifactId>rocketmq-spring-boot-starter</artifactId>
    <version>${RELEASE.VERSION}</version>
</dependency>
``` 

## Samples

Please see the [rocketmq-spring-boot-samples](rocketmq-spring-boot-samples).

## User Guide

Please see the [wiki](https://github.com/apache/rocketmq-spring/wiki) page.



