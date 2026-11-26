# GitHub Trending

分类：github-trends

## 热点项目榜单

本期合并材料中的 13 个项目 ，按原始 GitHub Trending 日榜名次排列；未提供的名次不补录。“周期新增 Star”沿用材料快照口径，不额外推定统计时长。 Trending 排名与 Star 反映关注度，不直接等同于生产采用率、活跃用户数或软件成熟度。

| Trending 名次 | 项目 | 核心用途 | 主要语言 | 周期新增 Star | 总 Star |
| --- | --- | --- | --- | --- | --- |
| #1 | elementalsouls/Claude-BugHunter | 面向 Claude Code 的漏洞挖掘与外部红队技能包 | Python | 1,826 | 未知 |
| #2 | obra/superpowers | 智能体技能框架与软件开发方法，涵盖子智能体驱动开发 | Shell | 1,003 | 325,937 |
| #3 | HKUDS/CLI-Anything | 通过 CLI 暴露软件能力，支持智能体调用与自动化 | Python | 1,074 | 64,975 |
| #4 | jingyaogong/minimind | 从零训练小规模语言模型，面向训练学习与实验 | Python | 727 | 70,409 |
| #5 | cursor/plugins | Cursor 插件规范及官方插件 | TypeScript | 360 | 19,287 |
| #6 | firecrawl/firecrawl | 通过统一 API 提供搜索、网页抓取、数据源访问及内容提取 | TypeScript | 991 | 209,088 |
| #8 | openvinotoolkit/openvino | AI 模型推理优化与部署，覆盖视觉及生成式 AI 等场景 | C++ | 185 | 12,497 |
| #9 | cathrynlavery/diagram-design | 面向 AI 编程工具的图表设计能力，输出自包含 HTML + SVG | HTML | 802 | 72,222 |
| #10 | mvanhorn/last30days-skill | 跨平台主题研究与带来源摘要生成 | Python | 703 | 74,374 |
| #11 | google-labs-code/stitch-skills | 配合 Stitch MCP 服务器使用的标准化智能体技能 | TypeScript | 403 | 12,727 |
| #12 | mjmirza/app-store-compliance | 应用商店合规手册、提交前检查工具及 AI 代理技能 | Shell | 928 | 5,955 |
| #13 | Tracer-Cloud/opensre | 面向 CI/CD 可靠性的开源智能体 | Python | 398 | 15,239 |
| #16 | zhouxiaoka/autoclip | 将长视频转成短视频，并生成字幕、封面及发布文案 | Python | 980 | 15,541 |

表中各行来源，按名次依次为：

# 1—#4：【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】、【GitHub Trending 2026-11-25 #2: obra/superpowers】、【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】、【GitHub Trending 2026-11-25 #4: jingyaogong/minimind】

# 5—#9：【GitHub Trending 2026-11-25 #5: cursor/plugins】、【GitHub Trending 2026-11-25 #6: firecrawl/firecrawl】、【GitHub Trending 2026-11-25 #8: openvinotoolkit/openvino】、【GitHub Trending 2026-11-25 #9: cathrynlavery/diagram-design】

# 10—#16：【GitHub Trending 2026-11-25 #10: mvanhorn/last30days-skill】、【GitHub Trending 2026-11-25 #11: google-labs-code/stitch-skills】、【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】、【GitHub Trending 2026-11-25 #13: Tracer-Cloud/opensre】、【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】

关注度观察： Claude-BugHunter 在合并样本中排名最高、周期增星最多；CLI-Anything 的周期增星高于排名更靠前的 superpowers。app-store-compliance 与 AutoClip 虽分别位列 #12、#16，仍录得 928、980 个新增 Star，值得重点关注。这也说明 Trending 名次不能简单理解为新增 Star 的降序排列。【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-25 #2: obra/superpowers】 【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】

## 热点项目分析

### 1. 智能体开发框架与接入生态：superpowers、CLI-Anything、cursor/plugins、stitch-skills

事实与定位： superpowers 将技能框架与软件开发方法结合，主题涵盖头脑风暴、编码、软件开发生命周期和子智能体驱动开发。CLI-Anything 以“让软件成为 Agent-Native”为目标，通过 CLI 连接软件与智能体，并提供 CLI-Hub 入口。两者分别关注开发流程组织和软件能力接入，潜在用户包括 AI 编程工具使用者、智能体开发者与自动化工程师。材料未给出 CLI-Anything 的完整软件支持清单，也未展开 superpowers 的任务拆分和质量控制机制。【GitHub Trending 2026-11-25 #2: obra/superpowers】 【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】

cursor/plugins 提供 Cursor 插件规范及官方插件；stitch-skills 则是配合 Stitch MCP 服务器的技能库，遵循 Agent Skills 开放标准，面向 Antigravity、Gemini CLI、Claude Code、Cursor 等编码智能体。前者面向 Cursor 的扩展开发，后者强调技能进入多种智能体工作流。【GitHub Trending 2026-11-25 #5: cursor/plugins】 【GitHub Trending 2026-11-25 #11: google-labs-code/stitch-skills】

