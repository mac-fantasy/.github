<p align="center">
  <img src="https://raw.githubusercontent.com/mac-fantasy/.github/main/profile/assets/banner.svg" alt="Mac Fantasy — Small tools. A better Mac." width="100%">
</p>

<p align="center">
  <strong>让日常使用 Mac 的小事，变得更顺手。</strong><br>
  Native macOS utilities for your clipboard, connected devices, system insights, and account usage.
</p>

<p align="center">
  <a href="https://github.com/mac-fantasy/homebrew-tap#应用与安装">安装应用</a> ·
  <a href="https://github.com/orgs/mac-fantasy/repositories">浏览源码</a> ·
  <a href="#反馈与参与">反馈与参与</a>
</p>

## 小工具，各司其职

Mac Fantasy 是一组开源桌面工具，围绕 macOS 原生体验开发。我们把常用功能放在菜单栏：找回刚才复制的内容、看清接入的设备、观察系统负载，或快速查看账号用量。

| 应用 | 帮你做什么 | macOS 兼容性 |
| :--- | :--- | :--- |
| **[ClipBar](https://github.com/mac-fantasy/ClipBar)**<br>[下载最新版 →](https://github.com/mac-fantasy/ClipBar/releases/latest) | 找回复制过的文本、图片和文件记录；从菜单栏重新复制，继续粘贴。 | 13+<br>Apple Silicon / Intel |
| **[iPorts](https://github.com/mac-fantasy/iPorts)**<br>[下载最新版 →](https://github.com/mac-fantasy/iPorts/releases/latest) | 查看 USB、雷雳、显示器、磁盘与网络等连接信息，了解设备状态并安全推出磁盘。 | 14+<br>Apple Silicon / Intel |
| **[Mac Monitor](https://github.com/mac-fantasy/mac-monitor)**<br>[下载最新版 →](https://github.com/mac-fantasy/mac-monitor/releases/latest) | 观察 CPU、GPU、内存与进程占用，快速找到正在消耗资源的应用。 | 14+<br>Apple Silicon |
| **[Krill Desktop](https://github.com/mac-fantasy/krill-desktop)**<br>[下载最新版 →](https://github.com/mac-fantasy/krill-desktop/releases/latest) | 查看 Krill 个人账号的套餐、余额和用量；也提供原生 Windows 客户端。 | 14+<br>Apple Silicon / Intel |

## 通过 Homebrew 安装

选择需要的应用，复制对应的一行即可：

```bash
brew install --cask mac-fantasy/tap/clipbar
brew install --cask mac-fantasy/tap/iports
brew install --cask mac-fantasy/tap/mac-monitor     # 仅 Apple Silicon
brew install --cask mac-fantasy/tap/krill-desktop
```

安装包由各项目的 GitHub Releases 发布，统一的 **[Homebrew tap](https://github.com/mac-fantasy/homebrew-tap)** 每 6 小时检查稳定版并校验安装包。更新、卸载、旧 tap 迁移和首次打开说明，均可在 tap 文档中查看。

不使用 Homebrew？点击上表中的「下载最新版」手动安装。Krill Desktop 的 Windows 安装包也在对应 Release 中提供。

> 当前 macOS 发行包尚未进行 Apple Developer ID 签名和公证。首次打开可能需要按「系统设置 → 隐私与安全性」的提示允许打开，具体见各项目说明。

## 我们关注的体验

- **原生交互**：macOS 应用使用 Swift、AppKit 和 SwiftUI，适配菜单栏与系统外观。
- **清楚的数据**：设备和系统指标以实际可读取的数据为准，无法取得时明确说明。
- **开放的维护**：源码、问题追踪与发布记录均在 GitHub，安装入口统一维护。

## 反馈与参与

发现问题或有新想法，欢迎到对应项目提交 Issue；复现步骤、系统版本和芯片型号会帮助我们定位问题。也欢迎通过 Pull Request 改进代码、文档和翻译。

[ClipBar Issues](https://github.com/mac-fantasy/ClipBar/issues) · [iPorts Issues](https://github.com/mac-fantasy/iPorts/issues) · [Mac Monitor Issues](https://github.com/mac-fantasy/mac-monitor/issues) · [Krill Desktop Issues](https://github.com/mac-fantasy/krill-desktop/issues)

---

<p align="center"><sub>Small tools. A better Mac.</sub></p>
