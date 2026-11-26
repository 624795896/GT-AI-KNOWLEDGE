# GitHub Trending

分类：github-trends

本期合并所提供的三批材料，去重后覆盖 14 个项目 ，包含 Trending 第 1—13 名及第 16 名，并非完整榜单。日期、排名与 Star 均沿用材料快照；“周期新增 Star”保留原统计口径，不推定具体窗口。以下区分材料事实、项目声明与分析推断； Trending 和 Star 反映关注度，不直接等同于生产采用率、可靠性或实际效果。

## 热点项目榜单

| Trending 名次 | 项目 | 核心用途 | 主要语言 | 周期新增 Star | 总 Star | 来源 |
| --- | --- | --- | --- | --- | --- | --- |
| #1 | elementalsouls/Claude-BugHunter | 面向 Claude Code 的漏洞挖掘与外部红队技能包 | Python | 1,803 | 未知：材料截断 | 【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】 |
| #2 | obra/superpowers | AI 编程代理技能框架与软件开发方法体系 | Shell | 883 | 323,813 | 【GitHub Trending 2026-11-22 #2: obra/superpowers】 |
| #3 | HKUDS/CLI-Anything | 围绕 CLI 为软件提供智能体交互入口 | Python | 769 | 62,154 | 【GitHub Trending 2026-11-22 #3: HKUDS/CLI-Anything】 |
| #4 | jingyaogong/minimind | 从零训练小型大语言模型的学习与实验项目 | Python | 488 | 68,220 | 【GitHub Trending 2026-11-22 #4: jingyaogong/minimind】 |
| #5 | cursor/plugins | Cursor 插件规范及官方插件 | TypeScript | 260 | 18,142 | 【GitHub Trending 2026-11-22 #5: cursor/plugins】 |
| #6 | firecrawl/firecrawl | 为智能体提供搜索、网页抓取与外部数据接入 API | TypeScript | 1,006 | 206,318 | 【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 |
| #7 | nginx/nginx | Web 服务、反向代理、负载均衡、缓存及协议代理 | C | 189 | 32,756 | 【GitHub Trending 2026-11-22 #7: nginx/nginx】 |
| #8 | openvinotoolkit/openvino | AI 推理优化与模型部署 | C++ | 200 | 11,957 | 【GitHub Trending 2026-11-22 #8: openvinotoolkit/openvino】 |
| #9 | cathrynlavery/diagram-design | 面向 AI 编程工具的图表设计，以 HTML、SVG 交付 | HTML | 583 | 69,859 | 【GitHub Trending 2026-11-22 #9: cathrynlavery/diagram-design】 |
| #10 | mvanhorn/last30days-skill | 跨平台检索近期信息并生成综合摘要 | Python | 560 | 72,090 | 【GitHub Trending 2026-11-22 #10: mvanhorn/last30days-skill】 |
| #11 | google-labs-code/stitch-skills | 配合 Stitch MCP 服务器使用的 Agent Skills 技能库 | TypeScript | 326 | 11,501 | 【GitHub Trending 2026-11-22 #11: google-labs-code/stitch-skills】 |
| #12 | mjmirza/app-store-compliance | 移动应用合规指引、拒审修复与提交前检查 | Shell | 720 | 3,477 | 【GitHub Trending 2026-11-22 #12: mjmirza/app-store-compliance】 |
| #13 | Tracer-Cloud/opensre | 面向 CI/CD 可靠性、故障分析与修复的智能体 | Python | 450 | 14,039 | 【GitHub Trending 2026-11-22 #13: Tracer-Cloud/opensre】 |
| #16 | zhouxiaoka/autoclip | 长视频转短视频，并生成字幕、封面和发布文案 | Python | 683 | 12,941 | 【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】 |

关注度观察（事实）： 本组材料中，Claude-BugHunter 的排名与周期增星均居首，Firecrawl 的周期增星次之，Superpowers 的总 Star 最多。排名较后的 app-store-compliance 和 AutoClip 分别新增 720、683 Star，也值得重点关注。榜单名次与周期增星并非同一排序，不能据此重建 Trending 排名。【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-22 #2: obra/superpowers】 【GitHub Trending 2026-11-22 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】

