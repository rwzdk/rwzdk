# 你好，我是 rwzdk 👋

计算机专业在读 · 全栈 / AI Agent 方向 · 用「上线的产品 + 造过的轮子 + 被合并的 PR」驱动学习

## 🔨 代表作品

| 项目 | 一句话介绍 | 技术要点 |
| --- | --- | --- |
| [Agent Workbench](https://github.com/rwzdk/agent-workbench) · [线上 Demo](https://agent-workbench.qixin-study.workers.dev) | 全栈 AI Agent 工作台：流式对话、多步工具调用可视化 | Next.js 15 · AI SDK · SSE 流式 · Function Calling 多步循环 · Cloudflare Workers + D1 · 会话认证 · CI |
| [RAG 知识库问答](https://github.com/rwzdk/rag-knowledge-base) · [线上 Demo](https://rag-knowledge-base.qixin-study.workers.dev) | 自研检索管线的 RAG 应用，零 API Key 可运行 | BM25 + 向量混合检索 · RRF 融合 · 中文 bigram 分词 · 引用溯源 · hit@3/MRR 评估进 CI |
| [mini-agents](https://github.com/rwzdk/mini-agents) | 零依赖的 TypeScript 多智能体编排库 | Agent 循环 · pipeline/supervisor 编排 · LlmClient 注入式设计 · 确定性 Mock 测试 · 事件流 |

## 🛠 技术栈

**前端** TypeScript · React 19 · Next.js 15 · Tailwind CSS
**后端** Node.js · REST · SQLite (libSQL) · Cloudflare D1
**AI** Vercel AI SDK · Function Calling · RAG 全管线 · Embeddings · 多智能体编排
**工程化** Vitest · GitHub Actions CI · 检索质量评估（hit@k / MRR）· OpenNext

## 📌 正在做

- [ ] 向 Langfuse / Novu 提交代码 PR 并合并
- [ ] mini-agents 发布 npm，agent-workbench 改用其驱动
- [ ] Agent 可观测性（trace / 工具调用延迟）与 LLM-as-judge 评估
- [ ] RAG 项目升级：PDF 解析、sqlite-vec 向量索引、检索 rerank

## 📫 联系我

邮箱：{你的邮箱} · 欢迎交流全栈与 AI Agent 开发
