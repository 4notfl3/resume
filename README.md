<div align="center">

**AI Agent 开发工程师** · 大三在读 · 2027 年毕业 · 寻找实习机会

[![GitHub](https://img.shields.io/badge/GitHub-4notfl3-181717?style=flat-square&logo=github)](https://github.com/4notfl3)
[![Email](https://img.shields.io/badge/Email-notcam83@outlook.com-0078D4?style=flat-square&logo=microsoft-outlook)](mailto:notcam83@outlook.com)
[![Phone](https://img.shields.io/badge/Phone-17777142495-4CAF50?style=flat-square&logo=whatsapp)](tel:17777142495)

</div>

---

## 📋 目录

- [技术栈](#-技术栈)
- [项目经历](#-项目经历)
- [自我评价](#-自我评价)

---

## 🛠 技术栈

### 🤖 AI Agent 生态（核心方向）

| 类别 | 技术 |
|------|------|
| **LLM / 框架** | Python、LangChain、LangGraph、FastMCP |
| **工具调用** | ReAct、Function Calling、XML 解析 |
| **检索增强** | RAG、Ollama、ChromaDB、文档分块与向量化 |
| **Agent 架构** | MCP Server / Host 编排、WebSocket 通信、动态工具发现 |
| **工作流** | Plan-and-Execute、状态机与图结构控制 |

### 🖥 后端开发

| 语言 / 框架 | 数据库 / 构建 |
|-------------|---------------|
| Java、Spring、Spring Boot | PostgreSQL |
| Node.js、Express | Maven |
| Python（FastMCP、Flask） | RESTful API 设计 |

### 🎨 前端开发

| 框架 | 语言 |
|------|------|
| Vue、React | JavaScript、TypeScript |

### 🔧 工具链

Git、GitHub、Docker、Linux、Shell

---

## 🚀 项目经历

### 🤖 AI Agent 全栈实践

> `2026.03 - 至今` · 实验室团队项目 + 个人独立项目 · 核心开发者

一个从 LLM 调用、RAG 检索到 MCP Server 开发与 Host 编排的全链路 AI Agent 落地项目，覆盖团队协作与个人独立两种开发模式。

#### 团队项目：MCP 模块负责人（4 人团队）

| 维度 | 详情 |
|------|------|
| **角色** | MCP 模块负责人 |
| **职责** | 参与 Host 端架构设计；独立负责多个 MCP Server 的调研、开发与联调 |
| **技术栈** | `FastMCP` `WebSocket` `Python` `stdio 通信` `动态工具发现` |
| **产出** | 基于 FastMCP 实现浏览器自动化、截图 + AI 分析等多个 MCP Server，支持 stdio 通信与动态工具发现，已与 Host 侧联调通过 |

#### 个人项目：MCP 天气查询 Agent（独立完成）

| 维度 | 详情 |
|------|------|
| **描述** | 从零实现完整 MCP Agent 链路（Server + Host + LLM），打通天气查询全流程 |
| **技术栈** | `FastMCP` `Python` `HTTP` `OpenAI Function Calling` |
| **亮点** | Server 侧支持 HTTP 通信与动态工具发现；Host 侧实现多服务器并发连接、TTL 缓存与中文工具名安全映射，成功对接 OpenAI Function Calling 工具调用链路 |

#### Agent Chat 全栈应用（独立开发）

| 维度 | 详情 |
|------|------|
| **描述** | 从零实现 Agent Chat 全栈应用，涵盖 JWT 认证、SSE 流式对话、多模型切换及 MCP 广场 |
| **技术栈** | `FastAPI` `Nuxt 3` `SQLite` `SSE` `JWT` `Docker` |
| **亮点** | MCP 广场实现三级降级策略（远程 API → 缓存 → 8 个内置服务）；解决 SQLite WAL 异步并发、中文工具名 Schema 校验等工程问题 |
| **源码** | [github.com/4notfl3/AI-Agent](https://github.com/4notfl3/AI-Agent) |

#### RAG 检索增强生成系统（独立搭建）

| 维度 | 详情 |
|------|------|
| **描述** | 本地化部署的文档智能检索问答系统 |
| **技术栈** | `Ollama` `Docker` `ChromaDB` `Python` |
| **亮点** | 独立部署本地嵌入模型与向量数据库，实现文档加载 → 分块 → 向量化 → 检索 → 生成的全链路 |

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  📄 文档加载  │ ──▶ │  ✂️ 文本分块  │ ──▶ │  🧮 向量化   │
└─────────────┘     └─────────────┘     └─────────────┘
                                                 │
                                                 ▼
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│  💬 生成回答  │ ◀── │  🔍 相似检索  │ ◀── │  💾 ChromaDB │
└─────────────┘     └─────────────┘     └─────────────┘
```

---

### 🏢 人事管理系统

> `个人项目` · [GitHub 仓库](https://github.com/4notfl3/hr-nagemet)

| 维度 | 详情 |
|------|------|
| **描述** | 完整的企业人事管理系统，具备员工信息管理、部门组织架构、考勤统计等核心功能 |
| **技术栈** | `Java` `Spring` `PostgreSQL` `Maven` |
| **亮点** | 独立完成前后端全栈开发，实践了企业级 Java Web 开发标准流程 |

---

### 📦 更多项目

| 项目 | 技术栈 | 说明 |
|------|--------|------|
| [ MCP 集成](https://github.com/4notfl3) | `Python` `MCP` `SSE` `阿里云 DashScope` | MCP Client 调用高德地图 API，实现地理信息智能查询 |
| 本地学习项目合集 | `Python` `Java` `Node.js` | 多语言学习实践项目，持续整理上传中 |

---

## 💡 自我评价

- 🎯 **AI Agent 全链路能力**：从 LLM 调用、RAG 检索到 MCP Server 开发、Host 编排，具备独立落地的端到端能力。深入理解 Agent、Skill、MCP 整套架构设计。

- 🔬 **工程落地意识**：不只停留在 Demo 层面。在实际项目中解决过 SSL 证书过期、编码兼容性等生产环境问题，具备将方案推进到可用状态的能力。

- 🧩 **工作流编排深度**：熟练使用 LangGraph 实现 Plan-and-Execute 等复杂工作流，底层理解状态机与图结构的控制差异，而非停留在 API 调用层面。

- 🌐 **全栈视野**：Python / Java / Node.js 多语言开发能力，Vue / React 前端经验，可独立完成从后端 Agent 到前端演示界面的完整闭环。

- 📈 **自主学习驱动**：20 岁即掌握 AI Agent + 全栈技术栈，GitHub 有多个完整项目代码可供验证，具备根据项目需求自主研究并落地前沿方案的能力。

---

<div align="center">

### 📫 联系方式

- **GitHub**：[github.com/4notfl3](https://github.com/4notfl3)
- **Email**：notcam83@outlook.com
- **手机**：17777142495
- **意向岗位**：AI Agent 开发实习生
- **到岗时间**：随时

---

*📄 这份简历也见证了我在 AI Agent 方向上的持续投入 —— 从 ReAct 到 MCP，从 RAG 到 LangGraph，每一步都有代码可循。*

</div>
