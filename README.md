# Lumen · 聊天与记忆

一个纯静态的单页 AI 聊天应用，带自己的长期记忆库。放在 GitHub Pages 上直接跑。

- **聊天**：流式回答，支持任何 OpenAI 兼容接口（默认 DeepSeek）。
- **记忆**：事实库 + 用户档案 + 最近事件，每次对话自动带上；点「记住这条」让模型提炼事实。
- **备份**：一键导出 JSON / facts.md，可以提交回本仓库的 `memory/` 目录，换设备继续用。

## 用法

1. 打开 https://ysepec.github.io/kb/
2. 「设置」里填 API Key（只存浏览器 localStorage，不会上传，也不会进仓库）
3. 开聊

## 记忆文件

- `memory/facts.md` — 种子事实，首次打开自动导入
- `memory/profile.md` — 用户档案

## 隐私

纯前端，没有后端。API Key 不出设备；这个仓库是公开的，别把 Key 提交进来。
