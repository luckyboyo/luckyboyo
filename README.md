<p align="center">
  <img src="https://raw.githubusercontent.com/luckyboyo/luckyboyo/main/assets/header.svg" width="100%" alt="Fang Ziyue — AI Agents · RAG · AI Engineering" />
</p>

<p align="center">
  <strong>你好，我是方子悦 👋</strong><br />
  <sub>探索智能体与知识检索，把想法做成可运行、可验证的 AI 应用。</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HKU-Robotics_%26_Intelligent_Systems-2563EB?style=for-the-badge" alt="香港大学 · 机器人与智能系统" />
  <a href="https://github.com/luckyboyo/resume-site"><img src="https://img.shields.io/badge/Portfolio-My_Work-0D9488?style=for-the-badge&logo=github&logoColor=white" alt="个人简历与项目作品集" /></a>
</p>

---

## 👋 About me

我是 **方子悦（Fang Ziyue）**，目前在香港大学攻读**机器人与智能系统硕士**，本科毕业于合肥工业大学电子信息工程专业。

我的兴趣是 **AI Agents、检索增强生成（RAG）与 AI 应用工程化**。我喜欢把复杂任务拆成清晰的工作流，也关注模型接入之后的检索质量、状态管理、执行验证和使用体验。

- 🤖 **多智能体协作**：用 LangGraph 串联代码探索、编写、评审与测试。
- 📚 **知识库问答**：探索混合检索、查询理解、上下文组织与回答质量评估。
- 🛠️ **工程实践**：让原型具备清晰的结构、可复现的部署方式和可追踪的执行过程。

## 🧰 Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=python,cpp,ts,react,nextjs,postgres,redis,docker,git,linux&perline=5" alt="Python, C++, TypeScript, React, Next.js, PostgreSQL, Redis, Docker, Git, Linux" />
</p>

<p align="center">
  <strong>AI &amp; Retrieval</strong><br />
  <code>LangGraph</code> · <code>LangChain</code> · <code>RAG</code> · <code>pgvector</code> · <code>RAGAS</code><br /><br />
  <strong>Application &amp; Tooling</strong><br />
  <code>Streamlit</code> · <code>Flask</code> · <code>Docker Compose</code> · <code>ROS 2</code>
</p>

## ✨ Selected projects

### 🤖 [Code Agent · 多智能体软件工程助手](https://github.com/luckyboyo/Code_agent)

围绕一个编程任务，让多个职责明确的 Agent 协作完成**理解 → 编写 → 评审 → 验证**。

- **Supervisor** 拆解任务并调度 Explorer、Coder、Reviewer、Executor。
- 通过 Coder–Reviewer 反馈回路迭代代码，由 Executor 运行测试验证。
- 使用 Redis 保存会话检查点，以 PostgreSQL 记录操作审计日志。

`Python` `LangGraph` `LangChain` `Redis` `PostgreSQL`

### 📚 [RAG · 本地知识库问答系统](https://github.com/luckyboyo/RAG)

从文档入库到流式回答，构建一条包含检索、生成与评估的知识库问答链路。

- **关键词 + 语义向量双路召回**，结合 RRF 融合排序与 Dynamic Top-K。
- 通过查询重写、问题拆分与 Parent–Child 分块组织回答上下文。
- 用 Streamlit 提供交互界面，结合 LLM-as-Judge 与 RAGAS 评估质量。

`Python` `pgvector` `bge-m3` `Streamlit` `Docker Compose` `RAGAS`

### 🌐 [Resume Site · 个人简历与作品集](https://github.com/luckyboyo/resume-site)

以简洁的页面呈现教育背景、技术经历和项目实践，使用 Next.js、TypeScript 与 Tailwind CSS 构建，支持静态导出部署。

`Next.js` `React` `TypeScript` `Tailwind CSS`

---

<p align="center">
  <strong>Learn by building. Improve by iterating.</strong><br />
  <sub>欢迎浏览我的项目，也欢迎通过项目 Issues 交流实现思路与改进建议。</sub><br /><br />
  <a href="https://github.com/luckyboyo?tab=repositories">查看全部仓库 ↗</a>
</p>
