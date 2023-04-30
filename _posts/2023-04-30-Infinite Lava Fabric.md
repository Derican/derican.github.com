---
title: Infinite Lava Fabric
layout: post
post-image: "https://derican-picgo.oss-cn-hangzhou.aliyuncs.com/img/icon%20-%20%E5%89%AF%E6%9C%AC.png"
description:
category: Minecraft
---

## 起因 Intro

最初是21年寒假在家自己做了以科技复兴（Tech Reborn）为核心的整合包，然后对于几乎所有的科技模组来说，能量的充足供应是一个逃不开的话题。一种无限能源的方式是地毯机配合燃料发电机，然而其存在卡顿严重、效率低等问题。而岩浆作为较高效率的燃料，如果能像水一样再生，那么对于能源的产生将产生很大帮助。

## 类似模组 Related Work

在此之前也有很多像控制流体无限性的模组，既有单纯以岩浆为主题的，也有兼有功能性和扩展性的模组，有开发者制作了[相关wiki](https://modwiki.miraheze.org/wiki/Instant_Lava)，用于查询不同版本对应可用的模组。对于1.18.1的Fabric来说，正好缺乏这个功能的模组，故我选择进行重新开发。

## 历程 Story

本身无限岩浆是一个很简单的功能，只需要找到原版里对应的岩浆的属性方法，对返回值进行Mixin就可以。主要是整个模组打包的过程，其中一些配置文件的修改也比较考验信心。

## 注释 Notes
