# KernelSU 模块收藏

收藏网上发现的有趣模块，供日后查找。所有模块归原作者所有；收录不代表推荐安装、安全审计或兼容性保证。

## 模块目录

| 模块 | 用途 | 收录版本 | 许可证 | 本仓库测试状态 |
| --- | --- | --- | --- | --- |
| [DirBridge](#dirbridge--下载目录映射) | 将应用下载目录只读映射到播放器可访问的位置，不复制视频 | v0.1.3 | MIT | 未安装测试 |

## DirBridge · 下载目录映射

- 作者：liebig（GitHub：Liebig773）
- 原项目：https://github.com/Liebig773/DirBridge
- 发布与下载：https://github.com/Liebig773/DirBridge/releases
- 发现来源：[酷安原帖](https://www.coolapk.com/feed/74550945?s=NDM1YzI2MzUzYTlkNzZnNmFkYWJiODN6a1664)
- 收录版本：v0.1.3（versionCode 103）
- 原始安装包文件名：`DirBridge-v0.1.3.zip`
- 安装包归档状态：尚未上传至本仓库；请先使用上游 Releases。

### 功能与限制

根据作者说明，模块使用只读 bind mount，将 Telegram、迅雷等应用的下载目录映射到共享存储的播放器入口；支持多目录、中文 WebUI、开机自动应用，不复制、移动或转码视频。

要求 Root、KernelSU / KernelSU Next 及标准 BusyBox、WebUI 接口。安装器最低要求 Android 10（API 29），不代表所有 Android 10 及以上设备均已验证。当前仅支持主用户的内部共享存储；Magisk、APatch 不在作者当前安装器支持范围内。以原项目最新说明为准。

本仓库仅核对了所提供 ZIP 的模块元数据、许可证及文件列表，未安装、未实机测试，也未做完整代码安全审计。

### 文件校验

所提供安装包计算得到的 SHA-256（尚未与上游校验文件核对）：

```text
4dff01c40e6d83f83bfb0f054bdbfd3b6c6b01a0a127b897ad1b131f2e447209  DirBridge-v0.1.3.zip
```

### 许可证与署名

DirBridge 使用 MIT License，Copyright (c) 2026 liebig。原始安装包包含 `LICENSE`；分发时应保留原版权声明及许可全文。

本仓库仅为第三方收藏整理，与原作者不存在官方关联。

## 收录原则

1. 记录原作者、项目地址、发现来源、版本、许可证和实际测试状态。
2. 有明确分发许可的安装包才做镜像归档，并保留原文件及许可证；未明确允许分发的仅记录介绍与链接。
3. 归档不保证持续更新；安装前查看上游说明、兼容性与风险提示。
4. Root 模块拥有高权限，请自行审查并做好备份，不要因被收录就直接安装。
