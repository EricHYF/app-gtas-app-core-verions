# GPTR · 谷歌市场雷达 updates

Official application installers and signed Core update packages.
This repository contains release artifacts and public documentation.

## 0.1.2 · 内测开发版

- 当前内核：**0.1.2 (Build 1792994698)**，macOS Apple Silicon（arm64）。
- [0.1.2 更新日志](CHANGELOG.md)
- [内核下载与发行说明](https://github.com/EricHYF/app-gtas-app-core-verions/releases/tag/core-dev-v0.1.2-build.1792994698)
- [development 签名更新索引](https://github.com/EricHYF/app-gtas-app-core-verions/releases/download/development-latest/update.json)

本次发布包含加密内核、签名更新索引、校验文件和发行说明；DMG 安装器仍保留在本地。加密内核由已有 GPTR App 的 Settings → 关于与更新下载安装，不能作为独立安装器直接运行。

开发版与 stable 更新源隔离。本地与公网版本、BuildNumber 和包内容一致时，App 显示“当前已是最新版本”。

仓库的 `0.1.2` 标签标记本次公开文档快照；不可变构建标签 `core-dev-v0.1.2-build.1792994698` 和 `development-latest` 更新入口继续用于客户端更新。