## 热点项目分析

### 1. Claude-BugHunter：把安全研究经验组织成代理可用的技能

事实与项目声明： 项目面向漏洞赏金研究员、渗透测试人员及应用安全团队，为 Claude Code 提供安全研究技能。材料记载其包含 82 项技能、15 个斜杠命令，以及覆盖 24 类核心漏洞的 681 个已披露报告模式 ，另有企业身份与基础设施攻击矩阵。这些数字体现内容规模，不能替代检测准确率或实战效果评估。【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】

技术看点与走红推断： “报告模式—技能—命令”的组织方式，尝试把安全知识转为可重复使用的研究步骤。明确的专业场景、Claude Code 使用入口和具体的知识规模展示，可能共同解释其吸引力；但现有材料无法证明它能提高漏洞发现率，也无法确定本次增星的直接诱因。【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】

### 2. Superpowers、CLI-Anything 与插件技能生态：让代理更容易组织工作、调用工具

事实： Superpowers 定位为 AI 编程代理技能框架与开发方法体系，涉及头脑风暴、软件开发生命周期和子代理驱动开发。CLI-Anything 提出让软件具备智能体原生交互能力的目标，围绕 CLI 提供入口，并列出 CLI-Hub；材料未披露其支持的软件清单及调用架构。【GitHub Trending 2026-11-22 #2: obra/superpowers】 【GitHub Trending 2026-11-22 #3: HKUDS/CLI-Anything】

事实与项目声明： cursor/plugins 提供 Cursor 插件规范和官方插件。Stitch Skills 则提供配合 Stitch MCP 服务器使用的技能，声明遵循 Agent Skills 开放标准，并列出 Antigravity、Gemini CLI、Claude Code、Cursor 等兼容目标；这些兼容声明尚不能替代实际集成验证。【GitHub Trending 2026-11-22 #5: cursor/plugins】 【GitHub Trending 2026-11-22 #11: google-labs-code/stitch-skills】

技术看点与走红推断： 这组项目分别解决流程组织、软件调用、编辑器扩展和技能复用问题，潜在用户包括 AI 编程工具使用者、自动化工程师和插件开发者。它们的共同吸引力可能在于降低反复编写提示、接入工具和组织任务的成本。值得观察的设计分别是流程如何执行、CLI 操作如何稳定返回结果、插件规范如何约束扩展，以及技能能否跨工具复用；材料不足以确认这些机制的成熟度。【GitHub Trending 2026-11-22 #2: obra/superpowers】 【GitHub Trending 2026-11-22 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-22 #5: cursor/plugins】 【GitHub Trending 2026-11-22 #11: google-labs-code/stitch-skills】

### 3. Firecrawl 与 last30days-skill：从获取网页走向完成信息研究任务

事实与项目声明： Firecrawl 面向智能体及 LLM 应用开发者，以统一 API 提供搜索、抓取和外部数据接入，宣称可访问 550 多个数据提供方 ，主题还包括 HTML 转 Markdown；项目主要使用 TypeScript，许可证为 AGPL-3.0。【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】

事实： last30days-skill 聚合 Reddit、X、YouTube、Hacker News、Polymarket 与网页等来源，提供近期信息检索和综合摘要，服务研究、分析及内容创作任务。材料没有提供来源覆盖、摘要准确率或引用质量评测。【GitHub Trending 2026-11-22 #10: mvanhorn/last30days-skill】

技术看点与走红推断： 两者分别位于数据接入与任务综合环节：Firecrawl 的统一接口和内容转换可能减少采集工程成本，last30days-skill 的多平台检索则可能减少研究人员切换来源的负担。外部信息的时效性和分散性，是解释这类工具吸引力的合理线索；其实际价值仍取决于来源质量、可追溯性、稳定性和使用成本。【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-22 #10: mvanhorn/last30days-skill】

