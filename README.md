# 小红书爆款笔记 AI Agent 🚀

基于 Hermes Agent 框架构建的多 Agent 内容生成系统，专注于小红书爆款笔记自动化创作。

## ✨ 项目亮点

- 多 Agent 协作（意图解析 / 策略生成 / 合规检测 / 视觉生成）
- 支持长链推理（Multi-step Reasoning）
- RAG + 爆款内容知识库
- 自动标题优化 & 标签策略
- 飞书机器人集成
- 自我进化反馈机制（基于用户行为 & 内容表现）

---

## 🧠 系统架构

```
用户输入（飞书）
      ↓
意图解析 Agent
      ↓
策略 Agent（标题 + 内容结构）
      ↓
视觉 & 合规 Agent
      ↓
内容生成输出
      ↓
反馈 Agent（持续优化）
```

---

## 🚀 快速开始

```bash
git clone https://github.com/yourname/xiaohongshu-ai-agent
cd xiaohongshu-ai-agent
pip install -r requirements.txt
python main.py
```

---

## 🧩 示例输入

```
帮我写一篇探店笔记，周末去的安福路韩系咖啡馆
```

---

## 📈 能力展示

- 自动生成 3 个高点击标题
- 输出完整笔记（含结构化内容）
- 推荐标签组合（流量词 + 精准词）
- 合规改写（避免违规）

---

## 🔁 自我进化机制

系统会基于以下数据持续优化：

- 用户修改行为
- 内容点击率 / 收藏率
- 平台规则变化

---

## 🛠 技术栈

- LLM（OpenAI / Claude / DeepSeek）
- Hermes Agent Framework
- LangChain / 自定义调度器
- 向量数据库（FAISS / Weaviate）
- 飞书 Bot API

---

## 📌 未来计划

- 接入实时热点抓取（Trending Agent）
- 多平台扩展（抖音 / B站）
- A/B 标题自动测试

---

## 📄 License

MIT