技术设计与走红推断： 这组项目的共同看点，是把软件接口、操作知识与开发步骤组织成可复用能力。CLI、插件规范、技能标准和 MCP 分属不同接入方式，可能降低工具接入与工作流定制的门槛；其中排名靠前的 superpowers 和 CLI-Anything，显示这一方向获得较强关注。不过，材料不足以比较它们的实际兼容性、集成成本和流程可靠性，也不能证实具体传播原因。【GitHub Trending 2026-11-25 #2: obra/superpowers】 【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-25 #5: cursor/plugins】 【GitHub Trending 2026-11-25 #11: google-labs-code/stitch-skills】

### 2. 专业知识进入智能体工作流：Claude-BugHunter、app-store-compliance、opensre

Claude-BugHunter｜事实： 项目面向漏洞赏金研究员、渗透测试人员及外部红队，将安全测试知识组织为 Claude Code 技能包。材料列出 84 项技能、15 个斜杠命令、681 个已披露报告模式，覆盖 24 类核心漏洞 ，并包含企业身份与基础设施攻击矩阵。其设计看点是“技能—命令—报告模式”的知识组织方式；这些数量说明内容覆盖，不能证明漏洞发现效果。【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】

app-store-compliance｜事实： 项目面向 iOS、Android 开发者及发布团队，整理 124 类拒审模式及修复方案 ，提供隐私清单、Google Play 数据安全申报等提交前检查，并跟踪 112 项监管期限 。开放手册、Shell 工具与 AI 代理技能的组合，尝试把合规知识带入实际发布流程；材料没有给出检查准确率或过审效果。【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】

opensre｜事实： 项目定位为面向 CI/CD 可靠性的开源智能体，主要语言为 Python，主题涉及告警、可观测性、事件管理、根因分析与修复，潜在用户是 DevOps、SRE 和流水线维护团队。材料同时出现 LLM、Ollama 主题，但摘要在集成信息处截断，无法据此确认具体工具集成或自动修复能力。【GitHub Trending 2026-11-25 #13: Tracer-Cloud/opensre】

走红推断： 这组项目都对应明确的专业任务：发现安全问题、减少发布阻碍、维护流水线可靠性。把领域经验包装成可调用的技能或检查流程，可能让用户更容易理解其价值。Claude-BugHunter 与 app-store-compliance 的明显增星支持“相关方向受到关注”，但不支持“专业判断已可可靠自动化”的结论。【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-25 #13: Tracer-Cloud/opensre】

### 3. 信息获取与研究自动化：Firecrawl、last30days-skill

事实与定位： Firecrawl 为智能体、LLM 应用及网页数据处理提供统一 API，覆盖搜索、抓取、数据源访问与内容提取，支持 HTML 转 Markdown。项目描述宣称可访问 550 多个数据提供方 ，但材料没有提供完整覆盖清单或独立验证。last30days-skill 则围绕主题检索 Reddit、X、YouTube、Hacker News、Polymarket 及网页内容，生成有来源依据的摘要，潜在用户包括研究人员、内容创作者和开发者。【GitHub Trending 2026-11-25 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-25 #10: mvanhorn/last30days-skill】

技术设计与走红推断： Firecrawl 着重统一信息入口和内容格式，last30days-skill 着重把检索与整理包装为研究任务。它们分别体现信息接入层和任务交付层的价值，可能因降低人工搜索、清洗和归纳负担而受到关注。材料未显示二者存在直接集成关系，也未披露 last30days-skill 的来源验证机制，因此不能仅凭“带引用”判断摘要可靠性。【GitHub Trending 2026-11-25 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-25 #10: mvanhorn/last30days-skill】

### 4. 面向具体交付物的 AI 工具：diagram-design、AutoClip

diagram-design｜事实与设计： 项目面向 Claude Code、Codex、GitHub Copilot、Cursor 等 AI 编程工具，覆盖 52 种图表类型 ，采用自包含 HTML + SVG 输出，并强调无阴影的视觉风格。其潜在用户是需要技术文档、架构图和可视化内容的开发者与作者。以 Web 标准承载输出、同时约束视觉风格，是值得关注的设计选择；材料没有提供具体兼容性与用户案例。【GitHub Trending 2026-11-25 #9: cathrynlavery/diagram-design】

AutoClip｜事实与设计： 项目是以 Python 为主要语言的 AI 视频剪辑桌面工具，可将播客、访谈、课程等长视频转为短视频，并生成字幕、封面和发布文案，面向内容创作者与社交媒体运营人员。描述涉及链接一键出片及多个短视频平台适配；标签包含 AI Agent 和 MCP，但材料没有披露模型、剪辑架构或协议实现细节。【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】

走红推断： 两者都将能力落在容易展示的产物上：可用图表和包装后的短视频。这种明确的交付形式可能降低用户理解成本，也可能增强传播吸引力。AutoClip 在较后名次仍取得 980 个周期新增 Star，值得持续观察；不过，热度不能证明剪辑质量、图表质量或效率提升幅度。【GitHub Trending 2026-11-25 #9: cathrynlavery/diagram-design】 【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】

