# 支点云平台(Pivaiot Cloud)开放文档

## 简介

支点云平台开放文档

## 文档编写约定

* 所有文档使用 markdown 编写，文件扩展名统一为 `.md`
* 所有 markdown 文件都放在 `/posts` 目录下,  同时 `/posts` 直接子目录为语言名称，其中包括 zh-CN 和 en-US 两个目录
* 每一个子类别在对应的语言目录下创建目录，把改类别的所有 markdown 文档放在这个目录下面
* 所有文件(包括目录)的命名都使用英文字符，只使用 (^0-9a-zA-Z\-$) 来命名
* 所有的图片等二进制文件都放在 `/assets` 目录下面，子目录和 `/posts` 的子目录对应，对于不区分语言的文件，可以单独在 assets 目录下建立文件类型的目录归纳在一起

## markdown 文档模板定义

```yaml
---
title: 文档标题
subtitle: 文档副标题
tags:
    - 标签1
    - 标签2
---
文档内容(使用 markdown 格式)
```

## 文档目录生成规则

* h1/h2/h3 将会自动生成页面阅读导航菜单

## 站点菜单生成规则

为了方便文档生成为HTML浏览，可以定义页面菜单进行导航. 在项目根目录下创建 `menu.json` 来定义页面菜单.

## 目录

* [English](posts/en-US)
* [中文](posts/zh-CN)
  * [消息传输协议](posts/zh-CN/50-protocol)
    * [37 消息传输协议](posts/zh-CN/50-protocol/37-mtp.md)
  * [快速开始](posts/zh-CN/10-quickstart)
    * [数据点定义](posts/zh-CN/10-quickstart/data-point.md)