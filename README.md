# 时光影视 下载分发

这是时光影视的公开分发仓库，用于提供：

- Android APK 安装包
- 应用内更新所需的 `stable` / `beta` manifest
- GitHub Releases 下载入口

## 下载入口

- 稳定版 Releases：
  [tvbox-stable-v5.1.4](https://github.com/TimeJason/shiguang-yingshi/releases/tag/tvbox-stable-v5.1.4)
- 测试版 Releases：
  [tvbox-beta-v5.1.4](https://github.com/TimeJason/shiguang-yingshi/releases/tag/tvbox-beta-v5.1.4)
- 下载说明：
  [DOWNLOAD.md](https://github.com/TimeJason/shiguang-yingshi/blob/main/DOWNLOAD.md)

## 更新通道

- `stable`
  面向普通用户，优先保证稳定性。
- `beta`
  面向愿意提前体验新版本的用户，可能更早收到更新。

## 应用内更新来源

应用内会从以下地址检查更新：

- `stable`
  [manifest.json](https://raw.githubusercontent.com/TimeJason/shiguang-yingshi/main/tvbox/stable/manifest.json)
- `beta`
  [manifest.json](https://raw.githubusercontent.com/TimeJason/shiguang-yingshi/main/tvbox/beta/manifest.json)

主下载源为 GitHub Releases。  
如果 GitHub 访问不稳定，客户端会自动尝试镜像兜底。

## 说明

- 本仓库当前只用于 APK 软件升级分发。
- 数据包更新能力在应用协议中仍保留，但当前默认不启用。
- 如果你只想正常使用，选择 `stable` 即可。
