<!--
Author: Lin Sen
Contact: jlinnice@163.com
GitHub: https://github.com/jinglinsen
Created: 2026-06-29
Description: Bilingual README for the global AI coding agent rules repository.

Copyright (c) 2026 Lin Sen. All rights reserved.
-->

# AI Coding Agents Rules

English | [中文](#中文说明)

## Overview

This repository contains my personal global `AGENTS.md` instructions for AI coding agents.

It defines a reusable engineering rule set for AI-assisted full-stack development. The rules are designed to help AI coding agents work in a more consistent, maintainable, secure, and verifiable way across different projects.

## What This Repository Covers

This global rule set includes guidelines for:

* Response style
* File header standards
* Scope control
* Frontend and backend boundaries
* Database safety
* Logging and debugging
* Testing and verification
* Security rules
* Dependency management
* Git hygiene
* Documentation standards
* Project-level instruction overrides

## Purpose

The goal of this repository is to make AI coding agents follow clear engineering constraints instead of producing uncontrolled, inconsistent, or hard-to-maintain code.

It is especially useful for tools such as:

* OpenAI Codex
* Claude Code
* Cursor
* Other AI coding agents that support repository-level instruction files

## Usage

Use this repository as the source of my global AI coding constraints.

For a specific project, copy `AGENTS.md` into the root directory of that project.

```text
your-project/
├── AGENTS.md
├── README.md
├── frontend/
├── backend/
└── docs/
```

If a project needs more specific rules, create or modify the project-level `AGENTS.md`.

When global rules conflict with project-level rules, the project-level rules should take priority.

## Recommended Workflow

1. Keep this repository as the global source of truth.
2. Copy `AGENTS.md` into each project that needs AI coding constraints.
3. Add project-specific technology stack, commands, directory rules, and deployment notes.
4. Let AI coding agents follow the project-level `AGENTS.md` during development.

## Repository Structure

```text
ai-coding-agents-rules/
├── AGENTS.md
├── README.md
└── LICENSE
```

## Author

Lin Sen
Contact: [jlinnice@163.com](mailto:jlinnice@163.com)
GitHub: https://github.com/jinglinsen

---

# 中文说明

[English](#ai-coding-agents-rules) | 中文

## 项目简介

本仓库用于存放我的个人全局 `AGENTS.md` 约束规范。

它是一套可复用的 AI 编码 Agent 工程规则，用于指导 AI 在不同项目中按照统一、可维护、安全、可验证的方式进行全栈开发。

## 本仓库覆盖内容

这套全局规则主要包括：

* 回复风格规范
* 文件头规范
* 任务边界控制
* 前端与后端职责边界
* 数据库安全规范
* 日志与 DEBUG 规范
* 测试与验证规范
* 安全规则
* 依赖管理
* Git 协作规范
* 文档规范
* 项目级规则覆盖机制

## 项目目的

本仓库的目标是让 AI 编码工具在开发时受到清晰的工程约束，而不是随意生成不可控、不一致、难维护的代码。

它适用于以下工具或场景：

* OpenAI Codex
* Claude Code
* Cursor
* 其他支持仓库级规则文件的 AI 编码 Agent

## 使用方式

本仓库作为我的全局 AI 编码约束源文件。

在具体项目中，可以将 `AGENTS.md` 复制到项目根目录。

```text
your-project/
├── AGENTS.md
├── README.md
├── frontend/
├── backend/
└── docs/
```

如果某个项目有更具体的技术栈、目录结构、运行命令、测试命令或部署规则，可以在项目级 `AGENTS.md` 中补充说明。

当全局规则和项目级规则冲突时，优先遵循项目级规则。

## 推荐工作流

1. 将本仓库作为全局规则源文件维护。
2. 在每个需要 AI 编码约束的项目中复制一份 `AGENTS.md`。
3. 根据具体项目补充技术栈、启动命令、目录规范、测试命令和部署说明。
4. 让 AI 编码 Agent 在开发时优先读取并遵循项目内的 `AGENTS.md`。

## 仓库结构

```text
ai-coding-agents-rules/
├── AGENTS.md
├── README.md
└── LICENSE
```

## 作者

Lin Sen
Contact: [jlinnice@163.com](mailto:jlinnice@163.com)
GitHub: https://github.com/jinglinsen

