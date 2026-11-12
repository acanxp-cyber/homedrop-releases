# HomeDrop 0.8.0

- 新增 Windows 单文件安装器，内置 Node.js 运行时。
- 安装到当前用户目录，不要求单独安装 Node.js。
- 支持隐藏启动、开始菜单、桌面和 Windows 登录启动选项。
- 二维码优先使用真实家庭局域网地址，忽略 VPN 虚拟网卡。
- 新增 `_homedrop._tcp` 局域网广播。
- 新增稳定设备 ID；iPhone 已配对设备可在电脑 IP 变化后自动重连。
- 新安装默认将配置保存在 `%LOCALAPPDATA%\HomeDrop\data`。
- 卸载程序保留照片、配置和备份索引。

## 校验

请同时下载 `.sha256` 文件，并确认安装器哈希与本版本 Release 一致。
