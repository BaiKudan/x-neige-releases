# X内阁桌面安装包

此仓库提供 Windows x64 安装包和自动更新清单。

[下载最新版](https://github.com/BaiKudan/x-neige-releases/releases/latest)

安装最新版后，在设置的更新页开启自动下载。程序启动后检查更新，并每隔 15 分钟再次检查。下载完成后，选择重启安装即可升级。项目、会话和设置保存在用户目录的 `.ao/ao-team` 下。

从 0.14.6 开始，可以在设置的更新通道中选择稳定版或测试版（Beta）。稳定版接收正式发布，测试版接收 Beta 和后续正式发布。刚启用测试频道时，两条频道可以同时提供当前正式版本。

已经安装较高版本的 Beta 时，切回稳定版会等待版本号追平或更高的正式版。例如 `0.14.7-beta.2` 可以更新到 `0.14.7`。

频道清单为 [latest.yml](https://raw.githubusercontent.com/BaiKudan/x-neige-releases/main/updates/latest.yml) 和 [beta.yml](https://raw.githubusercontent.com/BaiKudan/x-neige-releases/main/updates/beta.yml)。每个版本同时提供 SHA256.txt，清单使用 SHA-512 校验安装包。

当前安装器尚未配置 Windows 代码签名。macOS 与 Linux 更新渠道后续单独发布。
