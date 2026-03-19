# 时光影视 下载说明

## 选择哪个版本

- `stable`
  适合普通用户，更新更稳。
- `beta`
  适合愿意测试新版本的用户，可能会更早收到更新。

## 选择哪个安装包

### 电视 / 投影 / 机顶盒

优先选择 `leanback` 包：

- `tvbox-leanback-arm64_v8a-modern-514.apk`
- `tvbox-leanback-armeabi_v7a-modern-514.apk`

一般规则：

- 新一些的电视、投影、盒子：
  优先尝试 `arm64_v8a`
- 较老设备：
  如果 `arm64_v8a` 无法安装，再尝试 `armeabi_v7a`

### 手机 / 平板

选择：

- `tvbox-mobile-arm64_v8a-modern-514.apk`

## 当前正式版本

- 稳定版：
  [tvbox-stable-v5.1.4](https://github.com/TimeJason/shiguang-yingshi/releases/tag/tvbox-stable-v5.1.4)
- 测试版：
  [tvbox-beta-v5.1.4](https://github.com/TimeJason/shiguang-yingshi/releases/tag/tvbox-beta-v5.1.4)

## 如果 GitHub 下载慢

应用内更新已经内置镜像兜底。  
如果你是手动下载，优先从当前 Release 页面下载；若访问不稳定，可稍后重试，或直接在应用内使用更新功能。

## 应用内更新

应用默认检查 `stable` 通道。  
如果你在设置里切到 `beta`，之后只会检查 `beta` 更新。

当前 manifest 地址：

- `stable`
  [raw manifest](https://raw.githubusercontent.com/TimeJason/shiguang-yingshi/main/tvbox/stable/manifest.json)
- `beta`
  [raw manifest](https://raw.githubusercontent.com/TimeJason/shiguang-yingshi/main/tvbox/beta/manifest.json)