### 4. app-store-compliance 与 OpenSRE：专业知识进入发布和运维流程

事实： app-store-compliance 面向移动应用开发者和发布团队，材料记载其整理了 124 类拒审模式及修复方法 ，覆盖隐私清单、Google Play Data safety，并追踪 111 个监管相关期限 。项目以 Shell 为主，同时提供 AI 编程代理技能；材料没有披露自动检查覆盖率，也没有通过审核的效果保证。【GitHub Trending 2026-11-22 #12: mjmirza/app-store-compliance】

事实与定位： OpenSRE 面向研发、DevOps 和 SRE 团队，定位为 CI/CD 可靠性智能体，主题涉及 LLM、Ollama、根因分析和故障修复。Datadog、Grafana、GitLab CI、Slack 等标签只能说明生态方向，尚不能证明集成成熟度或自动修复能力。【GitHub Trending 2026-11-22 #13: Tracer-Cloud/opensre】

技术看点与走红推断： 两者都尝试将专业知识嵌入具体工作节点：前者服务提交前检查，后者服务故障分析与修复。合规项目较明显的增星，可能与上架障碍明确、规则查询繁琐有关；OpenSRE 的潜在吸引力则是缩短排障链路。评估重点应分别落在规则更新与检查覆盖，以及诊断依据与修复验证上。【GitHub Trending 2026-11-22 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-22 #13: Tracer-Cloud/opensre】

### 5. AutoClip 与 diagram-design：AI 工具围绕可交付成果组织能力

事实： AutoClip 将长视频转成短视频，并生成字幕、封面和发布文案，适配抖音、小红书、TikTok、Reels、YouTube Shorts 等平台。项目以 Python 为主，定位包含桌面应用，标签涉及 AI Agent 和 MCP；材料未披露模型、剪辑策略或 MCP 实现。【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】

事实： diagram-design 面向 Claude Code、Codex、GitHub Copilot、Cursor 等工具提供 45 类图表 ，采用自包含 HTML 与 SVG，并强调无阴影的视觉风格。【GitHub Trending 2026-11-22 #9: cathrynlavery/diagram-design】

技术看点与走红推断： AutoClip 主要吸引内容创作者和运营团队，价值线索是将素材处理与发布准备串联起来；diagram-design 则面向需要文档配图、架构说明和可视化交付的开发者及创作者，自包含输出可能便于展示与交付。两者都让用户直接看到成品，可能因此更易传播，但材料尚不能证明时间节省、成品质量或用户留存。【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】 【GitHub Trending 2026-11-22 #9: cathrynlavery/diagram-design】

### 6. MiniMind 与 OpenVINO：训练学习和推理部署同时受到关注

项目声明： MiniMind 主打“两小时从零训练出 64M 参数模型 ”，面向模型学习者和小规模训练实验用户。材料没有对应硬件、数据规模和训练质量信息，因此“两小时”只能作为项目声明，不能作为普遍复现耗时。【GitHub Trending 2026-11-22 #4: jingyaogong/minimind】

事实： OpenVINO 面向模型推理优化和部署，主要使用 C++，覆盖视觉、自然语言处理、LLM、扩散模型、语音识别及推荐系统等方向；材料未提供性能基准。【GitHub Trending 2026-11-22 #8: openvinotoolkit/openvino】

技术看点与走红推断： MiniMind 的吸引力可能是让训练过程成为可尝试的学习任务，OpenVINO 则对应工程团队对推理执行效率和部署的需求。两者说明本期关注同时涉及理解模型训练与落实模型应用；尚不能据此推导小模型替代趋势，或判断某类硬件上的加速优势。【GitHub Trending 2026-11-22 #4: jingyaogong/minimind】 【GitHub Trending 2026-11-22 #8: openvinotoolkit/openvino】

### 7. NGINX：成熟网络基础设施仍进入热点视野

