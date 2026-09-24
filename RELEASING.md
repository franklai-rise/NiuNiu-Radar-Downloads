# 发布牛牛雷达版

本仓库仅用于公开发布，不提交应用源码或构建中间文件。

## 正式版

1. 将版本号同步到安装包和程序，例如 `0.1.1`。
2. 构建 Windows x64 安装包，名称必须为 `NiuNiu-Radar-0.1.1-Windows-x64-Setup.exe`。
3. 创建标签 `v0.1.1` 的 GitHub Release，上传该安装包。
4. 保持该 Release 为正式版：不选 Draft，也不选 Pre-release。

GitHub 会把该 Release 作为 `releases/latest` 返回。官网可读取 `tag_name`、`published_at` 和该附件的 `browser_download_url`。

## 测试版

使用例如 `v0.2.0-beta.1` 的标签，并在 GitHub Release 中选中 **Set as a pre-release**。测试版不会成为默认下载版本，也不会被程序自动更新读取。
