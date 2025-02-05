# Cursor：基于 GPT-4 的智能代码生成工具使用指南

## 简介

`Cursor` 是一款基于人工智能技术的代码生成工具，利用先进的自然语言处理和深度学习算法，能够根据用户的输入或需求，自动生成高质量代码。无论是编程初学者，还是资深开发者，`Cursor` 都能成为编程路上的得力助手。

它支持多种编程语言，包括 `Python`、`Java`、`C#`、`JavaScript` 等，并兼容 `Mac`、`Windows`、`Linux` 等主流操作系统。

![Cursor 工具界面](https://bbtdd.com/img/659013156630.webp)

> **官网原话：**  
> Built to make you extraordinarily productive, Cursor is the best way to code with AI.  
> Cursor 旨在提高您的工作效率，是使用 AI 进行编码的最佳方式。

**摘要：**  
本文详细介绍 `Cursor` 这一基于 AI 技术的代码生成工具，涵盖其特点（支持多语言、多系统运行）及使用教程，包括下载、初始化配置、插件设置、模型配置和使用方法等步骤。

👉 [WildCard | 一分钟注册，轻松订阅海外线上服务](https://bbtdd.com/WildCard)

## 实现步骤

### 1. 下载与安装

1. 访问官网，点击 `Download` 下载与系统对应的版本。
2. 下载完成后找到 `Cursor Setup 0.40.4 - Build 2409052yfcjagw2-x64.exe` 文件，双击运行安装。

![下载界面](https://bbtdd.com/img/223029977.webp)

### 2. 初始化配置

#### 2.1 配置快捷键与 AI 语言

- **Keyboard：** 根据常用编辑器选择快捷键，例如选择 JetBrains 风格。
- **Language for AI：** 为 AI 指定非英语语言，如中文。
- **Codebase-wide：** 默认启用，为代码库范围问题计算嵌入。

![快捷键配置](https://bbtdd.com/img/390726201827643.webp)

#### 2.2 导入 VS Code 扩展

- 选择 `Use Extensions` 导入现有扩展，或选择 `Start from Scratch` 从零开始。

![导入扩展](https://bbtdd.com/img/3566661297639.webp)

#### 2.3 数据偏好设置

- **Help improve Cursor：** 允许收集使用数据（如聊天问题、代码片段）。
- **Privacy Mode：** 不存储任何问题和代码。
- 选择后点击 `Continue`。

![数据偏好设置](https://bbtdd.com/img/64015260278125.webp)

#### 2.4 登录/注册

- 必须登录才能使用 AI 功能，可选择 `Skip for now` 跳过。
- 点击 `Log In` 登录，支持 GitHub 账号登录。

![登录界面](https://bbtdd.com/img/206121178351547.webp)

### 3. 插件配置

#### 3.1 设置 Cursor 中文界面

- 快捷键 `Ctrl + Shift + X` 打开插件市场，搜索并安装 `Chinese (Simplified)` 插件。

![中文插件安装](https://bbtdd.com/img/7023039136.webp)

#### 3.2 Gitee 配置

- 安装 `Gitee` 插件并申请 `私人令牌`（access token）。
- 按 `F1` 输入 `Gitee` 命令前缀，从搜索结果中选择执行命令。

![Gitee 配置](https://bbtdd.com/img/993319373644779.webp)

### 4. 模型与密钥配置

#### 4.1 选择模型

- 点击右上角设置图标，选择 `Models` 选项进入配置界面，选择需使用的模型。

![模型选择](https://bbtdd.com/img/94758103680.webp)

#### 4.2 配置密钥

- 输入自己的 `API Key` 和 `URL`。
- 点击 `Override OpenAI Base URL` 填写自定义 URL。

![密钥配置](https://bbtdd.com/img/270582185057.webp)

#### 4.3 自定义模型

- 点击 `Add model` 填写模型名称，配置自定义模型。

![自定义模型](https://bbtdd.com/img/90300990976.webp)

#### 4.4 测试配置

- 配置完成后点击 `Verify` 测试，若无提示则表示成功。

![测试配置](https://bbtdd.com/img/24183255.webp)

### 5. 使用指南

#### 5.1 打开提示词面板

- 通过快捷键或界面按钮打开提示词面板，输入需求生成代码。

![提示词面板](https://bbtdd.com/img/72122864528442.webp)