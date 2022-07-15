---
title: 64位windows中安装BIPublisherDesktop
date: 2013-08-05 15:41:32
categories:
- 技术
tags:
- ebs
- Bi Publisher
keywords:
description:
---


* 1.JRE问题
在x64的win7或者win8上安装BIPublisherDesktop32时，会提示需要jre 1.6或更高版本,哪怕已经安装过了jre了，也提示同样的错。
解决办法:安装x64的jre，至于原因，问候oralce去吧
<!-- more -->
* 2.安装BIPublisherDesktop32完成后，在word 2013里找不到BI Publisher的菜单项，嗯嗯，又到了问候oracle全家的时候了
解决办法:在BI Publisher 的安装目录下，比如本机是C:\Program Files (x86)\Oracle\BIPublisher\BI Publisher Desktop\DotNetInstallFiles，运行里面的TBMenusSetup2007，目前BI Publisher Desktop不支持x64版的office2013，虽然oracle 提供了一个BIPublisherDesktop64安装包，所以骚年，要用BIPublisherDesktop，安装32位office2013吧

