# 视听质量检测工作站 · 发布库

本仓库只放安装包与在线更新清单，**不含源码**（源码在私有仓库 `vqa-rs`）。

## 下载

- 最新版：见 [Releases](https://github.com/meng587/vqa-rs-releases/releases/latest)
- 更新清单：[latest.json](https://raw.githubusercontent.com/meng587/vqa-rs-releases/master/latest.json)（客户端自动更新读取此文件）

## 说明

- 安装包均为 Tauri NSIS 构建、minisign 签名，更新时校验签名。
- 本库自 v0.2.193 起接收新版本；v0.2.46 – v0.2.192 旧安装包已随源码库转私有而不再公开提供，如需旧版请联系维护者。
- 已安装 v0.2.192 及更早版本的客户端无法跨库自动升级，请手动下载最新版安装一次，此后恢复自动更新。