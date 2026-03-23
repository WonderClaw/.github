# ClawCV — WonderCV AI Agent 💼✨

[简体中文](./README.md) | [English](./README_EN.md)

> **ClawCV** 是 [超级简历 WonderCV](https://www.wondercv.com) 官方推出的 AI 求职技能集 (AI Skills)。基于 **MCP (Model Context Protocol)** 协议，让你的 AI Agent (Claude Code, Cursor, Windsurf) 瞬间变身顶级职业发展专家。

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://opensource.org/licenses/MIT)
[![Node.js: 18+](https://img.shields.io/badge/Node.js-18%2B-green.svg)](https://nodejs.org/)
[![Protocol: MCP](https://img.shields.io/badge/Protocol-MCP-blue.svg)](https://modelcontextprotocol.io/)
[![GitHub stars](https://img.shields.io/github/stars/WonderClaw/clawcv?style=social)](https://github.com/WonderClaw/clawcv)

---

## 🚀 核心仓库 (Core Repositories)

- **[clawcv](https://github.com/WonderClaw/clawcv)** : 📥 **用户入口与集成指南**。如果你想在自己的 AI 工具中使用 ClawCV，请从这里开始。
- **[clawcv-skills](https://github.com/WonderClaw/clawcv-skills)** : 🛠️ **MCP Server 核心实现**。简历分析、改写、匹配、PDF 导出的底层逻辑。

---

## 🚀 核心功能 (Core Skills)

| 技能 | 说明 |
| :--- | :--- |
| **简历分析 (Analyze)** | 5 维度专业评分（完整度/清晰度/匹配度/成果感/结构），精准识别问题 |
| **智能改写 (Rewrite)** | 基于 160 万字行业语料库，将经历改写为高竞争力表达 (STAR 法则) |
| **岗位匹配 (Match)** | 对照 JD 深度评估，识别关键差距与核心关键词 (ATS 优化) |
| **一页纸 PDF (Export)** | 自动整理并导出 HR 推荐格式的一页纸 PDF，支持 4 种专业模板 |
| **AI 导师 (Mentor)** | 涵盖面试问题、求职规划、薪资谈判、多版本简历等 8 大求职模块 |

---

## 📦 快速开始 (Quick Start)

只需一行命令，即可在你的 AI 工具中激活 **ClawCV**。

### 1. 安装 (Install)
```bash
npm install -g clawcv
```

### 2. 配置 (Configure)
在 **Claude Code** (`~/.claude/settings.json`) 或 **Cursor** (MCP Settings) 中添加：
```json
{
  "mcpServers": {
    "clawcv": {
      "command": "clawcv"
    }
  }
}
```

### 3. 使用 (Usage)
直接在对话中输入需求：
- *"帮我分析这份简历哪里有问题？"*
- *"把我的工作经历改得更像产品经理"*
- *"导出这份简历为一页纸 PDF"*

---

## 🔗 生态链接 (Ecosystem)

- **[clawcv](https://github.com/WonderClaw/clawcv)** — 用户手册与快速入门指南 (User Guide)
- **[clawcv-skills](https://github.com/WonderClaw/clawcv-skills)** — MCP Server 核心实现 (Core implementation)
- **[Official Website](https://www.wondercv.com/claw)** — 获取 Pioneer 权益与完整服务

---

## 🌟 Pioneer 计划 (Pioneer Program)

前 100 名绑定 WonderCV 账号的用户可成为 **Pioneer**，享受：
- 每日 20 次深度分析 + 10 次智能改写
- 解锁一页纸 PDF 生成功能
- 权益持续到产品正式收费（预计 3-6 个月）

在对话中对 AI 说 **"我要绑定账号"** 即可开始。

---

© 2026 [超级简历 WonderCV](https://www.wondercv.com) - 专业求职简历制作平台
