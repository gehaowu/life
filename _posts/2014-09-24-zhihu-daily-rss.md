---
author: ccbikai
comments: true
date: 2014-09-24 17:00:28 +0800
layout: post
slug: zhihu-daily-rss
title: 知乎日报 RSS
postid: 1626
categories:
- 一块分享
tags:
- 知乎
- RSS
- 工具
---
之前用的知乎日报 RSS 是别人的，但是最近不工作了，所以只能自己动手折腾一个。 
[![知乎日报](http://ww3.sinaimg.cn/large/c74746f0gw1ei8pvavboij20r808cmz2.jpg)](http://ww3.sinaimg.cn/bmiddle/c74746f0gw1ei8pvavboij20r808cmz2.jpg)

<!-- more -->
用 Fiddler 抓包，然后 Python 模拟安卓客户端获取内容，用模板渲染一次，加上缓存就 OK 了。不过知乎日报的的API太简陋，不输出更新时间和作者，让人感觉很不舒服。而且有的文章还是站外的，只能去输出一个链接了。首页 14 分钟更新一次，分类的缓存有效期 30 分钟，超过 30 分钟访问时会刷新一次。

知乎日报首页 RSS： http://zhihurss.jd-app.com/dailyrss 。

分类RSS：  
“足球日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/8  
“动漫日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/9  
“设计日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/4  
“开始游戏” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/2  
“财经日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/6  
“电影日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/3  
“电子音乐” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/7  
“不许无聊” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/11  
“大公司日报” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/5  
“互联网安全” 的 RSS 为 http://zhihurss.jd-app.com/daily/id/10 

其他日报的RSS请访问 [http://zhihurss.jd-app.com/theme](http://www.miantiao.me/url/zhihurss) 。
