# useAiWork Releases

useAiWork 桌面应用的公开安装包与签名更新资源。此仓库仅用于分发，不保存项目源码。

## 下载

从 [最新 Release](https://github.com/WebJeffery/use-aiwork-releases/releases/latest) 下载适合平台的安装包，并阅读对应发布说明。

- macOS Apple Silicon：下载 `.dmg` 安装包。
- `.app.tar.gz` 与 `.sig` 用于应用内签名更新。
- `latest.json` 为 Tauri 更新清单；`SHA256SUMS` 提供文件一致性校验。

macOS 当前使用临时代码签名，未完成 Apple 公证。平台可用性以每次 Release 的实际资产为准。

## 更新与签名

本仓库采用独立 updater 签名密钥。旧分发源的安装版需要手动安装本仓库的基线版本，后续使用应用内更新。私钥不存放于此仓库。

正式版本不可覆盖。每个 Release 包含同版本安装包、更新资源、发布说明与 SHA256 清单；发布前先上传草稿并核对资产。
