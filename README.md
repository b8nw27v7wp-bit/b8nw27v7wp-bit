# 👋 Hi, I'm Yu

计算机科学与技术本科生，专注于 **全栈开发** 和 **AI 工具链**。

喜欢做有实际用户价值的工具类产品，从需求到上线全流程独立完成。

## 🛠️ Tech Stack

`TypeScript` `React` `Next.js` `Node.js` `Java` `MySQL` `Docker` `微信小程序` `Git`

## 🚀 Featured Projects

### 🌐 [GitHub-ZH-Plugin](https://github.com/b8nw27v7wp-bit/GitHub-ZH-Plugin)

> GitHub 界面中文化油猴脚本 — 轻量 · 实时 · 智能

- 覆盖 **29 种页面类型**，**1080+ 词条**，支持正则动态翻译
- MutationObserver 监听 DOM，动态内容实时翻译；适配 GitHub Turbo SPA 无刷新切换
- 仓库描述一键翻译、未命中词条收集导出、深色模式适配、页面标题翻译
- 智能跳过代码块/搜索框/昵称/文件名，防误翻；textContent 写入杜绝 XSS
- **103 项自动化测试**全通过（GitHub Actions CI），零依赖开箱即用
- 技术栈：`JavaScript` `Tampermonkey` `Vue` `正则表达式` `MutationObserver`

### 🏋️ [铁馆日志 Gym Tracker](https://github.com/b8nw27v7wp-bit/gym-tracker-backup)

> 微信小程序：专业健身训练记录工具 — 纯本地存储 · 零成本部署

- 记录训练动作/组数/重量/次数，自动计算**训练容量（Volume）与 PR**，生成周容量趋势、训练热力图与部位分布统计
- 内置 **278 个动作**专业动作库、**43 篇**健身知识文章、**5 套**训练计划模板（17 个训练日），支持自建计划
- 渐进超负荷智能建议、1RM 趋势预测、减量周检测、肌肉恢复建议、连续打卡与 9 枚成就徽章
- 超级组 / 递减组 / Tabata 计时器 / 组间休息提醒 / kg-lb 单位全局换算
- **纯前端 + 本地存储**：无后端、无域名、零成本，个人主体可直接上线
- **767 项测试**全通过，16 个专项验证脚本覆盖极端场景与安全审计
- 技术栈：`微信小程序` `JavaScript` `本地存储` `容量追踪算法`

### 🎓 [codingagent](https://github.com/b8nw27v7wp-bit/codingagent)

> AI 编程教学助手 — 面向编程初学者的智能辅导系统

- 苏格拉底式引导教学，5 级渐进提示策略，让学生自己学会编程而非直接给答案
- **3 门交互式课程**（Python 基础 / JavaScript 基础 / 算法入门），代码沙箱实时运行
- Monaco Editor 在线练习 + 代码自动评测（测试用例 + AI Review）
- AI 对话式辅导，根据学习进度自适应调整；学习数据看板可视化进度
- NextAuth 登录 + MySQL 进度同步，Docker 一键部署，**64 项测试**全通过
- 技术栈：`Next.js` `React` `MySQL` `NextAuth` `Docker` `DeepSeek`

### 🔧 [repo-ai-cli](https://github.com/b8nw27v7wp-bit/repo-ai-cli)

> AI 驱动的仓库助手 CLI — npm 包 `repo-ai-cli`，21 条命令覆盖仓库全流程

- **AI 工作流**：双语 README、Conventional Commits、CHANGELOG、代码审查、代码解释、PR 描述、文档翻译、单元测试、重构建议、bug 定位、代码库问答（RAG）
- **离线工具集**：密钥扫描、环境体检、.gitignore / LICENSE 生成、仓库统计、依赖解析、项目脚手架、git 钩子安装、语义化版本发布
- BYOK 模式，支持 **8+ 家 LLM 提供商**（DeepSeek / OpenAI / Kimi / GLM / 通义千问 / MiniMax / Grok / 硅基流动）及任意 OpenAI 兼容端点，Key 不上传
- 智能 Token 预算、流式输出、`--json` 脚本友好；**173 项测试**全通过（GitHub Actions CI）
- 技术栈：`TypeScript` `Node.js` `CLI` `commander` `clack`

### 🤖 [AgentOrb](https://github.com/b8nw27v7wp-bit/agent-orchestrator)

> 多 Agent 编排 CLI —— 统一调度本机多个 AI agent

- 一条命令让 CodeBuddy / Codex / Claude Code **并行执行**同一任务，输出结果对比表
- 支持任务分发、轮询分配、超时终止、JSON 结构化输出
- 零外部运行时依赖（仅 commander），TypeScript strict 模式
- **15 项测试**全通过（Node.js 内置测试框架，零测试依赖）
- 技术栈：`TypeScript` `Node.js` `CLI` `子进程编排`

---

> 💡 *Building tools that people actually use.*