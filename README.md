# River Lab

Mac 上的德州算力训练应用：八人桌、电脑对手、概率练习、自定义 AI 复盘，以及同一 Wi-Fi 下的朋友桌。

**仅使用虚拟筹码，无真实金钱交易。**

## 下载

在本仓库的 **Releases** 页面下载 `River-Lab-v1.0.0-macOS-arm64.zip`，解压后将 `River Lab.app` 拖入“应用程序”。

适用 Apple Silicon（M 系列）Mac，最低构建版本 macOS 13.5；已内置运行环境，无需安装 Node.js。

此版本未经 Apple Developer ID 签名与公证，首次打开可能被 macOS 阻止。请自行判断是否信任下载来源，不需要关闭系统安全保护。尚未验证旧版系统、Intel Mac 或 Windows。

## 使用

- **AI**：菜单「River Lab → AI 复盘设置」，填写 OpenAI 兼容接口、模型和自己的密钥。密钥仅在后台内存中；接口费用由使用者承担。
- **联机**：菜单「创建局域网房间」，分享局域网地址及房间码。朋友通过同一 Wi-Fi 的浏览器加入；最多八人，空位电脑补齐。
- **存档**：桌面单机存档独立于浏览器；联机为临时普通桌，退出 App 后结束。
- **下注**：比例按钮以跟注后底池计算额外加注，并显示最低额、取整或后手限制后的实际比例。

完整功能、已知限制和验证范围见每个 Release 的发布说明。下载后可用附带的 `SHA256SUMS.txt` 校验安装包。

## 第三方组件

应用内置 Node.js；完整许可证包含在 `River Lab.app/Contents/Resources/NODE-LICENSE.txt`。
