# Lumen 剧场

一个纯静态的角色扮演 AI 聊天页：导入角色卡，选个主题，直接开聊。托管在 GitHub Pages。

- **角色卡**：支持 Tavern / SillyTavern / Chub 的 v2 JSON 卡片，也支持 PNG 卡片（读 PNG 里 `chara` 的 tEXt 块），可以导入、自建、导出。
- **对话**：流式回复，角色人设、性格、场景、示例对话和示例开场白都会带进提示词。
- **主题**：午夜紫 / 樱花 / 黑金，右上角 ◐ 一键切换。
- **示例角色**：`cards/dafeiyu.png`，首次打开自动导入。

## 用法

1. 打开 https://ysepec.github.io/kb/
2. 「⚙ 设置」填 API Key（OpenAI 兼容接口，默认 DeepSeek），只存在浏览器 localStorage
3. 「＋ 导入角色卡」选 JSON 或 PNG，或者点「＋」自己捏一个
4. 开聊

## 隐私

纯前端、无后端。API Key 不出设备，也不会进这个公开仓库。
