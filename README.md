<div align="center">
<img src="./website/static/img/svg/logo-text.svg" alt="icon"/>

<h1 align="center">GPT Runner</h1>

English / [简体中文](https://github.com/nicepkg/gpt-runner/tree/main/README_CN.md)

Use GPT-Runner to manage your AI presets, engage in AI-powered conversations with your code, and significantly boost the development efficiency of both you and your team!

用 GPT-Runner 管理您的 AI 预设，通过 AI 与您的代码文件聊天，极大提升您和团队的开发效率！

[![CLI][cli-image]][cli-url]
[![Web][web-image]][web-url]
[![VSCode][vscode-image]][vscode-url]
![License](https://img.shields.io/github/license/nicepkg/gpt-runner)
![GitHub stars](https://img.shields.io/github/stars/nicepkg/gpt-runner?style=social)


[CLI](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-cli/) / [Web Page](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-web/) / [VSCode Extension](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-vscode/) / [Issues](https://github.com/nicepkg/gpt-runner/issues) / [Buy Me a Coffee](https://bmc.link/jinmingyang)

[终端工具](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-cli/) / [网页版](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-web/) / [VSCode 扩展](https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-vscode/) / [反馈](https://github.com/Yidadaa/ChatGPT-Next-Web/issues) / [打赏开发者](https://github.com/nicepkg/gpt-runner/assets/35005637/98a4962a-8a2e-4177-8781-1e1ee886ecdc)

[cli-url]: https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-cli/
[cli-image]: https://img.shields.io/badge/CLI-Node.js-green?logo=node.js
[web-url]: https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-web/
[web-image]: https://img.shields.io/badge/Web-React-blue?logo=react
[vscode-url]: https://github.com/nicepkg/gpt-runner/tree/main/packages/gpt-runner-vscode/
[vscode-image]: https://img.shields.io/badge/VSCode-Extension-blue?logo=visualstudiocode

</div>

<details>
<summary>Table of Contents</summary><br>

- [Why GPT-Runner?](#why-gpt-runner)
- [Features](#features)
- [Quick Start](#quick-start)
  - [The first way: CLI](#the-first-way-cli)
  - [The second way:  VSCode Extension](#the-second-way--vscode-extension)
- [Documentation](#documentation)
- [Road map](#road-map)
- [What's New](#whats-new)
- [为什么选择 GPT-Runner？](#为什么选择-gpt-runner)
- [主要功能](#主要功能)
- [快速开始](#快速开始)
  - [方式一：CLI](#方式一cli)
  - [方式二：VSCode 扩展](#方式二vscode-扩展)
- [文档](#文档)
- [开发计划](#开发计划)
- [最新动态](#最新动态)
- [FAQ](#faq)
  - [Sponsor](#sponsor)
  - [Contributor](#contributor)
- [Acknowledgement](#acknowledgement)
- [LICENSE](#license)

<br></details>

## Why GPT-Runner?

1. **Conversations with Code Files:** 
    - Before using GPT-Runner: Manual copy and paste of multiple file codes into the ChatGPT window were required to propose features or fix bugs to AI.
    - After using GPT-Runner: Simply select your project files from the file tree. The AI will provide responses based on the most recent contents of those files.

2. **Manage the Project's AI Presets:** 
    - Before using GPT-Runner: Project prompts saved in memos needed to be copied and pasted to ChatGPT for inquiries, making it difficult to put them under git version control.
    - After using GPT-Runner: Each [xxx.gpt.md](https://github.com/nicepkg/gpt-runner/tree/main/docs/example.gpt.md) file represents an AI role preset. They are easy to read, modify, and can be version-controlled. Team members can share and enhance AI presets, making the code they produce closer to 100% usability.


## Features

- **Conversations with Code Files**: Select files or folders and engage in real-time conversations with AI.
- **Powerful CLI and IDE integration:** Implement efficient AI workflows in various IDEs.
- **AI Preset Manager:** Manage your AI presets, Just like a locally Storybook for AI presets.
- **Customize AI parameters:** Flexibly control the configuration of AI models.
- **Support for third-party LLMs:** High compatibility and adaptability.
- **Privacy-first:** Local data storage protects your privacy.
- **Locale support:** Support for multiple languages.

## Quick Start

> 1. Requirements NodeJS >= 16.15.0
>     - To check your NodeJS version, run `node -v` in your terminal. If you need to install or update NodeJS, visit [the official NodeJS website](https://nodejs.org/) for download and installation instructions.
> 2. Make sure you have an Open AI Key or a free ChatGPT account.

### The first way: CLI

```bash
cd <your project folder>
npx gptr
```

You can see the web interface in your browser at [http://localhost:3003](http://localhost:3003).

### The second way:  VSCode Extension

Install the [GPT-Runner VSCode Extension](https://marketplace.visualstudio.com/items?itemName=nicepkg.gpt-runner) from the VSCode Marketplace.

## Documentation

Read the [documentation](https://gpt-runner.nicepkg.cn/) for installation instructions, usage guide, and more details on GPT-Runner's features.

## Road map

- [ ] Jetbrains Plugin: Add Jetbrains IDE Plugin
- [ ] Export And Import Chat History: Add dialogue import and export function
- [ ] AI Preset Store: Add AI Preset Store for community sharing AI Preset File
- [ ] Template Interpolation: Add template interpolation support
- [ ] Electron: Add an Electron client to expand the target audience to non-developers

## What's New

- 🚀 v1.0.0: First Release

## 为什么选择 GPT-Runner？

1. **与代码文件对话：** 
    - 使用 GPT-Runner 前：必须手动复制多个文件代码到 ChatGPT 窗口，向 AI 提出需求或修复 bug 。
    - 使用 GPT-Runner 后：只需在文件树中勾选项目文件，AI 将根据文件的最新内容为您提供解答！

2. **管理项目的AI预设：** 
    - 使用 GPT-Runner 前：保存在备忘录中的项目提示需要复制粘贴给 ChatGPT 才能提问，难以进行 git 版本管理。
    - 使用 GPT-Runner 后：[xxx.gpt.md](https://github.com/nicepkg/gpt-runner/tree/main/docs/example-cn.gpt.md) 文件代表一个AI角色预设，它易于阅读、修改并可进行版本控制。团队成员可以分享和优化 AI 预设，使其生成的代码更接近 100% 的可用性。

## 主要功能

- **与代码文件聊天：** 选择文件或文件夹与 AI 实时对话。
- **强大的 CLI 与 IDE 集成：** 在各种 IDE 中实现高效的 AI 工作流程。
- **管理你的 AI 预设：** 管理你的 AI 预设，它就像 AI 预设的本地 Storybook。
- **自定义 AI 参数：** 灵活控制 AI 模型的配置。
- **支持第三方 LLM：** 具有高度兼容性和适应性。
- **隐私优先：** 本地数据存储保护您的隐私。
- **国际化：** 支持多种语言。

## 快速开始

> 1. 要求 NodeJS >= 16.15.0
>    - 要检查您的 NodeJS 版本，请在终端中运行 `node -v`。如果您需要安装或更新 NodeJS，请访问 [官方 NodeJS 网站](https://nodejs.org/) 以获取下载和安装说明。
>
> 2. 确保你有一个 Open AI Key 或一个免费的 ChatGPT 账号。
> 3. 确保你的命令终端能 ping 通 api.openai.com （如果你在中国大陆，你可能需要科学上网）。

### 方式一：CLI

```bash
cd <你的项目路径>
npx gptr
```

在浏览器中打开 [http://localhost:3003](http://localhost:3003) 即可看到 GPT-Runner 的 Web 界面。

### 方式二：VSCode 扩展

从 VSCode Marketplace 安装 [GPT-Runner VSCode 扩展](https://marketplace.visualstudio.com/items?itemName=nicepkg.gpt-runner)。

## 文档

阅读 [文档](https://gpt-runner.nicepkg.cn/) 以获取安装说明、使用指南和有关 GPT-Runner 功能的更多详细信息。

## 开发计划

- [ ] Jetbrains 插件：添加 Jetbrains IDE 插件
- [ ] 导出和导入聊天记录：添加对话导入导出功能
- [ ] AI预设商店：添加 AI 预设商店以供社区共享 AI 预设文件
- [ ] 模板插值：添加模板插值支持
- [ ] Electron：添加 Electron 客户端，将目标受众推广到非开发人员

## 最新动态

- 🚀 v1.0.0: 首次发布

## FAQ

[English > FAQ](https://github.com/nicepkg/gpt-runner/tree/main/docs/faq-en.md)

[简体中文 > 常见问题](https://github.com/nicepkg/gpt-runner/tree/main/docs/faq-cn.md)

### Sponsor

Waiting for you...

### Contributor

This project exists thanks to all the people who contribute:

<a href="https://github.com/nicepkg/gpt-runner/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=nicepkg/gpt-runner" />
</a>

## Acknowledgement

GPT-Runner is made possible thanks to the inspirations from the following projects:

> in alphabet order

- [Docusaurus](https://github.com/facebook/docusaurus)
- [LangchainJs](https://github.com/hwchase17/langchainjs)
- [UnoCss](https://github.com/unocss/unocss)
- [VSCode-Webview-Ui-Toolkit](https://github.com/microsoft/vscode-webview-ui-toolkit)

## LICENSE

[MIT](https://github.com/nicepkg/gpt-runner/tree/main/LICENSE) License &copy; 2023-PRESENT [Jinming Yang](https://github.com/2214962083)
