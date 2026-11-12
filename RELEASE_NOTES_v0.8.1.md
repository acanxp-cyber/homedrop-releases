# HomeDrop Windows 0.8.1

## 下载

Release 中只提供一个用户安装包：

`HomeDrop-Windows-Setup.exe`

App 内“下载或更新 Windows 版”会直接下载这个文件，不再先打开 Release
页面让用户挑选附件。

## 更新

- Windows 安装包使用固定文件名，`releases/latest/download` 链接始终指向
  最新稳定版。
- 安装器内置 Node.js，不需要单独安装运行环境。
- 安装、隐藏启动、健康检查和原有照片目录保持兼容。
- SHA-256 校验值写入 Release 说明，不再额外提供第二个校验文件下载。

SHA-256:

`F85D46B9557071819D63EF5882B8A2AD56AEF995FA8E7EF72ED46C5A5B406C2B`
