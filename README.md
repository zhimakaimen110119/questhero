# questhero
A privacy-first, offline-ready landing page for QuestHero — transforming complex, long-cycle workflows into actionable atomic steps with built-in AI anonymized prompting.
# QuestHero Landing

> "渐渐的，你会看到你自己 —— 以及这个 QuestHero 的进步。"

QuestHero 是一个**单文件、全离线、绝对隐私**的原子级任务推进看板。它不是繁重的 Notion，也不是过于轻量化的 To-Do List。它专为贷款经纪（LO）、项目经理等需要面对长周期、多节点、强沟通 file 的专业人士打造，帮助你在错综复杂的推进过程中，永远锁定“当前下一步”。

## ✨ 核心心法

- **原子推进**：大任务拆解为最小可执行动作，一次只锁一件事。
- **隐私脱敏**：内置 AI 助手自动将真实客户隐私（姓名、地址等）转化为虚拟故事，一键生成 Wall Street brevity 风格的 Prompt，完美对接 ChatGPT/Claude。
- **客户视图**：一键生成干净的进度图与邮件草稿，让沟通走在催件前面。

## 📦 部署结构 (2-File Architecture)

本项目支持通过 GitHub Pages 进行一体化免费托管：

| 文件名 | 实际内容 | 访问路径 |
| :--- | :--- | :--- |
| `index.html` | 极简 Quiet Luxury 风格 Landing Page | `https://<your-username>.github.io/questhero-landing/` |
| `app.html` | QuestHero 核心加密应用（全离线纯前端） | `https://<your-username>.github.io/questhero-landing/app.html` |

## 🔒 隐私与安全承诺

QuestHero 没有任何后端服务器。所有数据均通过浏览器 `localStorage` 进行本地持久化存储。不上传、不收集、不分析。你的数据，100% 属于你。
