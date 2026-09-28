# 星海 (XingHai)

个人聚合工作台（Windows 桌面，Tauri 2 + React 18 + TypeScript + SQLite）。本地优先、离线可用、无账号，组件可插拔。

## 本仓库的用途

**只用于分发安装包与更新清单，不存放应用源码。**

- 需要安装或更新，请到 [Releases](https://github.com/QingTFH/xinghai/releases) 页面下载最新的 `XingHai_<版本>_x64-setup.exe`。
- 应用内的「检查更新」会读取本仓库 Releases 下的 `latest.json`，比对版本号后提示；下载完成后校验 sha256，不通过则不会安装。
- `latest.json` 与安装包一并作为 Release 附件上传，两者由同一次构建产出，摘要是同一个文件的实测值。

## 其他

- 仓库保持「无代码」是刻意的：应用源码与个人数据均不在此处。
- 若把某个 Release 标记为「预发布」，应用侧的「检查更新」不会看到它——这是更新通道的灰度开关。
