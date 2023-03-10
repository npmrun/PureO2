---
layout: "@blog/layouts/BlogPage.astro"
title: PureO2
hideMenu: true
heroImage: https://api.lorem.space/image/movie?w=1360&h=800
---

## 博客使用指南

[Astro](https://astro.build/)是一个不错的框架,也已经浅用开发了几个静态博客，整个过程还是比较舒心的。在此也是分享下我使用的过程。

## 纯在线方案

1. [stackblitz](https://stackblitz.com/)  
    一个在线编辑器，能够在本地浏览器模拟一个linux环境，同时可以运行启动端口，是个十分方便的在线编辑器，可惜尚存在一些问题，比如跟Github同步之后，如果没有及时提交就刷新网页，此时数据就丢失了。
2. [netlify](https://www.netlify.com/)  
    能够直接部署Github仓库的代码并自动生成一个域名，如果Github推送了，能够自动触发代码编译部署，所以写了文章只需直接提交即可，别的无需操心，速度也是挺快的。

因此，有了这两个工具，使得云上编辑更方便了，毕竟比起github不停的抽风，stackblitz速度还是不错的。不过缺点有以下几点：

1. stackblitz同步github仓库，如果未能同步成功，然后刷新界面，本次未提交的代码将全部丢失，如果要克服的话，必须没编辑几下就提交。同时也有可能网络问题导致无法同步，此时刷新也会丢失代码。

2. 无法粘贴图片，但可以同步PicGo先自行上传到cdn上再粘贴。

## 本地开发方案

使用此博客本地开发还是十分方便的，前提是安装了本项目推荐的几个插件，可以在`插件列表-->推荐`中可以看到，配置也大致配置了，除了可能`browse-lite`需要自行调整一下。本博客提供了以下几点：
1. 粘贴图片  
    可以自行复制图片，然后右键选择粘贴图片，那么图片会自动复制到`public/article`目录下，编辑器也会插入一个图片。
2. 模板生成  
    右键文件夹第一个选项点击即可，取个名字就行
3. vscode运行网页
    运行`npm run dev`后，使用`Ctrl+Shift+A`打开命令，执行`Browse Lite: Open ...`即可出现网页，热更新也是实时的。
4. 插入当前时间  
    编辑器内使用`Ctrl+Shift+A`打开命令，执行`Inser Formatted DateTime`，会在编辑器中生成当前时间，可当作发布时间和更新时间。

