# Awesome AI Engineering

精选 AI 编程工具与资源集合 🚀

本项目收录了 149+ AI 驱动的编程工具和资源，涵盖从代码生成、测试、审查到部署的完整开发流程。

## 📋 目录

- [VibeTool - 入门工具](#vibetool---入门工具)
- [CliAgent - 命令行工具](#cliagent---命令行工具)
- [IDE - 开发IDE](#ide---开发ide)
- [Testing - AI测试](#testing---ai测试)
- [DevOps - DevOps工具](#devops---devops工具)
- [Extension - IDE插件](#extension---ide插件)
- [CodeReview - 代码审查](#codereview---代码审查)
- [Other - 其他工具](#other---其他工具)
- [Resource - 相关资源](#resource---相关资源)
- [Docs - 文档相关](#docs---文档相关)
- [Design - 设计工具](#design---设计工具)
- [UI-Code - UI生成](#ui-code---ui生成)
- [CodeAgent - CodeAgent](#codeagent---codeagent)
- [McpTool - Mcp工具](#mcptool---mcp工具)

## VibeTool - 入门工具

| 名称 | 描述 |
|------|------|
| [Readdy](https://readdy.ai/) | Readdy是一款基于AI的智能建站工具，核心特点是通过自然语言对话实现零代码网站开发。用户只需描述需求，AI即可在几分钟内将创意转化为专业级网站设计和生产就绪的前端代码，支持一键发布。其突出优势在于：① 对话式设计界面，无需编程和设计基础；② 自动生成响应式网页和可部署代码，大幅降低开发门槛；③ 提供实时编辑和无限次修改功能，结合定价策略显示其注重用户迭代需求，适合快速打造个性化网站的中小企业和个人创作者。 |
| [nocode](https://nocode.cn/) | 美团的 vibe Coding 平台 |
| [Bolt.new](https://bolt.new/) | Bolt.new 是由 StackBlitz 推出的 AI 驱动全栈开发平台，通过结合 AI 智能与 WebContainers 技术，用户可在浏览器中直接通过自然语言提示生成、编辑、运行并部署全栈应用，无需复杂的本地环境配置。 ￼该平台支持多种框架，如 React、Vue 和 Svelte，并提供丰富的预设模板，如博客网站、移动应用等，方便开发者快速启动项目。 ￼此外，Bolt.new 允许用户一键将应用部署到 Netlify 等平台，并即将支持 Cloudflare，简化了从开发到生产的流程。 ￼其浏览器内运行的特性提高了开发速度和安全性，使其成为开发者快速原型设计和全栈开发的有力工具。 |
| [V0.dev](https://v0.dev/chat) | V0.dev 是由 Vercel 推出的 AI 驱动 UI 开发工具，旨在通过简单的文本提示或图像输入，快速生成与 Shadcn UI 和 Tailwind CSS 兼容的 React 代码。它支持多种前端框架，如 React、Vue 和 Svelte，方便开发者将生成的组件代码直接集成到现有项目中。V0.dev 提供直观的聊天界面，用户可以通过对话生成和预览 UI 组件，并进行测试和定制。 ￼此外，它还具备项目管理和数据源集成功能，提升团队协作效率。 ￼通过 V0.dev，开发者能够显著加快 UI 开发流程，降低开发门槛，提升工作效率 |
| [Lovable](https://lovable.dev/) | Idea to app in seconds. Lovable 是您的超级人类全栈工程师。 |
| [doubao](https://www.doubao.com/code/chat) | 豆包里的vibe coding编程工具，面向非专业开发人员 |
| [miaoda](https://www.miaoda.cn/) | 百度的vibe Coding 平台，一句话生成网站，小游戏等 |

## CliAgent - 命令行工具

| 名称 | 描述 |
|------|------|
| [qwen-code](https://github.com/QwenLM/qwen-code) | Qwen Code 是阿里巴巴通义实验室基于 Qwen3-Coder 模型优化的 AI 编程工具，专为开发者设计的命令行（CLI）工作流工具，旨在通过 AI 能力提升代码开发全流程效率。 |
| [gemini-cli](https://github.com/google-gemini/gemini-cli) | Gemini CLI 是谷歌推出的开源AI编程工具，基于Gemini 2.5 Pro多模态模型，支持自然语言交互，可直接在终端中实现代码生成、调试、文件操作和命令执行，免费且跨平台，极大提升开发者效率。 |
| [crush](https://github.com/charmbracelet/crush) | 开源的终端开发工具 |
| [Claude-Code](https://www.anthropic.com/claude-code) | Claude Code 是 Anthropic 推出的终端原生 AI 编程助手，能通过自然语言交互生成代码、调试修复，以代理式搜索深度感知项目结构，支持跨文件批量编辑与重构，无缝集成 Git、测试套件等开发工具，改动需用户确认，兼具企业级安全与可脚本化特性，适配多系统与 IDE。 |
| [Codex](https://openai.com/codex/) | openAI 出品，Codex 可以并行处理多项任务，例如编写功能、回答代码库问题、运行测试以及提交 PR 以供审查。每项任务都在其自己的安全云沙箱中运行，并预加载了您的代码库 |
| [Aider](https://aider.chat/) | 终端内的 AI 编程助手，Aider is AI pair programming in your terminal |
| [Auto-coder](https://auto-coder.chat/) | 命令行 AI 编程工具，AI-powered interactive coding assistant |
| [iflow](https://github.com/iflow-ai/iflow-cli) | iFlow CLI 是阿里心流团队开发的终端级 AI 智能体，支持自然语言交互，可执行代码分析、文档生成、调试排错、文件管理等任务。它内置 Qwen3-Coder、Kimi K2 等免费模型，能理解项目上下文并调用本地或云端工具，实现从简单脚本到复杂 DevOps 流程的自动化 |
| [warp](https://www.warp.dev/) | Warp Dev 工具是一款面向开发者的现代终端，核心特点包括：采用 Rust 开发，性能高效；支持块状命令输出，便于阅读和交互；内置 AI 助手，可智能补全、生成命令和脚本；提供命令搜索、历史管理、快捷片段等功能；支持团队协作与共享，提高开发效率；界面现代化，兼顾命令行的灵活性与图形化的易用性。 |
| [copilot-cli](https://github.com/github/copilot-cli) | github copilot 对应的终端开发工具，类似 claude-code |

## IDE - 开发IDE

| 名称 | 描述 |
|------|------|
| [Kiro](https://kiro.dev/) | 亚马逊AWS正在研发的AI编程工具Kiro，通过多模态界面与AI Agent协同工作，实现代码的近乎实时生成，覆盖从技术设计到实现的完整流程，可能彻底改变软件开发的传统模式  |
| [trae.cn](https://www.trae.cn/) | trae 国内版 |
| [LingmaIDE](https://lingma.aliyun.com/lingma/download) | 阿里的 AI IDE，对标 cursor |
| [Trae](https://www.trae.ai/home) | Trae 是字节跳动 2025 年推出的首个 AI 原生 IDE，集成豆包、DeepSeek 等多模型，支持自然语言生成完整项目、Figma 设计稿秒转代码，能跨文件定位 Bug 并优化，更适配国产框架，通过 Builder、Chat 等模式实现从需求到部署的全流程开发，且免费开放核心功能，大幅提升开发效率。 |
| [Cursor](https://www.cursor.com/) | Cursor是一款基于AI的智能代码编辑器，旨在通过集成大型语言模型（如GPT-4o和Claude 3.5等）来提升开发者的编码效率和体验。它不仅是一个文本编辑器，更是一个能够理解和生成代码的智能助手，具备多种强大的功能。 |
| [PearAI](https://trypear.ai/) | VS Code 的开源分支，支持聊天与内联代码生成 |
| [Void](https://voideditor.com/) | 开源的 Cursor 替代品 |
| [Zed](https://zed.dev/) | Zed 是一款新一代代码编辑器，专为与人类和 AI 的高效协作而设计。 |
| [Melty](https://github.com/meltylabs/melty) | VS Code 的开源分支，内置聊天、变更预览、AI 生成提交信息 |
| [CodeStory](https://codestory.ai) | 基于 VSCodium 的 IDE，支持聊天、代码解释、自动生成提交和 PR 概述， Aide编辑器 |
| [Neovim](https://github.com/yetone/avante.nvim) | Avante.nvim 插件模仿 Cursor IDE 的行为 |
| [Windsurf](https://codeium.com/windsurf) | 首个具备代理特性的集成开发环境 (IDE)。Windsurf Editor 是开发者与 AI 真正融为一体的工作场所，带来宛如魔法般的编码体验，让编程更流畅、更高效。 |
| [CodeBuddy](https://www.codebuddy.ai/) | CodeBuddy IDE 是腾讯云推出的革命性 AI 编程工具，旨在通过自然语言交互和 AI 驱动技术彻底改变传统软件开发流程。CodeBuddy IDE的核心优势在于：全流程AI驱动：通过四大智能体（Plan/Design/Coding/Deploy Agent）实现从需求分析到部署的一站式开发，效率提升10倍（如电商页面开发从2天压缩至2小时） |
| [Qoder](https://qoder.com/) | Qoder 是阿里推出的 Agent 级 AI 编程平台，通过 RepoWiki 把"祖传代码"变知识图谱，Quest 模式让 AI 按 Spec 自主拆任务、写代码、跑测试并实时透明展示，全程可追溯；配合长期记忆与模型自动路由，开发者只需验收，实现"写需求即可交付"的新范式 |
| [joycode](https://joycode.jd.com/) | JoyCode 是京东云推出的新一代智能编程 AI IDE ，通过 AI 技术为开发者提供高效、智能的编程体验。支持自然语言编程，开发者可以通过简单的语言描述需求， AI 自动生成代码，极大地提升了开发效率。JoyCode 配备了多智能体协作团队，智能体能协同工作，拆解复杂任务并高效执行，实现人机协同编程。JoyCode 基于代码仓库、Lint 错误、终端信息等上下文，提供更精准的代码生成和优化建议。全面支持云端开发，用户可以随时随地创建远程项目并进行自动化环境配置。开发完成后，JoyCode 支持一键部署和快速上线，打通了从开发到发布的全流程闭环。 |
| [catpaw](https://catpaw.meituan.com/) | 美团 CatPaw 是一款以 Agent 驱动的 AI 编程 IDE，依托自研 LongCat 大模型，支持 Python、Java 等主流编程语言，具备代码补全预测、智能问答生成、IDE 内预览调试及项目级分析等全链路功能，当前对用户免费开放（新用户享 500 次对话额度），能大幅提升开发效率。 |
| [Antigravity](https://antigravity.google/) | Google 推出的 AI 原生 IDE，集成代理管理器、编辑器与浏览器，以 AI 驱动打通开发全流程，支持多模型免费使用 |
| [verdent](https://www.verdent.ai/) | 一个面向专业开发者的 AI 编程套件，通过"多 AI 智能体并行 + 计划-编码-验证"流程，将模糊需求自动拆解成可执行任务、生成经过测试与审核的高质量可投产代码，从而大幅提升大型/复杂项目的开发效率和代码可靠性。 |
| [talkcody](https://talkcody.com) | TalkCody 是一款免费、开源的 AI Coding Agent 桌面应用，使用 Rust + Tauri 2 构建，支持 Windows、macOS 和 Linux 三大平台。 支持灵活切换模型和服务商。你用自己的 API Key，直接和 AI 厂商结算，没有中间商。这种 BYOK（BringYour Own Key）的模式，让你既能省钱，又不会被锁定。 |

## Testing - AI测试

| 名称 | 描述 |
|------|------|
| [EarlyAI](https://www.startearly.ai/) | EarlyAI 是一款智能开发工具，通过自动生成高覆盖率的单元测试来提升代码质量，帮助开发者专注于创新应用。它提供自动测试生成、易于导航的界面、文档建议和 Pull Request 测试等功能，用户已生成超过 50,000 个测试，显著提升了代码覆盖率和开发效率。 |
| [KushoAI](https://kusho.ai/) | API 测试的 AI 代理，可以将您的 Postman 集合、OpenAPI 规范、curl 命令等转换为完整的测试套件，并集成到您的 CI/CD 管道中。 |
| [MutahunterAI ](https://github.com/codeintegrity-ai/mutahunter) | 通过发现代码中的漏洞并为其生成测试，加速开发者的生产力和代码安全。开源并提供 CLI 或 CI/CD 管道支持。 |
| [Meticulous.ai ](https://www.meticulous.ai/) | 自动生成、自动维护的端到端测试：随着应用程序的发展，测试套件也会不断更新。 |
| [carbonate](https://carbonate.dev/) | 使用自然语言进行端到端测试。与现有的测试套件（目前支持 Jest、PHPUnit 和 Python 的 unittest）集成。 |
| [OctoMind ](https://www.octomind.dev/) | 自动维护并生成基于浏览器的端到端测试，集成到 Github Actions、Azure DevOps 等工具中。 |
| [BlinqIO](https://blinq.io/) | BlinqIO AI Test Engineer 实现了应用程序的完整端到端测试自动化，帮助您更快发布高质量软件。借助 AI Test Engineer，您可以轻松将手动测试转换为测试自动化代码（Playwright，开源），并将其集成到您的 CI/CD 管道中。 |
| [tusk](https://www.usetusk.ai/) | 通过高影响力的测试增加代码覆盖率。生成基于代码库上下文的单元测试和集成测试，捕捉开发者遗漏的边界情况。 |
| [devchat](https://www.devchat.ai/) | 从文档到测试脚本，只需一步根据 API 文档、调用日志、业务场景描述等，自动生成测试脚本。 将你的测试开发效率提升 10 倍，轻松提升接口测试覆盖。 |
| [testsprite](https://www.testsprite.com/) | 这是一款由 AI 驱动的"零代码"自动化测试平台，能够自动生成并执行 GUI、前端交互、后端 API 等测试用例，在几十分钟内完成完整测试流程，从而帮你快速发现与修复 bug，提高代码发布质量与效率。 |
| [momentic](https://momentic.ai/) | 一款由 AI 驱动的端到端自动化测试平台——你只需用自然语言描述用户流程或断言，Momentic 就能自动生成稳定、不易"断裂"的测试脚本，并随着应用 UI 演化自适应更新，极大节省开发／QA 团队编写和维护测试的时间，提高发布效率与质量 |

## DevOps - DevOps工具

| 名称 | 描述 |
|------|------|
| [keep](https://github.com/keephq/keep) | 开源的警报管理和 AIOps 平台，提供单一监控视图、去重、过滤等功能，支持双向集成、工作流和仪表板等。其主要功能包括可定制的用户界面、警报管理工具、深度集成与监控工具的同步、自动化监控工具的 GitHub Actions，以及基于 AI 的关联和总结（AIOps 2.0）。 |
| [HolmesGPT](https://github.com/robusta-dev/holmesgpt) | HolmesGPT作为一款创新的开源DevOps助手，旨在简化Kubernetes故障排除、事件响应和工单管理。它的独特之处在于能够自主获取缺失数据，直到问题解决，潜在地将开发团队的问题解决速度提高一倍。其符合合规的特性和透明的结果对于关注数据隐私和法规遵从的组织至关重要 |

## Extension - IDE插件

| 名称 | 描述 |
|------|------|
| [CodeBuddy](https://copilot.tencent.com/) | 腾讯云代码助手，兼容 Visual Studio Code、Visual Studio、JetBrains IDEs 等主流编程工具， 为你提供高效、流畅的智能编码体验 |
| [junie](https://www.jetbrains.com/zh-cn/junie/) | jetbrains 出品，您的智能编码智能体,不仅提高工作效率 – 一种新的编码方式 |
| [roo-code](https://github.com/RooVetGit/Roo-Code) | Roo Code (prev. Roo Cline) gives you a whole dev team of AI agents in your code editor. |
| [javaAI](https://www.feisuanyz.com/home) | 不仅仅是一个代码生成工具，引导式开发，辅助需求细化和功能设计精准生成完整工程源码 |
| [tabby](https://www.tabbyml.com/) | 免费开源的自托管AI编程助手 |
| [Augment](https://www.augmentcode.com/) | Augment 是一个 AI 驱动的开发辅助工具，能在 IDE 中为代码提供实时解释、上下文搜索、调试建议和架构可视化，帮助开发者更快理解和维护大型代码库。 |
| [Tabnine](https://www.tabnine.com/) | Tabnine 的 AI 代码助手帮助您更快地交付更高质量的软件 |
| [GitHub-Copilot](https://github.com/features/copilot) | AI 编程辅助插件 |
| [Codium](https://www.codium.ai/) | AI 辅助代码生成和优化 |
| [Comate](https://comate.baidu.com/zh) | 百度的 AI 编程插件 |
| [lingma](https://tongyi.aliyun.com/lingma) | 阿里巴巴的 AI 编程工具，通义灵码 |
| [Cline](https://github.com/cline/cline) | Cline是一款开源的VS Code AI编程助手，通过多模型支持（如DeepSeek、Claude等）实现智能代码生成、错误修复及终端命令执行，其核心特点是灵活可控的AI协作：所有操作需用户确认确保安全，支持本地模型降低成本，并能通过无头浏览器等扩展功能处理复杂任务，区别于收费工具（如Cursor）的封闭性 |
| [Continue](https://www.continue.dev/) | Continue 是一款开源免费的 AI 编程助手插件，支持 VS Code 和 JetBrains IDE，核心特点包括灵活配置多种 AI 模型（如 GPT-4、Claude 等）、本地化部署保障数据隐私，以及智能代码补全、自然语言交互和上下文感知编辑功能。其开源特性与高度可定制化（如自定义模型、上下文工具）显著区别于闭源工具如 GitHub Copilot 和 Cursor，尤其适合对安全性和扩展性要求高的开发者 |
| [supermaven](https://supermaven.com/) | Supermaven通过100万个token的超大上下文窗口和极低的延迟，提升代码生成的精准性和速度，并结合上下文感知技术增强开发体验。 |

## CodeReview - 代码审查

| 名称 | 描述 |
|------|------|
| [CodeDog](https://www.codedog.ai/) | CodeDog是一款AI驱动的代码审查工具，旨在通过自动化的方式提高代码质量和开发效率。它能够检测代码中的潜在问题、风格违规和安全漏洞，并提供修复建议，帮助开发者在早期阶段发现并解决问题。 |
| [AI Code Reviewer](https://github.com/buxuku/ai-code-reviewer) | 一个利用 openai api 对 gitlab 提交的 merge request 进行 code review 的小工具 |
| [CodeReviewBot](https://codereviewbot.ai/) | CodeReviewBot是一款自动化代码审查机器人，能够在代码提交时自动进行审查，提供改进建议。它支持多种编程语言，旨在提高代码审查的效率和一致性。 |
| [coderabbit](https://www.coderabbit.ai/) | CodeRabbit 是一个由 AI 驱动的代码审查工具，可以在几分钟内为拉取请求提供上下文相关的反馈，大幅减少手动代码审查所需的时间和精力。 |
| [Bito](https://bito.ai/) | Bito.ai 提供基于 AI 的代码审查服务，能结合整个代码库理解代码，在 GitLab、GitHub 等平台及 VS Code 等 IDE 中使用，支持自定义审查规则，可追踪 PR 数据，助力团队快速合并 PR、减少回归问题，且保障代码安全，帮团队提升开发效率。 |
| [qodo](https://www.qodo.ai/) | Qodo（前称Codium）是一个智能代码完整性平台，旨在审查、测试和编写代码。它将人工智能整合到开发工作流中，以加强每个阶段的代码质量。Qodo提供人工智能驱动的代码审查、测试和代码生成功能，旨在提升生产力和代码质量。它支持多种编程语言，并可与VSCode和JetBrains等集成开发环境，以及GitHub和GitLab等Git提供商集成。 |

## Other - 其他工具

| 名称 | 描述 |
|------|------|
| [superclaude](https://superclaude.netlify.app/) | A framework that extends Claude Code with 16 specialized commands, smart personas, and MCP server integration |
| [yoyo](https://www.runyoyo.com/) | AI 编程版本管理工具 |
| [codemagic](https://codemagic.io/start/) | Codemagic CI/CD 与 Azure DevOps、GitHub、GitLab、Bitbucket 和其他自托管或基于云的 Git 仓库集成。您推送代码，Codemagic 会负责构建、测试和分发您的应用程序 |
| [SourceGraph](https://sourcegraph.com/) | Sourcegraph 是一个代码智能平台，能够深入理解您的代码，无论它有多大，或托管在哪儿，从而支持现代开发者的体验。Cody：使用 Cody 作为我们的 AI 代码助手，更快速地阅读、编写和理解您的整个代码库；代码搜索：在所有的仓库、分支和代码托管平台中搜索；代码智能：浏览代码、查找引用、查看代码所有者、追踪历史等；修复与重构：在多个仓库中一次性推出并跟踪大规模的更改和迁移。 |
| [buildship](https://buildship.com/?ref=producthunt) | 自动化复杂的业务任务并构建由 AI 驱动的 API。您可以从成千上万的预构建节点中选择，或创建您自己的节点。使用生产级可扩展性、版本控制、代码访问、存储等进行部署。无需编码的简便性与编码灵活性结合。 |
| [code5](https://github.com/salesforce/CodeT5) | 开放的代码大语言模型 (LLMs) 用于代码理解和生成 |
| [easycode](https://www.easycode.ai/) | IDE 扩展；EasyCode - AI 能够理解您的代码库。通过即时回答开发者的问题，帮助解除开发障碍 |
| [komment](https://www.komment.ai/) | Komment 无缝集成到现有的开发者工作流程中，从零开始为您的代码库构建复杂、富有见解的技术维基。Komment 生成多种类型的技术文档，并自动将其组织成一个有凝聚力的维基，使您的团队能够轻松搜索、查看和共享项目的关键知识。 |
| [copycoder](https://copycoder.ai/) | 为下一代 AI 编程人员打造。上传完整应用程序、UI 原型或自定义设计的图片，并使用我们生成的提示更快地构建您的应用程序。 |

## Resource - 相关资源

| 名称 | 描述 |
|------|------|
| [Awesome Code AI](https://github.com/sourcegraph/awesome-code-ai) | AI 编程工具资源汇总 |
| [Awesome AI Coding](https://github.com/wsxiaoys/awesome-ai-coding) | A list of AI coding tools (assistants, completions, refactoring, etc.) |
| [Awesome AI DevTools](https://github.com/jamesmurdza/awesome-ai-devtools) | 开发者 AI 工具资源集合,比较全面 |
| [devhunt](https://devhunt.org/) | 开发者工具产品集合,类似 product hunt |
| [toolify-tools](https://www.toolify.ai/zh/free-ai-tools/coding-development) | toolify导航网站里的AI编程工具列表，工具丰富 |

## Docs - 文档相关

| 名称 | 描述 |
|------|------|
| [deepwiki](https://deepwiki.com/) | DeepWiki 是 Devin Wiki 和 Devin Search 的免费公共版本，可以将任何公共 GitHub 仓库快速转换成可对话的、类似维基式的文档界面 |
| [mappie](https://www.mappie.ai/) | 产品需求文档AI生成 |
| [codeguide](https://www.codeguide.dev/) | 您的 AI 开发伴侣，帮助您编写文档、规划，以便更好的使用cursor，windsurf等工具进行开发 |
| [zread](https://zread.ai/) | Zread能够把复杂的 GitHub 项目"翻译"成简单易懂的语言，包括快速生成结构化的 Wiki 文档，对代码进行梳理、总结，介绍项目的背景、口碑、团队等。有了这样的生产力工具，终于不用花好几天埋头研究代码，几分钟内就能掌握项目的核心内容。 |
| [Spec-kit](https://github.com/github/spec-kit) | Spec-Kit 是 GitHub 官方推出的开源规范驱动开发工具包，以 "规范即代码" 为核心，通过深度集成 Copilot、Claude 等 AI 编码助手，将清晰完整的需求规格直接转化为可执行代码，颠覆传统开发中规格与实现脱节的问题。它依托 "项目宪法" 建立统一标准，覆盖从项目初始化到代码生成的全流程，支持多技术栈，适配新项目开发、遗留系统现代化等场景，能显著提升开发效率、保证代码质量与合规性，降低维护成本。 |
| [codewiki](https://codewiki.google/) | Code Wiki 是 Google 推出的 Gemini 驱动 AI 代码文档工具，可深度扫描 GitHub 代码仓库，自动生成含系统概览、模块说明与可视化图表的结构化 Wiki，支持代码提交实时同步更新，集成交互式聊天问答与代码直达导航，助力开发者快速理解代码库、团队协作与新成员上手，解放文档撰写精力。 |

## Design - 设计工具

| 名称 | 描述 |
|------|------|
| [lovart](https://www.lovart.ai/) | Lovart 是一个跨模态的 AI 设计代理工具，它不仅能将自然语言文本转换为专业级视觉设计（如图像、视频、音频、3D 等），还能自主策划、执行并协同多种 AI 模型，像一个完整的设计团队一样帮你完成创意项目 |
| [motiff](https://motiff.com/) | AI设计，一句话生成设计稿 |
| [superdesign](https://www.superdesign.dev/) | SuperDesign 是一个面向开发者的AI 设计助手，其核心理念是：让设计回归代码工作流，让开发者零门槛做设计。 它通过插件形式无缝嵌入到开发者日常使用的IDE 中，使你可以在写代码的同时完成界面设计、组件复用和快速迭代。 |
| [stitch](https://stitch.withgoogle.com/) | Stitch 是 Google 于 2025 年 5 月推出、隶属于 Google Labs 的实验性 AI 驱动工具，依托 Gemini 系列模型（如 Gemini 2.5 Pro/Flash、Gemini 3 Pro），支持通过自然语言描述或图像（草图、线框图等）输入快速生成 Web 和移动应用的 UI 设计及对应前端代码，可导出至 Figma 进一步优化或直接提供 HTML/CSS 代码，助力设计师与开发者简化从创意到原型 / 代码的流程 |

## UI-Code - UI生成

| 名称 | 描述 |
|------|------|
| [same.new](https://same.new/) | Same.dev是一款专注于UI克隆的AI工具，其核心价值主张简单明了："Copy any UI"（复制任何UI）。与传统的UI设计工具不同，Same.dev采用了一种全新的方法：用户只需提供目标网站的URL，系统就能生成该界面的像素级完美复制版本。 |
| [flame](https://github.com/Flame-Code-VLM/Flame-Code-VLM) | Flame 是一款开源的多模态人工智能系统，专为将 UI 设计稿转化为高质量的 React 代码而构建。该系统通过融合视觉语言建模、自动化数据合成和结构化训练流程，致力于消除设计与前端开发之间的鸿沟，实现设计稿到可运行代码的端到端转换。 |
| [Draw-A-UI](draw-a-ui.com) | 根据草图生成代码，Use AI to turn your UI sketches into HTML code instantly, right from your browser. |
| [Screenshot-to-Code](screenshottocode.com) | 根据截屏生成代码，Drop in a screenshot and convert it to clean code (HTML/Tailwind/React/Vue) |
| [UI-Pilot](https://ui-pilot.com/) | UI Pilot 是一个由 AI 驱动的代码生成器。您可以要求它为您创建一个表单式 UI，它会提供代码和一个运行示例。您可以输入类似以下内容："创建一个包含名字和姓氏字段的表单"。 |
| [builder](https://builder.io/) | Figma 插件：将设计转换为干净、响应式的代码，支持多个框架和 CSS 库。 |
| [Kombai ](https://kombai.com/) | 从 Figma 生成前端代码的AI工具。 |
| [locofy](https://www.locofy.ai/) | Locofy.ai：将您的设计转换为适合开发人员的前端代码，支持移动应用和网页。它使构建者能够在现有设计工具、技术栈和工作流程的基础上将产品交付速度提高 10 倍 |
| [webdraw](https://webdraw.ai/) | webdraw.ai：提供了一个直观的环境，将草图直接转换为完整的应用程序 |
| [Literallyanything ](https://www.literallyanything.io/) | HTML 和 JavaScript Web 应用生成器：生成完整的前端应用，支持 HTML 和 JavaScript |
| [anima](https://dev.animaapp.com/) | Anima（访问 dev.animaapp.com）是一款将设计稿（如 Figma 设计）或网页 URL "一键"自动转换为可运行、可编辑、响应式网页／应用代码（React / Vue / HTML + CSS 或 Tailwind 等）的 AI 驱动 "design-to-code" 平台，帮助设计师和开发者从视觉稿快速生成生产就绪代码，极大缩短从"设计"到"上线"的开发周期。 |

## CodeAgent - CodeAgent

| 名称 | 描述 |
|------|------|
| [fragments](https://github.com/e2b-dev/fragments) | 这是类似于 Anthropic 的 Claude Artifacts、Vercel v0 或 GPT Engineer 的开源版本。 |
| [Devika](https://github.com/stitionai/devika.git) | Devika 是一个代理型 AI 软件工程师，能够理解高级人类指令，将其拆解成步骤，研究相关信息，并编写代码以实现给定目标。Devika 旨在成为 Cognition AI 的 Devin 的竞争性开源替代品。 |
| [OpenHands](https://github.com/OpenDevin/OpenDevin) | 一个由 AI 驱动的软件开发代理平台。OpenHands 代理能够执行任何人类开发者能够做的事情：修改代码、运行命令、浏览网页、调用 API，甚至从 StackOverflow 复制代码片段。 |
| [MetaGPT](https://github.com/geekan/MetaGPT.git) | 多代理框架，支持自然语言编程；The Multi-Agent Framework: First AI Software Company, Towards Natural Language Programming |
| [bolt.new-any-llm](https://github.com/coleam00/bolt.new-any-llm) | 使用任何您想要的 LLM 提示、运行、编辑和部署全栈 Web 应用程序！ |
| [DevOpsGPT](https://github.com/kuafuai/DevOpsGPT) | 面向 AI 驱动的软件开发的多代理系统。将 LLM 与 DevOps 工具结合，使用自然语言需求转换为可工作的软件。支持任何开发语言，并扩展现有代码。 |
| [momen](https://momen.app/?ref=producthunt) | Momen是一款无代码全栈开发工具，用户可以通过Momen完成页面、业务逻辑和数据模型的可视化设计，通过高性能后端来实现复杂的数据交互与管理，并将项目一键部署上线 |
| [Jules](https://jules.google.com/) | google 出品，这个工具的定位很明确：不是编程助手，而是能独立承担任务的开发者。 |
| [youware](https://www.youware.com/) | YouWare是一款面向AI时代创作者的"氛围编程"平台，通过自研AI Agent和Sandbox引擎实现"所想即所得"，让非技术用户能用自然语言生成网页并一键部署，同时提供创意社区、作品二次创作（Remix）及激励体系，彻底打破编程与部署的壁垒。 |
| [MetaGPTX](https://mgx.dev/) | MetaGPT X 是一个多智能体开发团队，由 leader、product manager、architect、engineer 和 data analyst 共 5 位 AI 智能体组成，能够创建网站、博客、商店、分析、游戏等，目标是替代小型开发团队。 |
| [trickle](https://app.trickle.so/) | Trickle.so 是一款面向非专业开发者的 AI 驱动型 Vibe coding 工具，以 "Magic Canvas" 可视化画布为核心，融合多模态生成能力，让用户通过自然语言描述需求，即可无缝完成网站、AI 应用、智能表单等数字产品的构思、设计、逻辑搭建与一键部署，其内置轻量级数据库、丰富设计模板、自定义域名及多模型集成功能，支持上传自有素材与实时预览，无需编程基础就能实现 "所想即所得"，既适配个人快速验证创意，也满足团队构建内部工具、数据仪表盘的需求，为全球用户提供开箱即用的高效创作体验。 |
| [townie](https://www.val.town/townie) | Townie 是 Val Town 的 AI 助手，专注于帮助开发者快速创建、部署和迭代代码片段（在 Val Town 中被称为"vals"）。它不仅能生成代码，还支持即时部署，让你的想法立刻"跑起来"，省去了手动配置环境的麻烦。 |
| [Devin](https://devin.ai/) | Devin是一款自主的人工智能软件工程师，能够编写、运行和测试代码，帮助软件工程师处理个人任务或团队项目。 |
| [Websim](WebSim.ai) | 可以生成网站、网页游戏、小工具 |
| [Srcbook](srcbook.com) | Srcbook是一个以TypeScript为中心的应用开发平台。它使您可以利用AI作为配对程序员，以极快的速度创建和迭代Web应用程序。它可以创建或编辑Web应用程序，还可以通过交互式笔记本界面编写和执行后端代码。 |
| [Replit](https://replit.com/) | 一站式开发环境，支持自动化编写代码、安装包、配置数据库和部署 |
| [Marblism](https://www.marblism.com/) | Marblism 是一个由 AI 驱动的平台，能够从一个简单的提示生成功能齐全的 Web 应用程序。它通过创建数据库架构、Node.js 后端 API 和 React 前端页面来自动化开发过程。Marblism 提供诸如身份验证、OpenAI 集成、电子邮件功能、支付处理和文件上传等功能，使开发者能够快速构建 SaaS 应用程序、市场平台、社交应用和 AI 驱动的工具。 |
| [Pico ](https://picoapps.xyz/) | 简单的前端代码生成，不太成熟 End-to-end micro app generator with instant deployment. |
| [Mage ](https://usemage.ai/) | 使用 Wasp、React、Node.js 和 Prisma 生成全栈 Web 应用程序。用户可以实时查看生成过程，并且提供开源代码供参考和定制。 |
| [Factory ](https://www.factory.ai/) | Factory 通过为 AI 和人类协作量身打造的企业平台，帮助组织自动化并优化其软件开发生命周期。 |
| [potpie](https://potpie.ai/) | 开源 AI 代理，可在几分钟内为您的代码库服务。您可以使用预构建的代理进行问答 (Q&A)、测试、调试和系统设计，或创建专为特定目的设计的自定义代理。 |
| [Fine](https://fine.dev) | Fine 是一个面向初创企业的 AI 编程平台，可帮助更快地构建、测试和交付软件。在任何地方都可以在自然的协作工作流程中使用 AI。 |
| [codeflying](https://www.codeflying.net/#/index) | 码上飞，需求秒变软件的全流程自动化智能开发平台 |
| [sudocode](https://sudocode.ai/) | Develop on the bleeding edge with an AI task force that turns your ideas directly into code。 类似jupyter，可以执行代码 |
| [llamacoder](https://llamacoder.together.ai/) | 一个开源的 Claude Artifacts，可以通过一个简单的提示生成小型应用程序。由 Llama 3 405B 和 Together.ai 提供支持。 |
| [aigcode](https://www.aigcode.net/) | AutoCoder 100% 端到端软件自动化平台 |
| [rocket](https://www.rocket.new/) | 描述你的应用构想，或上传 Figma 链接。Rocket（火箭）能帮你快速构建并发布真正可投入生产环境的应用，特点是除了可以生成 Web，也可以生成APP |
| [gambo](https://www.gambo.ai/) | Gambo.ai 是全球首款游戏氛围编码工具，无需专业开发经验，通过简单提示即可快速打造街机、动作、益智、恋爱模拟等多元类型游戏，自动生成 AI 游戏资源（动画、音效、地图等），内置顶级广告网络，一键植入广告实现首日变现，还配备地图编辑器与 Discord 社区支持，助力开发者高效构建受欢迎的游戏，从首个玩家起就能赚取收益，轻松实现游戏创作与盈利双赢。 |
| [base44](Base44.com) | AI 驱动的零代码应用开发平台，无需编程基础，一句话描述需求即可生成全栈应用。它自动搞定后端、数据库、部署等复杂流程，几十秒就能从创意落地为可使用的产品。适配个人工具、企业管理系统、商业 MVP 等多场景，支持 PC 与移动端，还能集成支付、短信等功能。 |

## McpTool - Mcp工具

| 名称 | 描述 |
|------|------|
| [taskmaster](https://github.com/eyaltoledano/claude-task-master) | 它是一个强大的 AI 任务管理工具，专为 AI 驱动开发设计。它通过智能解析产品需求文档（PRD），生成结构化的任务列表，并支持任务拆分、依赖管理及复杂性分析。它不仅能与 Claude、Chatgpt、Gemini 等 AI 模型深度整合，还支持 VS Code、Cursor、Windsurf等编辑器，让开发者在熟悉的开发环境中轻松管理复杂项目。 |
| [chrome-devtools](https://developer.chrome.com/blog/chrome-devtools-mcp?hl=zh-cn) | Chrome DevTools MCP 是谷歌推出的 Model Context Protocol 服务器，作为 AI 编程助手（如 Claude、Cursor）与 Chrome 浏览器间的桥梁，将 DevTools 能力封装为可调用工具，支持 AI 完成页面操控、网络分析、性能追踪、控制台监控等操作，实现自动化测试、调试与优化的闭环，无需人工介入验证。 |
| [mcp.so](https://mcp.so/zh) | mcp 市场，有丰富的 mcp 工具 |
| [mcpcn](https://mcpcn.com/) | mcp 中文网站，有丰富的 mcp 资料 |
| [cursor-mcp](https://cursor.directory/mcp) | 另一个mcp 市场，有丰富的 mcp 工具 |
| [context7](https://context7.com/) | Context7  MCP 是一款基于 Model Context Protocol (MCP) 的服务工具，能够为 AI 编码助手在提示中自动注入最新库/框架的官方文档和代码示例，从而消除过时信息与"幻觉"代码，提升开发效率和准确性。 |

---

## 🤝 贡献

欢迎提交 Pull Request 来添加新的工具或更新现有信息！

## 📄 许可

MIT License

---

**⭐ 如果这个项目对你有帮助，请给个 Star！**
