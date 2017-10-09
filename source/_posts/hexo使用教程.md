---
title: hexo使用教程
date: 2017-10-09 22:02:20
tags: [hexo]
author: May
---

hexo 使用教程，点击看更多！

<!-- more -->

# 安装

想玩hexo,需要安装以下应用
- [git](https://git-scm.com/)
- [node](https://nodejs.org/en/)

安装完成在终端输入

`$ npm install -g hexo-cli`  全局安装hexo-cli

# 准备&配置

1. 在自己的githun上创建 `你的用户名.github.io` 的项目
2. `git clone` 下来这个项目到本地
3. 进入刚刚clone下来的项目，输入`hexo init .`
4. `npm i`安装依赖
5. `hexo new 文章名`这里不需要加`.md`后缀
6. 创建的文章就会在`source/_posts/文件名.md`
7. 修改`_config.yml`
   - title 改为你的名字
   - subtitle 网站副标题
   - description 网站描述
   - author 您的名字
   - language 语言
   - timezone 网站时区
   - type 改成 git
   - 最后一样增加`repo: 仓库地址`
   - [更多配置]（https://hexo.io/zh-cn/docs/configuration.html）

# 指令

| 指令 | 缩写 | 功能 |
| ------ | ------ | ------ |
| hexo new XXX | -- | 创建一个XXX的文章 |
| hexo denerate | hexo g | 生成静态文件 |
| hexo publish | --  | 发布草稿 |
| hexo server | hexo s | 启动本地服务器（一般可以在4000端口看） |
| hexo deploy | hexo d | 部署网站 |
| hexo clean | -- | 清理缓存 |

# 主题

[hexo 各种主题](https://hexo.io/themes/index.html)
1. 每个主题想相当于一个项目 需要将项目clone到themes
2. 在`_config.yml`修改`theme`为刚刚`clone`的主题
