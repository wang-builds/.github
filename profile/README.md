<div align="center">

# Wang Builds · 阿王写工具

**拒绝臃肿环境与订阅绑架，专注纯原生、本地优先的硬核开源工具**

*Native, local-first, zero-subscription open-source developer & creator tools.*

[![GitHub Org](https://img.shields.io/badge/GitHub-wang--builds-0f172a?style=for-the-badge&logo=github)](https://github.com/wang-builds)
[![Homebrew Tap](https://img.shields.io/badge/Homebrew-wang--builds%2Ftap-fbb040?style=for-the-badge&logo=homebrew&logoColor=white)](https://github.com/wang-builds/homebrew-tap)
[![License: MIT](https://img.shields.io/badge/Open_Source-MIT-10b981?style=for-the-badge)](https://github.com/wang-builds/cutword)

</div>

---

## 旗舰开源项目

### ✂️ [CutWord · 剪字](https://github.com/wang-builds/cutword) — 像删 Word 文档一样剪口播视频（macOS 14+ 原生）

- **极致轻量离线**：纯 Swift 6.2 调用系统内置离线语音引擎与 `AVFoundation` / `VideoToolbox`，**整个 `.dmg` 仅 `2.2 MB`**，0 Python、0 模型下载、0 API Key、断网即用，全面兼容 **macOS 14 / 15 / 26+**。
- **声学 + 语义自动精剪**：16kHz PCM 扫描切除冷场气口（保留 `120ms` 自然呼吸留白 + `8ms` 防爆音淡入淡出），自动划除 `嗯/啊/那个/就是说` 口癖与「说错半句……不对重来……」NG 重录废句。
- **三路零门槛导出**：一键直出 **逐字金色高亮胶囊字幕 MP4**、**纯净 MP4 + 校准 `.srt`（直拖免费版剪映 0 元套花字）** 或 **Final Cut Pro / 达芬奇 `FCPXML v1.10`**，内置 `cutword` 命令行与 AI Agent Skill。

```bash
brew install --cask --no-quarantine wang-builds/tap/cutword
```

👉 [**前往仓库查看演示与源码**](https://github.com/wang-builds/cutword) · [**直接下载 2.2 MB `.dmg` 安装包**](https://github.com/wang-builds/cutword/releases/latest)

---

## 我们的三个工程原则

1. **100% 本地优先（On-Device First）**：音视频与隐私数据全程留在本机芯片处理，不强制注册、不上传云端。
2. **零环境负担、零订阅刺客**：能用系统原生算力 `2 MB` 解决的事，绝不让用户装 `3 GB` 依赖或按月付费解锁基础功能。
3. **欢迎实测与二创分享**：所有公开项目均采用 MIT 协议，内置开箱实测样片，欢迎 **B站、抖音、小红书、YouTube** 创作者自由录屏评测或提 Issue 共建。

---

## 🤝 商务合作与企业定制开发

承接 **macOS / iOS 原生音视频工作流、批量口播自动化粗剪系统、AI Agent 本地优先工具** 企业私有化定制与商务合作：  
📬 **直联邮箱**：`a3152557994@gmail.com`（来信注明「GitHub 合作」）
