# 快推 EasyPost — 一键自媒体多平台发布与矩阵助手

**快推 EasyPost 是一款 Chrome 扩展：一次编辑，一键把图文笔记与短视频同步填充到 10 大自媒体平台，告别逐个平台重复上传。**

[![Chrome 网上应用店](https://img.shields.io/badge/Chrome%20Web%20Store-%E5%AE%89%E8%A3%85-blue)](https://chromewebstore.google.com/detail/ajdpfajmgibbniipjfgjiappllekpiak)
![评分](https://img.shields.io/badge/%E8%AF%84%E5%88%86-4.4%E2%98%85-yellow)
![免费](https://img.shields.io/badge/%E4%BB%B7%E6%A0%BC-%E5%AE%8C%E5%85%A8%E5%85%8D%E8%B4%B9-green)

![快推导入主图](assets/promo-1.png)

## 核心功能

- **一次编辑，全平台同步**：标题、正文、图片、视频、封面填一次，自动同步填充到各平台发布页
- **图文 + 短视频**：两种内容形态都支持
- **智能适配**：自动按各平台的标题字数上限与格式要求调整，不再手动改五遍
- **失败自动重试**：填充失败自动重试，减少漏发、错发
- **数据追踪**：统一查看各平台内容数据表现，矩阵运营心里有数

## 支持的 10 大平台

抖音 · 小红书 · 快手 · 视频号 · B站 · 微博 · YouTube · TikTok · Instagram · X

![十大平台](assets/promo-3.png)

## ⚡ 快推导入（主推功能）

刷 X 时看到想搬运分发的好内容，不必再下载视频、复制文案、重打标签：

在 X 帖子下方点击 **「⚡快推导入」** 按钮，高清视频 / 原图 + 完整文案 + #话题标签 会被一键解析并导入快推工作台，接着就能分发到全部平台。

实现方式：DOM 嗅探帖子内容 + `api.fxtwitter.com` 直链解析；草稿保存在 `chrome.storage.local`，素材持久化在浏览器 IndexedDB。整个过程**零新增高危权限**。

![工作台实拍](assets/promo-7.png)

## 使用步骤

1. 在 Chrome 网上应用店安装「快推 EasyPost」
2. 打开工作台，编辑一次标题、正文并上传素材（或在 X 帖子下点「⚡快推导入」直接导入）
3. 勾选要分发的平台，一键同步填充
4. 在各平台发布页确认后发布，用数据追踪查看表现

## 纯本地 · 免注册 · 完全免费

- **纯本地运行**：内容不经过任何服务器，草稿与素材只存在你自己的浏览器里
- **免注册**：装上就能用，不用开账号
- **完全免费无配额**：没有条数限制、没有付费墙

## 安装

👉 [Chrome 网上应用店 — 快推 EasyPost](https://chromewebstore.google.com/detail/ajdpfajmgibbniipjfgjiappllekpiak)（当前评分 4.4 星）

---

## English

**EasyPost** is a Chrome extension for creators: write once, and publish everywhere. It syncs your posts and short videos to 10 platforms — Douyin, Xiaohongshu, Kuaishou, WeChat Channels, Bilibili, Weibo, YouTube, TikTok, Instagram, and X — with automatic per-platform title/format adaptation and smart retry on failed fills. Its signature feature, **⚡ Quick Import**, lets you grab an X post's HD video/original images, full text, and hashtags into the workbench with one click, then redistribute everywhere. EasyPost runs 100% locally (drafts in `chrome.storage.local`, media in IndexedDB), needs no account, and is completely free with no quotas.

👉 [Get it on the Chrome Web Store](https://chromewebstore.google.com/detail/ajdpfajmgibbniipjfgjiappllekpiak)
