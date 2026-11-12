# HomeDrop Windows

HomeDrop 的 Windows 接收端。iPhone App 通过同一 Wi-Fi 把原始照片和视频
备份到你的电脑，文件不经过第三方云存储。

## 下载

[直接下载最新版 HomeDrop Windows 安装包](https://github.com/acanxp-cyber/homedrop-releases/releases/latest/download/HomeDrop-Windows-Setup.exe)

App 内的“下载或更新 Windows 版”使用同一个直链。Release 中只提供一个
需要安装的软件包，不需要再单独下载校验文件。每个版本的 SHA-256 写在
Release 说明中。

## 安装

1. 运行安装器。
2. 选择是否随 Windows 启动。
3. 安装完成后 HomeDrop 会在浏览器打开本地控制台。
4. iPhone 安装 HomeDrop App，并扫描控制台中的二维码完成首次配对。
5. 后续 App 会通过局域网自动发现已配对电脑。

## 文件位置

- 程序：`%LOCALAPPDATA%\Programs\HomeDrop`
- 配置和索引：`%LOCALAPPDATA%\HomeDrop\data`
- 默认照片目录：`%USERPROFILE%\Pictures\HomeDrop`

卸载 HomeDrop 不会删除配置、索引或照片目录。

## 当前发布状态

0.8.x 为测试版本，安装器尚未进行 Authenticode 代码签名。Windows
SmartScreen 可能显示“未知发布者”；请先核对 Release 中的 SHA-256。

源码仓库保持私有。本仓库只发布 Windows 安装包和版本说明。
