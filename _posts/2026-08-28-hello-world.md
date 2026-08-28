---
layout: post
title: 博客上线啦
date: 2026-08-28 12:00:00
description: 第一篇博文：博客怎么搭建的，以及以后写什么
tags: 随笔
categories: blog
related_posts: false
---

博客今天上线了。基于 Jekyll + [al-folio](https://github.com/alshedivat/al-folio) 主题，托管在 GitHub Pages 上，推送 Markdown 到仓库的 `_posts/` 目录就会自动构建发布。

## 以后写什么

主要用来记录研究笔记和实验观察，偶尔写点随想。

## 写作备忘

- 文章放在 `_posts/`，文件名格式 `YYYY-MM-DD-标题.md`
- 公式直接写 LaTeX：行内像这样 \\( \ell_2 \\)，独立公式块如下

$$
\|\theta\|_2 = \Big( \sum_i \theta_i^2 \Big)^{1/2}
$$

- 图片放 `assets/img/`，用 `![描述](/assets/img/文件名.png)` 引用

第一篇就写到这。
