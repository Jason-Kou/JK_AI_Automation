---
permalink: /zh/projects/
title: "项目"
nav: main_zh
home_url: /zh/
toc: true
toc_label: "项目"
---

做的东西大多围绕一个主题：**让 AI 在本地跑起来，并且真的省事**，而不是又一个需要联网、要付费、要手动点十下的 demo。

## zhiyin — macOS 语音输入

按住热键说话，松开，文字直接出现在光标位置，任何 App 都能用。

- 14 种语言，**100% 离线**，音频不出本机
- MLX 后端，Apple Silicon 上近乎实时
- 不需要账号、不需要订阅

[GitHub →](https://github.com/Jason-Kou/zhiyin){: .btn .btn--primary}

## ExpoSnap — 展会名片扫描（iOS）

展会、贸易展上收名片的痛点是回酒店还要手动录一遍。ExpoSnap 拍一下就完事。

- 自动检测名片边缘，OCR 提取联系人信息，一次点击
- 可以给每个联系人加**语音备忘、跟进任务、展位照片、文字笔记** —— 记住的是"这个人聊了什么"，不只是名字
- OCR 和存储全在本机，**无网也能用**
- 导出到 iPhone 通讯录，或对接 CRM

[App Store →](https://apps.apple.com/us/app/exposnap/id6752795586){: .btn .btn--primary}
[支持页面](https://exposnap-support.vercel.app){: .btn .btn--inverse}

## AI 自动化流水线

自用的一套 agent 链路：定时扫描资讯源 → 去重筛选 → 生成简报 → 渲染成视频 → 分发。目前私有仓库，实现细节和踩坑记录会陆续写成[文章](/zh/writing/)。

<!-- 新项目加在这里：一个 ## 标题 + 两三行说明 + 一个链接按钮 -->
