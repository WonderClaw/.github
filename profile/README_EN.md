# ClawCV — WonderCV AI Agent 💼✨

[简体中文](./README.md) | [English](./README_EN.md)

> **ClawCV** is the official suite of AI Career Skills from [WonderCV](https://www.wondercv.com). Powered by **MCP (Model Context Protocol)**, it transforms your AI Agents (Claude Code, Cursor, Windsurf) into elite career development experts.

[![License: MIT](https://img.shields.io/badge/License-MIT-orange.svg)](https://opensource.org/licenses/MIT)
[![Node.js: 18+](https://img.shields.io/badge/Node.js-18%2B-green.svg)](https://nodejs.org/)
[![Protocol: MCP](https://img.shields.io/badge/Protocol-MCP-blue.svg)](https://modelcontextprotocol.io/)
[![GitHub stars](https://img.shields.io/github/stars/WonderClaw/clawcv?style=social)](https://github.com/WonderClaw/clawcv)

---

## 🚀 Core Repositories

- **[clawcv](https://github.com/WonderClaw/clawcv)** : 📥 **User Guide & Integration Manual**. If you want to use ClawCV in your own AI tools, start here.
- **[clawcv-skills](https://github.com/WonderClaw/clawcv-skills)** : 🛠️ **Core MCP Server Implementation**. The underlying logic for resume analysis, rewriting, matching, and PDF exporting.

---

## 🚀 Core Skills

| Skill | Description |
| :--- | :--- |
| **Analyze Resume** | Professional 5-dimension scoring (Clarity, Relevance, Impact, Structure, Completeness) to identify issues. |
| **Smart Rewrite** | Rewrite work experiences into high-impact expressions (STAR method) based on 1.6M words of industry data. |
| **Job Matching** | Deep evaluation against JDs, identifying key gaps and core keywords for ATS optimization. |
| **One-Page PDF** | Automatically organize and export HR-recommended one-page PDFs with 4 professional templates. |
| **AI Mentor** | 8 career modules including Interview Q&A, Career Planning, Salary Negotiation, and Multi-version Resumes. |

---

## 📦 Quick Start

Activate **ClawCV** in your AI tools with just a few steps.

### 1. Install
```bash
npm install -g clawcv
```

### 2. Configure
Add to **Claude Code** (`~/.claude/settings.json`) or **Cursor** (MCP Settings):
```json
{
  "mcpServers": {
    "clawcv": {
      "command": "clawcv"
    }
  }
}
```

### 3. Usage
Just ask your AI:
- *"Analyze this resume and tell me what's wrong."*
- *"Rewrite my work experience to sound more like a Product Manager."*
- *"Export this resume as a one-page PDF."*

---

## 🔗 Ecosystem

- **[clawcv](https://github.com/WonderClaw/clawcv)** — User Manual & Quick Start Guide
- **[clawcv-skills](https://github.com/WonderClaw/clawcv-skills)** — Core MCP Server implementation
- **[Official Website](https://www.wondercv.com/claw)** — Get Pioneer benefits and full services

---

## 🌟 Pioneer Program

The first 100 users to link their WonderCV account become **Pioneers** and enjoy:
- 20 deep analyses + 10 smart rewrites per day.
- Access to one-page PDF generation.
- Benefits active until the product officially starts charging (est. 3-6 months).

Just say **"I want to link my account"** to your AI to start.

---

© 2026 [WonderCV](https://www.wondercv.com) - Professional Resume Builder Platform
