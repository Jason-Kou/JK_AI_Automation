# jasonkou.com

个人主页。Jekyll + [minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)，GitHub Pages 托管（`master` 分支根目录 + CNAME）。

## 结构

```
_config.yml            站点配置（url 必须是 https://jasonkou.com，baseurl 留空）
_data/navigation.yml   顶部导航
index.md               首页（splash 布局 + feature_row 卡片）
_pages/                独立页面：/projects/ /writing/ /about/
_posts/                文章，文件名 YYYY-MM-DD-slug.md，/writing/ 自动列出
interactive/           独立 HTML 单页（不走主题）
```

## 加一篇文章

在 `_posts/` 建 `YYYY-MM-DD-slug.md`：

```yaml
---
title: "标题"
excerpt: "一句话摘要，会显示在列表页"
categories: [分类]
tags: [标签]
---
```

推到 `master` 即自动部署。

## 本地预览

```bash
bundle install
bundle exec jekyll serve
```