### 5. 模型训练与推理工程：MiniMind、OpenVINO

MiniMind｜事实： 项目主打“两小时从零训练自己的 64M 参数模型 ”，面向希望学习训练流程的开发者、学生与研究者。其看点是小规模模型与从零训练体验，为理解模型训练提供实践入口。但“两小时”属于项目宣称，材料缺少硬件、数据规模与评测条件，不能据此推定实际成本和模型质量。【GitHub Trending 2026-11-25 #4: jingyaogong/minimind】

OpenVINO｜事实： 项目是英特尔主导的开源 AI 推理优化与部署工具包，主要语言为 C++，覆盖视觉、NLP、LLM、扩散模型、语音识别与推荐系统等场景，面向需要优化模型运行效率和硬件部署的工程团队。相关主题同时包含传统视觉与生成式 AI 工作负载。【GitHub Trending 2026-11-25 #8: openvinotoolkit/openvino】

走红推断： MiniMind 的清晰实验目标可能吸引希望理解模型内部过程的开发者；OpenVINO 则对应模型落地时的推理效率与部署需求。两者提示训练学习和运行工程仍有独立关注度，但本期材料无法确认增星是否由版本发布、性能突破或特定传播事件驱动。【GitHub Trending 2026-11-25 #4: jingyaogong/minimind】 【GitHub Trending 2026-11-25 #8: openvinotoolkit/openvino】

## 技术趋势与信号

### 1. 开发范式：智能体能力正被组织为技能、规范和流程

事实： 样本包含开发方法框架、CLI 接入、插件规范、标准化技能，以及安全和合规领域技能。 推断： 这表明本期关注点明显涉及“如何让智能体持续参与任务”：既需要调用接口，也需要可复用步骤和领域知识。它支持工作流工程受到关注的判断，尚不足以证明这些流程已具备稳定的端到端执行能力。【GitHub Trending 2026-11-25 #2: obra/superpowers】 【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-25 #5: cursor/plugins】 【GitHub Trending 2026-11-25 #11: google-labs-code/stitch-skills】 【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】

### 2. AI 应用：价值表达更贴近具体任务与交付物

事实： 研究摘要、图表、短视频及其配套文案，都是本期项目明确指向的输出。 推断： 围绕完整交付物组织功能，可能成为 AI 工具吸引用户的一条路径；用户价值也延伸到检索、加工、包装与整理等环节。材料没有量化效率数据，因此不能判断实际节省了多少人力。【GitHub Trending 2026-11-25 #10: mvanhorn/last30days-skill】 【GitHub Trending 2026-11-25 #9: cathrynlavery/diagram-design】 【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】

### 3. 工具基础设施：信息接入、接口复用和运行可靠性同时受到关注

事实： Firecrawl 统一外部信息入口，CLI-Anything 与 stitch-skills 关注工具接入，opensre 面向 CI/CD 可靠性，OpenVINO 面向推理优化与部署。 推断： 智能体应用的工程需求正在覆盖数据、工具、运维和模型运行等多个环节。这些项目共同构成值得观察的配套能力方向，但材料未证明它们已形成互通的技术体系。【GitHub Trending 2026-11-25 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-25 #3: HKUDS/CLI-Anything】 【GitHub Trending 2026-11-25 #11: google-labs-code/stitch-skills】 【GitHub Trending 2026-11-25 #13: Tracer-Cloud/opensre】 【GitHub Trending 2026-11-25 #8: openvinotoolkit/openvino】

### 4. 技术栈：按任务选型，应用编排与性能工程并存

事实： 本期 Python 项目涉及安全、研究、训练、运维与视频；TypeScript 出现在数据 API、插件和技能生态；Shell 用于开发流程与检查工具；HTML 用于图表产物；C++ 用于推理工具包。 推断： 该样本呈现出按任务选择技术栈的特点，应用编排、内容表达与运行性能各有不同需求。仓库主要语言不足以还原完整架构，也不能据此判断整个生态的语言份额变化。【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-25 #4: jingyaogong/minimind】 【GitHub Trending 2026-11-25 #6: firecrawl/firecrawl】 【GitHub Trending 2026-11-25 #2: obra/superpowers】 【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-25 #9: cathrynlavery/diagram-design】 【GitHub Trending 2026-11-25 #8: openvinotoolkit/openvino】

### 5. 关注度信号：专业痛点与易展示成果都值得跟踪

事实： Claude-BugHunter 位列榜首，app-store-compliance 和 AutoClip 则在较后名次获得明显增星。 推断： 明确的专业痛点与直观的成果展示，都可能帮助项目获得关注。要进一步判断其工程价值，仍需结合项目实际效果、持续维护及真实使用证据；本期 Trending 与 Star 快照本身无法回答这些问题。【GitHub Trending 2026-11-25 #1: elementalsouls/Claude-BugHunter】 【GitHub Trending 2026-11-25 #12: mjmirza/app-store-compliance】 【GitHub Trending 2026-11-25 #16: zhouxiaoka/autoclip】
