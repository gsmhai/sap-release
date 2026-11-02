# NotifyGuard 发布仓库

本仓库**仅用于存放 NotifyGuard 的自动更新产物**，由 CI 自动发布，请勿手动修改。

## 这是什么
- 这里是公开仓库，NotifyGuard 客户端通过内置更新器从这里下载更新。
- 每次发布由源码仓库的 GitHub Actions 工作流自动生成并推送，包含：
  - `NotifyGuard_x.y.z_x64-setup.exe`（安装包）
  - `NotifyGuard_x.y.z_x64-setup.nsis.zip`（增量更新包）
  - `latest.json`（更新清单，客户端据此判断是否需更新）

## 普通用户
打开软件，在「检查更新」中即可自动获取新版本。
也可以来这里手动下载安装。

## 版本与更新
- 更新检测依赖版本号递增（`tauri.conf.json` 的 `version`），版本号不变不会触发更新。
- 如需回滚或手动安装，可在此处 Releases 页面下载对应版本的安装包。

---
此仓库内容由自动化流程维护。
