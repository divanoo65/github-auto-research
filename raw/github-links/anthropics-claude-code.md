# anthropics/claude-code

**GitHub**: https://github.com/anthropics/claude-code

## 项目简介

Claude Code 是 Anthropic 开发的 AI 编程助手 CLI 工具。它运行在终端中，能理解整个代码库上下文，通过自然语言帮助开发者完成编码任务。

## 核心能力

- **代码生成与修改**：理解需求，直接编辑文件
- **Bug 修复**：定位问题根因，给出修复方案
- **代码解释**：解释复杂逻辑和架构设计
- **Git 工作流**：自动化 commit、PR 创建等操作
- **测试编写**：生成单元测试和集成测试

## 技术架构

- 基于 Claude Sonnet/Opus 大模型
- 工具调用（Tool Use）：Read、Edit、Bash、Write 等原子操作
- 上下文管理：自动压缩长对话，保持工作连续性
- 权限系统：细粒度控制允许执行的操作类型

## 适用场景

- 大型代码库的重构和功能开发
- 代码审查和安全扫描
- 学习新技术栈时快速上手
- 自动化重复性编程任务

## 数据

- Stars: 123k+
- Language: Shell/TypeScript
- License: MIT

