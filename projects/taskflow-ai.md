# TaskFlow AI — 智能任务调度系统

**TaskFlow AI** 是一个基于 React + LLM 的自动化任务调度工具，专为追求高效工作流的开发者与团队设计。

## 核心特性

### 🧠 自然语言解析
支持自然语言描述任务，LLM 自动提取时间、优先级、依赖关系等关键信息。

```
"明天下午3点前完成API文档，优先级高"
→ 自动解析为：任务+截止时间+优先级
```

### 📊 甘特图可视化
基于 D3.js 构建的交互式甘特图，支持拖拽调整时间、依赖连线、关键路径高亮。

### 🔔 智能提醒
根据任务优先级和截止时间，自动计算最佳提醒时机，支持邮件、Slack、钉钉多渠道推送。

## 技术架构

- **前端**: React 18 + TypeScript + Tailwind CSS
- **后端**: Node.js (Express) + PostgreSQL
- **AI 引擎**: OpenAI GPT-4 API + 自定义 Prompt 工程
- **部署**: Vercel (前端) + Railway (后端)

## 学习收获

1. **Prompt Engineering 实践**: 学会了如何设计结构化 Prompt 来保证 LLM 输出的稳定性和准确性。
2. **状态管理**: 使用 Zustand 替代 Redux，体验了轻量级状态管理方案的简洁与高效。
3. **拖拽交互**: 实现了复杂的甘特图拖拽逻辑，对 D3.js 的交互事件有了深入理解。

## 链接

- [GitHub 仓库](https://github.com/Fuyh314/taskflow-ai)
- [在线演示](https://taskflow-ai.vercel.app)