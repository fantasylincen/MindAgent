# MindAgent 🧠🤖

> **An AI-powered IDE that builds software using a swarm of micro-agents based on an immutable mindmap contract.**
> 
> 基于不可变思维导图契约与微型 Agent 军团构建软件的 AI 驱动开发 IDE。

---

## 💡 项目愿景 (The Vision)

传统的 AI 编码工具（如 Copilot、Cursor）通常依赖扩大上下文窗口来理解整个项目，这会导致 AI 随着代码量增加而出现严重的**“上下文迷失”和“代码幻觉”**。

**MindAgent 提出了一个全新的 AI 领域微服务软件工程方法论：**
我们通过**“思维导图”将复杂的软件系统无限拆解**，直到每个最底层叶子节点的工作量压缩在 **128KB 内部文件**以内。同时，将思维导图的树状结构定义为**“绝对不可变契约”**。需求变更时禁止大改树结构，仅允许隐藏旧节点或挂载新节点（增量更新），从而构建出极高准确率、完全可预测的自动化编码与组装系统。

---

## 🛠 核心架构 (Architecture Blueprint)

目前项目正处于 **RFC (Request for Comments) 阶段**，整体架构由三种职责极度专一的微型 Agent (Micro-Agents) 矩阵与全局数据总线构成：

