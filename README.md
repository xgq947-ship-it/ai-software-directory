# AI Software Directory

这是一个用于整理 AI 相关软件、开发工具、远程控制、截图贴图和必要基础工具下载入口的资料库。

原则很简单：只收官方入口，不上传安装包，不收第三方网盘，不写容易失效的安装包直链。

## 快速入口

| 名称 | 类型 | 官方下载 / 安装入口 | 备注 |
| --- | --- | --- | --- |
| ChatGPT Desktop | AI 客户端 | https://chatgpt.com/features/desktop/ | OpenAI 官方桌面应用 |
| Claude Desktop | AI 客户端 | https://claude.ai/download | Anthropic 官方桌面应用 |
| Claude Code | AI 编程 Agent | https://claude.com/product/claude-code | Claude 官方编程工具 |
| OpenAI Codex CLI | AI 编程 Agent | https://developers.openai.com/codex/cli | OpenAI 官方 CLI |
| OpenCode | AI 编程 Agent | https://opencode.ai/download | 开源 AI 编程 Agent |
| ZCode | AI 编程 Agent | https://zcode.z.ai/en | Z.AI 官方工具 |
| Hermes Agent | AI Agent Runtime | https://hermes-agent.nousresearch.com/ | Nous Research 官方 Agent |
| Cursor | AI IDE | https://cursor.com/download | AI 代码编辑器 |
| Zed | AI IDE | https://zed.dev/download | 高性能代码编辑器，支持 AI Agent |
| Ollama | 本地模型运行 | https://ollama.com/download | 本地运行大模型 |
| LM Studio | 本地模型运行 | https://lmstudio.ai/download | 图形化本地模型工具 |
| UU 远程 | 远程控制 | https://uuyc.163.com/download/ | 网易官方远程控制工具 |
| Snipaste | 截图贴图工具 | https://www.snipaste.com/download.html | 官方下载页，覆盖 Windows/macOS/Linux |
| Vorssaint | macOS 实用工具 | https://github.com/vorssaint/vorssaint-utils/releases | 菜单栏工具箱，支持 Homebrew Cask 安装 |
| Hamibot | Android 自动化 | https://hamibot.com/download/ | 官方 APK 下载页 |
| AutoX.js | Android 自动化 | https://github.com/autox-community/AutoX/releases | APK 从 GitHub Release 下载 |
| cmux | 开发终端 | https://cmux.com/ | 面向 AI Coding Agent 的 macOS 终端 |
| CC Switch | AI CLI 管理 | https://ccswitch.io/zh/ | Claude Code、Codex、OpenCode 等 CLI 统一管理 |
| Clash Verge Rev | 网络基础工具 | https://github.com/clash-verge-rev/clash-verge-rev/releases | 只用官方 GitHub Release |
| Tailscale | 网络基础工具 | https://tailscale.com/download | 跨平台组网和远程访问工具，官方页覆盖 macOS/iOS/Windows/Linux/Android |

## 目录结构

```text
ai-software-directory/
├── README.md
├── data/
│   ├── software.yaml
│   ├── categories.yaml
│   └── vendors.yaml
├── docs/
│   ├── ai-coding.md
│   ├── android-automation.md
│   ├── desktop-chat.md
│   ├── developer-workstation.md
│   ├── local-llm-runtime.md
│   ├── macos-utilities.md
│   ├── network-tools.md
│   └── maintenance.md
├── templates/
│   └── software-entry.md
└── .github/
    └── workflows/
        └── link-check.yml
```

## 维护规则

- 优先记录下载页、安装文档、GitHub Release，不记录临时直链。
- 每条记录必须有 `last_checked`。
- 只收普通用户可安装的软件客户端、APK、插件、CLI 或官方安装入口。
- 安装包只从官方域名、官方 GitHub、官方应用商店下载。
- 代理、网络类工具只作为开发基础设施收录，不收订阅、不收节点。

完整数据在 `data/software.yaml`。
