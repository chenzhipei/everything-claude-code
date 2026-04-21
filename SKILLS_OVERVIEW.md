# Everything Claude Code - Skills 概览与推荐

根据 `everything-claude-code` 项目的 `skills` 目录结构，以下是核心技能（Skills）的功能点及其在不同类型项目开发中的推荐应用场景。这些技能可以作为扩展 Claude Code 能力的模块。

## 1. 前端与全栈开发 (Frontend & Full-stack)
适用于 Web 应用、SaaS 平台、交互式网站等项目。
* **`frontend-patterns`**：React、Next.js 前端开发模式，状态管理、性能优化和 UI 最佳实践。
* **`frontend-design`**：提供高质量、生产级别的前端界面和组件设计指导。
* **`nextjs-turbopack`**：针对 Next.js 16+ 和 Turbopack 的增量打包、文件系统缓存和开发加速。
* **`bun-runtime`**：使用 Bun 作为运行环境、包管理器和测试运行器的项目，提供与 Node 的迁移指南。
* **`frontend-slides`**：从零构建具有丰富动画的 HTML 演示文稿，或将 PPT 转换成 Web 格式。

## 2. 后端与接口设计 (Backend & API)
适用于服务端开发、微服务、RESTful API 架构建设。
* **`api-design`**：生产级 REST API 设计模式，涵盖资源命名、状态码、分页、过滤、错误响应和限流。
* **`backend-patterns`**：Node.js、Express 和 Next.js API 路由的后端架构模式、数据库优化和服务端最佳实践。
* **`mcp-server-patterns`**：使用 Node/TypeScript SDK 构建 MCP（Model Context Protocol）服务器的模式。

## 3. 工程化与代码质量 (Engineering & Quality)
适用于任何需要长期维护、团队协作、高质量交付的商业项目。
* **`coding-standards`**：跨项目的代码编写规范，包含命名、可读性、不可变性等基础检查。
* **`tdd-workflow`**：测试驱动开发（TDD）流程控制，强制达到 80%+ 的单元、集成和 E2E 测试覆盖率。
* **`e2e-testing`**：Playwright 端到端测试模式，包含页面对象模型 (POM)、配置、CI/CD 集成和防抖策略。
* **`security-review`**：处理鉴权、用户输入、密钥和支付等核心环节时的综合安全检查表与规范。

## 4. AI 与 Agent 工作流 (AI & Agent Workflows)
适用于大模型应用、多智能体协同、自动化任务流水线。
* **`claude-api`**：针对 Python 和 TypeScript 的 Anthropic Claude API 模式（包含 Messages API、流式处理、工具使用）。
* **`agent-introspection-debugging`**：针对 AI Agent 失败的结构化自调试工作流，包含诊断、恢复和自省报告。
* **`dmux-workflows`**：多智能体编排（使用 dmux），跨 Claude Code、Codex 等协调并行 Agent 开发工作流。
* **`eval-harness`**：基于评估驱动开发（EDD）原则的 Claude Code 会话正规评估框架。
* **`verification-loop`**：针对 Claude Code 会话的综合验证与检查系统。

## 5. 内容、媒体与社交 (Content, Media & Social)
适用于内容运营、出海营销、社交媒体自动化等业务场景。
* **`content-engine`**：为 X、LinkedIn、TikTok 等构建原生内容系统和多平台分发矩阵。
* **`article-writing`**：撰写长篇文章、指南、博客、教程和新闻通讯，保持品牌声音一致性。
* **`brand-voice`**：基于提供的示例文本构建专属写作风格，避免生成通用 AI 痕迹。
* **`crosspost`**：多平台内容分发与适配，确保不同平台的内容格式和基调最优化。
* **`fal-ai-media`**：通过 fal.ai MCP 生成图像、视频和音频（文生图、文生视频等）。
* **`video-editing`**：AI 辅助视频剪辑工作流，包含素材处理、Remotion 渲染以及后期完善。
* **`x-api`**：X/Twitter API 集成模式（发帖、读取时间线、OAuth 认证）。

## 6. 商业调研与投融资 (Business & Research)
适用于创业项目孵化、市场分析、投资尽调与融资筹备。
* **`deep-research`**：使用 firecrawl 和 exa MCP 进行多源深度研究、综合发现并提供带引用的报告。
* **`market-research`**：执行市场调研、竞品分析、行业情报收集和投资尽职调查。
* **`investor-materials`**：撰写商业计划书(Pitch Deck)、单页说明(One-pager)、财务模型和里程碑计划。
* **`investor-outreach`**：起草冷启动邮件、暖场介绍、后续跟进等针对投资人的沟通文案。

## 7. 特殊工具与架构优化
* **`product-capability`**：将 PRD（产品需求文档）或路线图转化为包含约束、不变量和接口的实施级能力计划。
* **`exa-search`**：通过 Exa MCP 提供基于神经网络的 Web、代码和企业信息搜索。
* **`documentation-lookup`**：通过 Context7 MCP 查找最新的库和框架官方文档，替代陈旧的训练数据。
* **`agent-sort`**：基于证据梳理出适合当前仓库的精简版 ECC (Everything Claude Code) 安装计划。

## 推荐配置组合
* **前端驱动的 SaaS 项目**：建议加载 `frontend-design`, `nextjs-turbopack`, `tdd-workflow`, `api-design`。
* **AI 产品及 Agent 矩阵**：建议加载 `claude-api`, `dmux-workflows`, `agent-introspection-debugging`, `mcp-server-patterns`。
* **个人出海/独立开发**：建议加载 `product-capability`, `content-engine`, `crosspost`, `market-research`，打通研发到推广的全链路。