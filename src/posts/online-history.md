---
title: "南工在线网站历史"
date: "2020-10-20T15:55:39.000Z"
update: "2020-10-20T15:55:39.000Z"
author: "陈宇明"
tags: ["南工在线", "历史"]
intro: "陈宇明学长介绍南工在线的发展历史"
---

## 2003 - 2013 年

下面第一张图是我能找到的最古老的网站界面：

![2003-2013](/assets/images/online-history/2003-2013.jpg)

以前的名字还叫工大在线，因为当初学校还不叫南工，域名还是 online.njut.edu.cn（目前是 online.njtech.edu.cn）。域名变更通知，来源于学校的公告：

> 根据学校“综合性、研究型、全球化”高水平大学建设需要，为进一步加强对外交流与合作，不断扩大我校办学的国际影响力，经学校研究决定，自 2014 年 1 月 1 日起，南京工业大学英文校名变更为 Nanjing Tech University（简称 NanjingTech），域名变更为 njtech.edu.cn（作为过渡，新旧域名将并行使用 6 个月）。

问了一下学长，这个旧版网站是他亲自关闭的，运行时间是在 2013 年之前。上图来源于知乎某匿名用户：[在南京工业大学（NJTECH）就读是怎样一番体验？](https://www.zhihu.com/question/24367863/answer/107465726) 于 2010 年写的答案。

## 2013 - 2018 年

我是 2015 年入学的，看到的是下面这个界面：

![2013-2018](/assets/images/online-history/2013-2018.png)

这个版本大概用了 5 年左右，使用 C# 开发的，具体的开发者我也不知道是谁。目前还在运行着，可以点击新版导航栏的怀念旧版进入，可以正常访问，但是很多资源已经不能访问了。

这时候的网站问题还是挺多的，很多视频不能在线播放、资源更新不及时等等。我接手的时候是 2016 年，那时候存储很紧张，导致很久没有更新资源，留言堆积了很多。刚开始我并没有把重心放到这上面来，而是弄了镜像站，不过很快就破产了。之后是 2017 年 3 月份的时候弄了资源社区，下面详细说。资源社区之后便是开始重写南工在线，于是有了下面这一版：

## 2018 - 2019 年

![2018-2019](/assets/images/online-history/2018-2019.png)

这一版是在 2018 年暑假的时候开发上线的，采用的是前后端分离的模式，后端采用 koa.js，前端采用 vue.js。后台管理和前端界面在同一个项目里。重写完这一版之后，便是资源的整理，以前的很多资源不能在线播放，只有重新编码之后才能看。资源整理用了很多时间，真是一段痛苦的经历。

后面我就去实习了，在 2019 年 3 月底的时候回学校的，那时候还没策划重构页面。我看了 git 的提交记录，重构页面的第一个 commit 是 2019 年 6 月 7 日上午 10:55 提交的，用了不到一个月，于是有了下面这一版：

## 2019 - 2020 年

![2019-2020](/assets/images/online-history/2019-2020.png)

我一直觉得这个版本太仓促了，采用的也是前后端分离的模式，后端采用 koa.js，前端采用 vue.js，UI 使用 vuetifyjs。至于为什么改成这种两栏的布局，主要还是个人喜好。迭代了很久才变成这个样子。这个版本接入学校的统一认证之后，新功能开发就冻结了，以后应该还会继续开发。

## 2020 - 至今

![2020-now](/assets/images/online-history/2020-now.png)

这个版本后端使用 Go+ Gin，前端使用 React.js + Spectre.css。我个人觉得，这个版本无论是从网站布局，整洁美观度，还是设备的适配情况做的 都比较粗糙，手机端的体验非常糟糕。主要的原因有三个：

- 没有手机端适配的经验
- 前后端一起开发，开发进度没有详细的规划，导致开发的时候会有赶工的情况
- 很多事情刚开始的时候很有激情，越到后面就得过且过了 没事，很快新的一版重构又会开始了，我觉得这也是我个人技术的不断成长，感谢你，让我在空闲时间有事可做。
