# AI Software Directory

这是一个用于整理 AI 相关软件、模型权重、开发工具和必要基础工具下载入口的资料库。

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
| Clash Verge Rev | 网络基础工具 | https://github.com/clash-verge-rev/clash-verge-rev/releases | 只用官方 GitHub Release |

## 模型权重入口

| 模型 / 系列 | 官方入口 | 备注 |
| --- | --- | --- |
| OpenAI gpt-oss | https://huggingface.co/openai/gpt-oss-120b | OpenAI 开源权重模型 |
| Meta Llama | https://developer.meta.com/ai/llama-downloads/ | Meta 官方下载页 |
| DeepSeek | https://huggingface.co/deepseek-ai | DeepSeek 官方 Hugging Face 组织 |
| Qwen | https://huggingface.co/Qwen | Qwen 官方 Hugging Face 组织 |
| Gemma | https://www.kaggle.com/models/google/gemma | Google 官方 Kaggle 模型页 |
| Mistral | https://huggingface.co/mistralai | Mistral AI 官方 Hugging Face 组织 |
| Nous Hermes | https://huggingface.co/NousResearch/Hermes-4.3-36B | Nous Research Hermes 模型 |
| xAI Grok | https://huggingface.co/xai-org/grok-2 | xAI 官方 Hugging Face 权重页 |

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
│   ├── desktop-chat.md
│   ├── local-llm-runtime.md
│   ├── model-weights.md
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
- 闭源模型不写“模型下载”，只写官方客户端、API 或安装入口。
- 安装包只从官方域名、官方 GitHub、官方应用商店下载。
- 代理、网络类工具只作为开发基础设施收录，不收订阅、不收节点。

完整数据在 `data/software.yaml`。
