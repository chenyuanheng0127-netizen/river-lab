# River Lab · macOS 安装包

Mac 上的八人桌无限注德州算力训练应用：范围推理电脑对手、实时 3D 荷官与角色、本地算力与自定义 AI 复盘，以及支持**异地跨网直连与局域网自动发现**的多人联机牌桌。

**仅使用虚拟筹码，无任何真实金钱交易。**

## 下载与安装

在本仓库 [**Releases**](https://github.com/chenyuanheng0127-netizen/river-lab/releases/latest) 页面下载：

- **`River-Lab-v2.0.0-macOS-arm64.dmg`**（推荐）：双击挂载磁盘映像，将 `River Lab.app` 拖入 `Applications`（应用程序）。
- **`River-Lab-v2.0.0-macOS-arm64.zip`**：解压后将 `River Lab.app` 拖入“应用程序”。

适用 Apple Silicon（M 系列）Mac，最低系统版本 macOS 13.5；已内置 Node.js 运行时，无需安装任何外部依赖。下载后可使用同目录 `SHA256SUMS.txt` 校验文件完整性。

> **首次打开提示**：本版使用本地临时签名，未经 Apple 公证。首次打开若被 macOS 拦截，请前往 **系统设置 › 隐私与安全性**，滑到底部点击 **“仍要打开”**。

## 快速上手

- **异地与局域网联机**：菜单「River Lab → 局域网联机…（⌘L）」或顶栏「联机」一键开桌。默认自动生成**异地公网加密邀请链接与通用二维码**——即使朋友在不同城市、不同家庭宽带或使用手机 5G，也能在 `River Lab.app` 中粘贴链接或用手机直接扫码入座；同一 Wi‑Fi 下的电脑则会自动发现牌桌并一键入座。空位由电脑补齐。
- **AI 深度复盘**：首次启动或菜单「River Lab → AI 复盘设置…（⌘,）」可填写 OpenAI 兼容接口地址、模型与密钥（密钥仅驻留本机后台内存）。不填也可完整使用单机、本地算力复盘与联机。
- **存档**：单机进度保存在 App 本地存储中，首次打开会自动迁移旧版存档；退出 App 时会自动关闭房间与公网隧道。

完整改动说明见同目录 `RELEASE-NOTES-v2.0.0.md`。

## 第三方组件

应用内置 Node.js 运行时与 Cloudflare `cloudflared` 隧道客户端，完整许可证包含在 `River Lab.app/Contents/Resources/NODE-LICENSE.txt` 与 `CLOUDFLARED-LICENSE.txt`。