事实： nginx/nginx 是 NGINX Open Source 官方仓库，以 C 为主，覆盖 Web 服务、反向代理、负载均衡、缓存，以及邮件和 TCP/UDP 代理。材料还列出 HTTP/2、HTTP/3、QUIC、HTTPS、TLS 等主题，但不足以推导具体配置、默认能力或性能表现。【GitHub Trending 2026-11-22 #7: nginx/nginx】

目标用户与热度推断： 后端开发、运维及平台工程团队可围绕流量接入、服务分发和缓存需求评估它。此次上榜说明成熟基础设施仍受到关注，但材料没有给出版本发布或事件线索，无法确认直接走红原因，也不能据排名推导部署规模变化。【GitHub Trending 2026-11-22 #7: nginx/nginx】

## 技术趋势与信号

- 技能、插件、CLI 和 MCP 正成为代理能力组织的重要入口。事实： 本期出现开发方法技能框架、CLI 接入项目、编辑器插件规范，以及遵循 Agent Skills 标准并配合 MCP 使用的技能库。 推断： 开发者的关注正在覆盖“如何稳定复用和接入能力”，工具之间的兼容性可能成为选型因素；现有样本不足以证明接口标准已经收敛。【GitHub Trending 2026-11-22 #2: obra/superpowers】 【GitHub Trending 2026-11-22 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-22 #5: cursor/plugins】 【GitHub Trending 2026-11-22 #11: google-labs-code/stitch-skills】

- 专业领域知识正在被整理为代理可使用的工作流程。事实： 漏洞研究、应用合规和 CI/CD 可靠性项目均进入本期样本。 推断： 领域规则、案例模式和任务步骤本身正在成为工具价值的一部分，关注点也随之延伸到知识更新、执行依据和结果验证；内容数量与功能标签仍不能证明任务成功率。【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-22 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-22 #13: Tracer-Cloud/opensre】

- AI 应用呈现从数据接入到最终交付的连续工作流。事实： Firecrawl 提供外部数据入口，last30days-skill 完成检索与综合，diagram-design 和 AutoClip 输出图表、短视频及配套内容。 推断： 围绕明确结果组合多个步骤，是本期值得关注的产品方向；这些项目并不因此构成已经互通的技术链路，也没有共同的端到端效果评测。【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-22 #10: mvanhorn/last30days-skill】 【GitHub Trending 2026-11-22 #9: cathrynlavery/diagram-design】 【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】

- 技术栈按任务呈现分工，基础设施与应用编排并行受关注。事实： 样本中的研究、训练和多个智能体项目以 Python 为主，接口与插件项目使用 TypeScript；开发流程项目出现 Shell，NGINX 和 OpenVINO 分别使用 C、C++，图表项目以 HTML 为主。 推断： 这提示工作流编排、工具扩展、网络服务、推理执行和成果呈现具有不同技术需求；仓库主要语言不能代表完整架构，也不能用于推导整个开源生态的语言份额变化。【GitHub Trending 2026-11-22 #4: jingyaogong/minimind】 【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-22 #2: obra/superpowers】 【GitHub Trending 2026-11-22 #7: nginx/nginx】 【GitHub Trending 2026-11-22 #8: openvinotoolkit/openvino】 【GitHub Trending 2026-11-22 #9: cathrynlavery/diagram-design】

- 热度更适合用来确定调研优先级，采用决策仍需补充验证。事实： 本期材料提供了排名、Star、项目定位及部分规模声明，但缺少可比的任务效果、性能和使用数据。 推断： 高增星项目适合优先试用；后续应针对各自用途验证技能执行质量、信息可追溯性、集成稳定性、输出质量或部署性能，避免把关注度直接转换为生产采用结论。【GitHub Trending 2026-11-22 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-22 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-22 #10: mvanhorn/last30days-skill】 【GitHub Trending 2026-11-22 #13: Tracer-Cloud/opensre】 【GitHub Trending 2026-11-22 #16: zhouxiaoka/autoclip】 【GitHub Trending 2026-11-22 #8: openvinotoolkit/openvino】
