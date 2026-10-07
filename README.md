# DPaste

[![Latest release](https://img.shields.io/github/v/release/lvshu-is-666/DPaste)](https://github.com/lvshu-is-666/DPaste/releases/latest)
[![Downloads](https://img.shields.io/github/downloads/lvshu-is-666/DPaste/total)](https://github.com/lvshu-is-666/DPaste/releases)

> **跨平台剪贴板管理器** · Windows / macOS / Android
> 自动保存复制历史 · 50+ 一键处理 · 随时搜索 · 钉在屏幕 · 同网络多设备互传

[官网](https://lvshu.cc.cd) ｜ [中文站](https://lvshu.cc.cd/cn/) · [English](https://lvshu.cc.cd/en/) ｜ [更新日志](https://lvshu.cc.cd/cn/changelog/)

![DPaste](https://lvshu.cc.cd/og-image.jpg)

> **本仓库是官方安装包发布仓库**：只提供安装包与更新说明，**不包含源代码**。
> 下载、更新与文档请以官网为准；反馈请走 Issues。

## 下载

安装包统一发布在官方发布页，以下链接**永远指向最新版本**，无需关心版本号：

- 官网下载页（自动读取最新版，推荐）：<https://lvshu.cc.cd/cn/download/>
- Gitee Releases（国内更快）：<https://gitee.com/lvshu-wangping-WP/dpaste/releases/latest>
- GitHub Releases（镜像）：<https://github.com/lvshu-is-666/DPaste/releases/latest>

| 平台 | 系统要求 | 安装包文件名 |
| --- | --- | --- |
| Windows | Windows 10 1809 及以上 · x64 | `DPaste_<版本>_x64-setup.exe` |
| macOS | macOS 12.0 及以上 · Apple Silicon | `DPaste_<版本>_aarch64_unsigned.dmg` |
| Android | Android 8.0 及以上 · arm64 | `androidApp-release.apk`（[GitHub 最新版直链](https://github.com/lvshu-is-666/DPaste/releases/latest/download/androidApp-release.apk)） |

> 供自动化脚本读取的最新版本信息（JSON，同样永远指向最新版）：
> `https://github.com/lvshu-is-666/DPaste/releases/latest/download/latest.json` ·
> `https://gitee.com/lvshu-wangping-WP/dpaste/releases/download/latest/latest.json`

## 功能

- **自动保存复制历史**：文本、图片、文件自动记录，不用手动收藏；可搜索、可分类、可给内容打标签。
- **50+ 一键处理**：自动识别内容类型，去重复、排顺序、清格式、提取文字、对比差异，处理完直接粘贴。
- **钉在屏幕**：把常用的文字、图片、地址钉在屏幕上，点一下即粘贴，不用来回切换窗口。
- **搜索与分类**：全文搜索，图片来源文字与二维码也能识别；文本、图片、链接自动归类。
- **多种显示方式**：卡片、列表、紧凑列表、侧边栏等，按自己的习惯选择。
- **记住内容来源**：每条记录都记住来自哪个软件或网页，想回去看看点一下就跳转。
- **同网络多设备互传**：手机和电脑连同一个 Wi-Fi 即可配对互传，**内容不经过任何服务器**（局域网直连 + 端到端加密）。
- **截图与标注**：截图、加标注、打马赛克、把图上的文字变成可粘贴文本，还能把截图钉在屏幕上。
- **文件预览**：PDF、Word、Excel、PPT、音视频与压缩包在列表里直接查看。
- **可插拔的功能开关**：每个功能都能单独开关，插件与主题都可自行选择。

## 安装提示

- **Windows 启动后一闪而过**：多为缺少运行库，请先安装 WebView2 Runtime 与 Visual C++ 2022 Redistributable (x64)。
- **macOS 提示「无法验证开发者」**：在「系统设置 → 隐私与安全性」中点击「仍要打开」；若提示「已损坏」，请勿移到废纸篓，在终端执行 `xattr -cr /Applications/DPaste.app` 后重新打开。当前 macOS 安装包未做代码签名。
- **Android 无法安装**：请允许「安装未知来源应用」；已装旧版本时先卸载再安装，避免签名冲突。

## 关于

- 完全免费：无内购、无订阅、无广告。
- 隐私优先：剪贴板内容只保存在你的设备与已配对设备上，不上传云端；详见[隐私政策](https://lvshu.cc.cd/cn/privacy/)。
- 使用须知见[服务条款](https://lvshu.cc.cd/cn/terms/)。
- 反馈与交流：[官网联系页](https://lvshu.cc.cd/cn/contact/) · QQ 群 1087465782。

---

# DPaste (English)

> **Cross-platform clipboard manager** for Windows, macOS and Android
> Auto-saved copy history · 50+ one-click transforms · instant search · pin to screen · LAN-only device sync

[Official site](https://lvshu.cc.cd) ｜ [English site](https://lvshu.cc.cd/en/) ｜ [Changelog](https://lvshu.cc.cd/en/changelog/)

> **This repository is the official release mirror**: it ships installers and release notes only, **no source code**.
> For downloads, updates and documentation, please use the official website; please file feedback in Issues.

## Download

Installers are published on the official release pages. The links below **always point to the latest version** — no version numbers involved:

- Official download page (reads the latest release automatically): <https://lvshu.cc.cd/en/download/>
- Gitee releases (faster in mainland China): <https://gitee.com/lvshu-wangping-WP/dpaste/releases/latest>
- GitHub releases (mirror): <https://github.com/lvshu-is-666/DPaste/releases/latest>

| Platform | Requirements | Installer name |
| --- | --- | --- |
| Windows | Windows 10 1809 or newer · x64 | `DPaste_<version>_x64-setup.exe` |
| macOS | macOS 12.0 or newer · Apple Silicon | `DPaste_<version>_aarch64_unsigned.dmg` |
| Android | Android 8.0 or newer · arm64 | `androidApp-release.apk` ([stable GitHub link](https://github.com/lvshu-is-666/DPaste/releases/latest/download/androidApp-release.apk)) |

> Latest-release metadata for scripts (JSON, always the newest version):
> `https://github.com/lvshu-is-666/DPaste/releases/latest/download/latest.json` ·
> `https://gitee.com/lvshu-wangping-WP/dpaste/releases/download/latest/latest.json`

## Features

- **Automatic history**: text, images and files are recorded as you copy, searchable, filterable and taggable.
- **50+ one-click transforms**: content types are detected automatically — deduplicate, sort, strip formatting, extract text, diff two blocks, then paste straight away.
- **Pin to screen**: keep frequently used text, images and addresses on screen and paste them with one click.
- **Search and categories**: full-text search including text inside images and QR codes, with automatic grouping.
- **Multiple layouts**: card, list, compact list, side panel and more.
- **Source tracking**: every entry remembers which app or web page it came from, one click takes you back.
- **LAN-only device sync**: pair your phone and computer on the same Wi-Fi and paste across devices — **content never goes through any server** (direct connection with end-to-end encryption).
- **Screenshots and annotation**: capture, annotate, blur and turn text in images into pasteable text, or pin a screenshot.
- **File previews**: PDF, Word, Excel, PowerPoint, audio, video and archives open right in the list.
- **Pluggable features**: enable only what you need; plugins and themes are up to you.

## Installation notes

- **Windows closes right after launch**: usually a missing runtime — install the WebView2 Runtime and Visual C++ 2022 Redistributable (x64).
- **macOS reports an unverified developer**: click "Open Anyway" under System Settings → Privacy & Security. If it says the app is damaged, do not move it to the bin — run `xattr -cr /Applications/DPaste.app` in Terminal and open it again. The macOS build is currently unsigned.
- **Android installation blocked**: allow "install unknown apps", and uninstall any older build first to avoid signature conflicts.

## About

- Completely free: no in-app purchases, no subscriptions, no advertising.
- Privacy first: clipboard content stays on your devices and paired devices, never uploaded to any cloud — see the [Privacy Policy](https://lvshu.cc.cd/en/privacy/).
- See the [Terms of Service](https://lvshu.cc.cd/en/terms/).
- Feedback: [contact page](https://lvshu.cc.cd/en/contact/)  · QQ group 1087465782.
