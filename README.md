# HandGlass Releases

HandGlass 桌面版(arm64 macOS)发布包仓库 — [源码仓库](https://github.com/east-city-90/Handglass)。

本仓库只放安装包与更新清单(latest.json),供应用内自动更新通道轮询:

- `HandGlass_x.y.z_aarch64.dmg` — 全新安装
- `HandGlass.app.tar.gz` + `.sig` — 自动更新差量包(minisign 签名)
- `latest.json` — 更新元数据(tauri-plugin-updater 静态端点)
