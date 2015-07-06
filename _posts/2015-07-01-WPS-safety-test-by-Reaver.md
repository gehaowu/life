---
author: Haowu Ge
comments: true
date: 2015-07-01  22:02:52 +0800
layout: post
slug: nexus-7-two
title: 通过 Reaver 测试 WPS 安全性
postid: 1601
categories:
- 扯淡文章
tags:
- 败家
- 平板
- 看书
---

```sh
airmon-ng start wlan0
airodump-ng wlan0
reaver -i moninterface -b bssid -vv
```
<!-- more -->
