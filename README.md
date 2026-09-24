# 牛牛雷达版

**牛牛雷达版（NiuNiu Radar）** 是基于牛牛的 Windows 衍生版，在硬件与网络监控基础上加入 Codex GPT 雷达缓存、综合评分和可定制的任务栏显示。

本仓库是公开的**发布渠道**，只保存安装说明和 GitHub Release 附件，**不包含应用源码**。

## 下载

请从 [最新正式版](https://github.com/franklai-rise/NiuNiu-Radar-Downloads/releases/latest) 下载 Windows x64 安装包。

## 发布约定

| 项目 | 约定 |
| --- | --- |
| 正式版标签 | `v<主版本>.<次版本>.<修订版本>`，例如 `v0.1.0` |
| Windows 安装包 | `NiuNiu-Radar-<主版本>.<次版本>.<修订版本>-Windows-x64-Setup.exe` |
| 测试版 | 标为 GitHub **Pre-release**，例如 `v0.2.0-beta.1`；不作为默认下载版本 |
| 自动更新与官网读取地址 | `https://api.github.com/repos/franklai-rise/NiuNiu-Radar-Downloads/releases/latest` |

GitHub 的 `releases/latest` 与上述 API 都只返回最新正式 Release，因此可直接获取版本号、发布时间和安装包下载链接。

## 共存说明

牛牛雷达版使用独立的程序标识、安装目录、配置数据目录、开机启动任务与更新地址；它可以与官方牛牛同时安装和更新，互不覆盖。
