# 知心御姐 AI 聊天网站

这是一个部署在 [Vercel](https://vercel.com) 上的 AI 聊天项目，前端采用 HTML + JS，后端使用 OpenAI GPT 模型，通过 Serverless API 与前端通信。

## 🚀 快速部署步骤

1. 将本项目上传到 GitHub
2. 登录 [vercel.com](https://vercel.com)，导入此仓库
3. 设置环境变量：
   - `OPENAI_API_KEY`：你的 OpenAI 密钥
4. 一键部署，享受知心御姐聊天体验！

## 📦 项目结构

- `/public/index.html`：聊天界面（QQ 风格）
- `/api/message.js`：调用 OpenAI 的 Serverless API
- `vercel.json`：Vercel 部署配置
