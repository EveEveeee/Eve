# Hi, I'm Eve 👋

[![Eve OS — AI products, agents, and thoughtful experiments](./banner.svg)](#selected-work)

<p align="center"><sub>Explore my product thinking, experiments, and open-source contributions below.</sub></p>

I'm an AI Product Manager exploring how AI fits into real workflows.\
I care about what people need, where systems fail, and how we can make them more useful.\
This is where I share what I'm building, testing, and learning.

🧪 [Selected work](#selected-work) · ✍️ [Writing](#writing) · 🌱 [About me](#about-me) · [RED / Xiaohongshu](https://www.xiaohongshu.com/user/profile/634fb9e1000000001802b00f)

---

## Selected work

Projects, product experiments, and contributions to more reliable AI workflows.

### AI product projects

- **[产品工坊 · Product Foundry](https://github.com/EveEveeee/product-foundry)** — an AI product workbench exploration: traceable requirement decisions, linked PRD and technical-plan versions, and an evidence-based review Agent POC. I define the product scope, workflow rules, and acceptance criteria, using Codex and Pi to support implementation. Currently demonstrated through separate local prototypes and POC validation. [Read the project case →](https://wangyangjuan.surge.sh/projects/product-foundry.html)

- **[Muse10 · AI 美甲](https://github.com/EveEveeee/muse10-ai-nails)** — a two-person exploration of nail-style co-creation and in-store try-on. I contribute research, product flows, interaction design, prompts, and quality criteria. Current evidence covers an interactive prototype and local backend POC; personal-hand try-on quality remains under evaluation. [Read the project case →](https://wangyangjuan.surge.sh/projects/muse10-ai-nails.html)

- **[儿童 AI 知识共创 · 豚小蓝](https://github.com/EveEveeee/child-knowledge-cocreation)** — a child-led co-creation project, currently explored through age-adapted story creation. I design the workflow, stage prompts, story context, and quality rules, with local prototypes and recorded model tests. Real family usability and the broader knowledge scope remain to be validated. [Read the project case →](https://wangyangjuan.surge.sh/projects/child-knowledge-cocreation.html)

### Open-source skills

- [Muse10 款式生成](./skills/muse10-nail-visuals/) — my maintained skill for ten-nail catalog visuals, matching wear and detail views, fixed templates, and interactive previews.

- [Evidence-led Product Teardown](./skills/evidence-led-product-teardown/) — a reusable Codex skill for evidence-gated product analysis across the user, technical, model, and data layers, with a traceable HTML deliverable.

<p>
  <a href="https://github.com/alibaba/open-code-review/issues/1492"><picture><source media="(prefers-color-scheme: dark)" srcset="./review-coverage-dark.svg"><img width="49%" src="./review-coverage-light.svg" alt="Review coverage — reporting a file-name edge case that can leave code changes unreviewed."></picture></a>
  <a href="https://github.com/alibaba/open-code-review/issues/1493"><picture><source media="(prefers-color-scheme: dark)" srcset="./scan-reliability-dark.svg"><img width="49%" src="./scan-reliability-light.svg" alt="Scan reliability — reporting a whitespace-handling issue in file discovery."></picture></a>
</p>

<p>
  <a href="https://github.com/alibaba/open-code-review/issues/894#issuecomment-5748485061"><picture><source media="(prefers-color-scheme: dark)" srcset="./session-isolation-dark.svg"><img width="49%" src="./session-isolation-light.svg" alt="Session isolation — adding evidence about cross-repository scan recovery to an existing issue."></picture></a>
  <a href="https://www.xiaohongshu.com/user/profile/634fb9e1000000001802b00f"><picture><source media="(prefers-color-scheme: dark)" srcset="./product-notes-dark.svg"><img width="49%" src="./product-notes-light.svg" alt="Product notes — sharing observations and experiments on AI products."></picture></a>
</p>

<sub>The OpenCodeReview contributions above are issue reports and a follow-up comment, prepared with AI assistance. They are not merged code fixes.</sub>

---

## 最新 AI 资讯

每日精选 AI 产品 / 模型 / Agent 动态（自动更新）。

### 2026-11-20

- **[Google 通过 Gemini API 向开发者开放世界模型 Genie 4](https://blog.google/innovation-and-ai/technology/developers-tools/genie-4-in-gemini-api/)** — 11 月 19 日宣布，继前一天发布后，Genie 4 现已通过 Gemini API（Interactions API）和 Google AI Studio 向开发者开放。开发者可用文本提示、参考图或两者生成带同步原生音频的连续 720p（24fps）世界，并用实时键盘控制与即时文本提示导航、改变天气、光照、物体或事件；由 Gemini 推理保持世界状态一致。每份输出含不可感知的 SynthID 水印。可在 Google AI Studio 试用交互画布和入门应用。 _(Google)_
- **[OpenAI 公布 Performance Factory：用 Codex Agent 自动排查并修复性能回退](https://openai.com/index/how-openai-performance-factory-keeps-chatgpt-fast/)** — 11 月 19 日介绍基于 Codex 的云端系统 Performance Factory，用于自动发现并修复性能问题。其中 Regression Workflow 在性能告警触发后由 Agent 调查、记录结论并提出修复方案供工程师审核，部署后再由另一个 Agent 核验是否恢复基线；该工作流运行三个多月以来，追踪了超过 1,700 次调查并定位了 600 多起根因，相当于每天约 17 次自动调查。人工复核 100 条根因建议中，70% 被评为准确。 _(OpenAI)_
- **[AWS Marketplace 支持通过 AgentCore 让 Agent 按次付费采购](https://aws.amazon.com/about-aws/whats-new/2026/11/marketplace-agentic-payments-agentcore/)** — 11 月 19 日宣布，AWS Marketplace 现已支持通过 x402 协议进行 agentic payments：AI Agent 可发现并购买部分软件、API、数据和内容，按次以美元支付，费用记入开发者已有的 AWS 账单，无需稳定币钱包，也无需为每个卖家单独申请 API key。用户可预先设置消费限额、批准的卖家和护栏，交易可在 AWS CloudTrail 与 AWS Cost Explorer 中审计。该能力在所有已提供 AgentCore payments 的 AWS 区域可用。 _(AWS)_

### 2026-11-19

- **[Google 发布 Gemini 4 Neon：面向复杂工程、知识工作与科学工作流的快速前沿模型](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/)** — 11 月 18 日宣布推出 Gemini 4 Neon，强调在复杂软件工程、知识工作与科学流程中更快完成端到端任务。在 Artificial Analysis Intelligence Index 的 xhigh 思考档位上总分为 61、整体排名第 3，并在 Vals Index 排名第 2；API 定价为每百万输入 token 3 美元（缓存输入 0.15 美元，折扣 95%）、输出 15 美元，上下文窗口 100 万 token。即日起在 Google AI Studio 的 Gemini API、Gemini for business，以及付费 Google AI Pro / Ultra 用户的 Google Antigravity 与 Gemini 应用中逐步上线。 _(Google)_
- **[Anthropic 公布 IPO 定价：每股 83 美元，股票代码 ANT](https://www.anthropic.com/news/anthropic-prices-initial-public-offering)** — 11 月 18 日宣布，Anthropic, PBC 的 Class A 普通股 IPO 定价为每股 83.00 美元，共发行 9.80 亿股（其中公司出售 956,351,354 股，其余 23,648,646 股由股东出售，公司不获得股东售股所得）。股票预计于 11 月 19 日在纳斯达克全球精选市场上市，代码 ANT，发行预计于 11 月 20 日交割；另给予承销商 30 天内最多加购 1.47 亿股的期权。 _(Anthropic)_
- **[OpenAI 发布 GPT-6.2 Astra 与 Sol：提升专业任务表现并降低成本](https://openai.com/index/introducing-gpt-6-2-astra-sol)** — 11 月 17 日宣布推出面向高难度项目的前沿模型 GPT-6.2 Astra，以及面向日常工作与多步 Agent 流程的高效模型 GPT-6.2 Sol。官方称 Astra 在 Agents’ Last Exam 上比 GPT-6 Astra 高 5.2 分、单任务成本不到三分之一，并比 Claude Fable 5.2 高 5.5 分、成本约为其 5%；API 中 Astra 的输入与输出价格较 GPT-6 Astra 低 20%，为每百万输入 8 美元、缓存输入 0.40 美元、输出 40 美元，Sol 仍沿用 GPT-6.1 Sol 的 API 定价。即日起向 ChatGPT Plus、Pro、Enterprise 和 Edu 用户在 ChatGPT Work 与 Codex 中开放，开发者可通过 API 使用 `gpt-6.2-astra` 与 `gpt-6.2-sol`。 _(OpenAI)_
- **[Microsoft 发布七款新模型：MAI Code 2 等以更低价格覆盖编码与多模态](https://microsoft.ai/news/microsoft-ignite-2026/)** — 11 月 17 日在 Ignite 上宣布推出七款新模型，强调以更低价格支撑可规模化的 Agent 工作。其中 MAI Code 2 在面向 GitHub Copilot 日常企业编码的四项基准上，编码质量约为 GPT-6.1 Sol 的 98%、价格约为其 40%，相对 Claude Opus 5.5 为 96% 性能、约 5% 价格，现已登陆 GitHub Copilot；MAI Code 2 Flash 面向高频日常改代码任务，已在 Copilot 上线，并在 Microsoft Foundry 提供有限预览。同期还有 MAI Image 2.7（Artificial Analysis 图像编辑榜第 1）等模型。 _(Microsoft AI)_

### 2026-11-17

- **[阿里巴巴发布旗舰模型 Qwen4-Max：原生视觉、百万 token 上下文](https://www.alibabacloud.com/en/press-room/alibaba-unveils-qwen4-max)** — 11 月 16 日宣布推出迄今最强的通义千问模型 Qwen4-Max，总参数 2.4 万亿、具备原生视觉能力与 100 万 token 上下文，编码、Agent 与视觉推理表现突出，在 Code Arena 排名第 6；新架构为稀疏 MoE，每 token 仅激活 710 亿参数。公司称在自有 Work360 评测上整体优于前代 Qwen3.8-Max，高推理模式下 token 用量减少 35%、单任务平均成本约降 60%。现已在 QwenCloud（Token Plan / API）以及 QwenWork、QwenStudio 上线，并表示将很快开源更小规模的 Qwen4 系列模型。 _(Alibaba Cloud)_
- **[腾讯发布 Hy4 flash：面向日常工作流的高速低成本模型](https://www.tencent.com/tencent-launches-hy4-flash-to-power-high-speed-cost-efficient-ai-deployment-for-everyday-workflows/)** — 11 月 16 日宣布推出 Hy 系列最新成员 Hy4 flash，总参数 2240 亿（含 640 亿 Engram 参数）、仅激活 120 亿，支持多模态输入与最长 100 万 token 上下文；官方定价约每百万输入 $0.070、输出 $0.281、缓存输入 $0.003，解码速度超过每秒 150 token。公司称在内部 WorkIndex 上单任务成本约为 Hy4 Preview 的 1/13、Hy4 的 1/20。现已登陆腾讯云 TokenHub、WorkBuddy、元宝、企业微信、QQ、ima 和 Marvis，即日起至 11 月 30 日可在 WorkBuddy 免费使用，TokenHub 标准价五折。 _(Tencent)_
- **[NVIDIA 推出 Nemotron for Science：用开源模型与数据帮助构建科学 Agent](https://nvidianews.nvidia.com/news/nvidia-introduces-nemotron-for-science-to-accelerate-discoveries-with-agents)** — 11 月 16 日宣布推出 Nemotron for Science，将开源模型 Nemotron 3.5 Super VL、科学评测、新的开源化学数据集 LitmusBench v0.2（近 5 万道化学推理题）以及后训练配方整合在一起，帮助研究者构建面向化学、蛋白质设计等任务的专业 Agent；模型与数据集已在 Hugging Face 上线，并针对 128GB DGX Spark 做了本地运行优化。阿贡国家实验室、于利希超算中心等机构正在将其用于科学发现 Agent。 _(NVIDIA)_
- **[OpenAI 与四家独立评估机构签约，启动嵌入式安全评估试点](https://openai.com/index/our-first-phase-of-embedded-assessments)** — 11 月 16 日宣布与 Apollo Research、METR、Transluce 和 Goodfire 签署协议，开展第一阶段嵌入式评估：独立专家可在较长期内深入访问内部模型与系统（视评估需要可包括检查点、源代码、训练与评测数据、监测系统等），评估训练与内部使用阶段的对齐情况和安全防护效果，以补充其安全论证，并履行白宫超级智能协议中关于独立评估安全控制的承诺。目前为试点合作，尚未发布评估结论。 _(OpenAI)_

### 2026-11-16

- **[OpenAI 推出科学博客，分享用 AI 推进科学发现的成果与方法](https://openai.com/index/our-new-blog-for-science/)** — 11 月 15 日宣布开设 OpenAI science blog，面向科学家与学术研究者，发布研究成果、模型用于科学计算 / 数据分析 / 文献与实验规划等方法实践，以及研究者的一线经验；强调会说明如何核查工作、方法在何处不足之处。 _(OpenAI)_
- **[GPT-6 Astra 协助提出标准模型的格点定义候选方案](https://openai.com/index/step-toward-defining-the-standard-model/)** — 科学博客首篇客座文章中，加州大学圣塔芭芭拉分校物理学家、OpenAI 访问科学家 Nathaniel Craig 介绍：他此前已有思路并于 10 月发表预印本，Astra 帮助把该策略落实为构造并主导了详细证明，给出标准模型的一个非微扰格点定义候选方案。该结果仍是候选，尚非可直接用于实际模拟的方法。 _(OpenAI)_
- **[印度芯片初创公司 Bharat Semi 获得 2400 万美元种子轮，押注 AI 图像传感器](https://techcrunch.com/2026/11/15/indian-chip-startup-bharat-semi-lands-24m-seed-round-as-it-eyes-global-ai-sensor-market/)** — 11 月 15 日报道，这家成立近五年、尚未实现收入的新德里公司完成 2400 万美元全股权种子轮，由 Info Edge Group、South Park Commons 与 Indus Bridge Ventures 领投，用于研发将成像、处理与 AI 能力集成在单芯片上的可编程图像传感器，并称相较传统分芯片方案有望将系统成本降低至少 70%。公司称已获得美国 General Atomics 与印度 Kaynes Semicon 的设计导入，传感器仍在开发中，目标 2027 年进入初始量产。 _(TechCrunch)_
- **[Safeguard 为每个 AI Agent 配备独立工作区：日历、会议、邮箱、消息、钱包与云盘](https://safeguard.sh/resources/press/safeguard-ai-agent-workspaces-calendar-meetings-mail-messaging-wallet-drive)** — 11 月 15 日宣布，Safeguard 平台上的每个 Agent 将拥有绑定其身份的独立日历、会议席位、邮箱、消息、钱包和云盘，并适用同一套策略、审批与审计追踪，避免借用个人账号办事导致权责不清。Agent 可在允许时段内安排日程、以具名参与者加入或主持会议，并在限额与审批规则下收发邮件、消息和付款。 _(Safeguard)_
- **[一项 API 流量统计显示：无审查模型主要用于 Agent，而非聊天角色扮演](https://huggingface.co/blog/OpenUncensored/uncensored-models-are-agent-infrastructure)** — 11 月 14 日，OpenUncensored 根据 2026 年 11 月一周、157 名付费用户向 84 个模型发出的 150,292 次请求（只记录请求方式、不记录内容）分析称：编程 Agent 占文本模型花费的 49%、请求量的 40%，其他 Agent / 自动化占花费 16%，而聊天、角色扮演和创意应用仅占花费 1.5%；典型请求约 86,612 个输入 token、仅返回 229 个输出 token，符合 Agent 循环的特征。 _(OpenUncensored / Hugging Face)_

### 2026-11-15

- **[Google 将 Google Wallet 接入 Gemini：可基于消费记录提供理财洞察](https://blog.google/innovation-and-ai/products/gemini-app/google-wallet-gemini-app/)** — 11 月 13 日宣布向美国所有 Gemini 应用用户推出：可在 Personal Intelligence 中连接 Google Wallet，通过 @Google Wallet 询问消费、订阅与预算等并生成动态图表；还可选经 Plaid 将信用卡和银行账户安全关联到 Wallet，以获得更深层洞察。连接为只读，Gemini 不能划转、管理或投资资金，用户可随时开关。已在网页与 Android / iOS 的 Gemini 应用推送。 _(Google)_
- **[llama.cpp 发布 v1.0.0：本地推理库迎来首个稳定大版本](https://huggingface.co/blog/ggml-org/llama-cpp-v1)** — 11 月 13 日，llama.cpp 与底层张量库 ggml 同步发布 v1.0.0，并开始采用语义化版本：公共 C API 的不兼容变更将提升主版本号。该版本移除了已弃用的公共 API，支持 150 多种模型架构与主流推测解码方法，并可通过 Debian、Homebrew、conda-forge、Docker、Winget 等渠道分发。 _(llama.cpp / Hugging Face)_

### 2026-11-14

- **[OpenAI 推出 ChatGPT Wallet：dots Agent 可代为安全付款](https://openai.com/index/introducing-chatgpt-wallet)** — 11 月 13 日宣布推出 ChatGPT Wallet，与 American Express、Mastercard、Visa 合作；Agent 通过支付网络代币完成付款、不接触真实卡号，每笔需用户核对商品、金额与所用卡片并以 Face ID 或指纹等安全校验批准。先通过 dots 向年满 18 岁、持有合格美国发行卡片的美国 ChatGPT Pro 订阅者开放，并同步发布面向商家的 Commerce Partner Playbook。 _(OpenAI)_
- **[Sierra 发布 Personal Agent Protocol（Poppy）1.0](https://sierra.ai/blog/releasing-poppy)** — 11 月 13 日宣布协议正式到 v1.0，个人 Agent 可通过企业 Agent、网站与 API 与商家交互，主要基于 MCP、OpenAPI、UCP，并以 OAuth 授权由用户控制权限；Shopify 已为平台全部商家启用，Meta 的 Muse 会在访问站点时优先查找 Poppy，Mercury、Synchrony、Turkish Airlines 等设计伙伴已上线，另有 60 家新伙伴加入，总数超过 100 家。 _(Sierra)_
- **[Yandex 推出 Alice AI「Do it!」：可打电话并完成日常任务](https://yandex.com/company/news/2026-11-13)** — 11 月 13 日宣布 Do it! 可将请求拆成步骤并选用工具，能代为打电话（聊天中显示实时转写）、在云端 Yandex Browser 中浏览网页并填表，并通过插件连接外卖、订花、出行、智能家居等服务；重要操作需用户批准。先向部分开通 Alice Plus 的活跃聊天用户开放，再推向全体订阅者。 _(Yandex)_
- **[Google 向外部开放 Antigravity /teamwork 多 Agent 工作流](https://research.google/blog/advancing-science-engineering-with-antigravitys-teamwork-feature/)** — 11 月 13 日公布 /teamwork 在数学、化学、系统软件与机器学习工程上的最新协作结果，并将 /teamwork、/boost 与 Deep Review 等工具向外部研究者和开发者开放；同时开放申请，为 1 万名学术研究者提供六个月最高用量档免费使用权。 _(Google Research)_
- **[Anthropic 推出 Claude Meetings：可加入视频会议并实时协作](https://claude.com/resources/articles/claude-meetings)** — 11 月 12 日宣布 beta 开始向 Team 与 Enterprise 计划推送：Claude 作为可见参与者加入通话，默认可书面回答问题并在许可下使用已连接工具，还能在会议中协作编写文档、白板等产物并整理笔记与待办；首发支持 Google Meet，其他会议平台即将跟进。beta 期间会议笔记与转写免费。 _(Anthropic)_
- **[Anthropic 推出自托管 Claude Managed Agents 私有预览](https://claude.com/resources/articles/self-hosted-claude-managed-agents)** — 11 月 12 日宣布私有 beta：企业可在自有云或本地运行完整 Managed Agents 服务（含 harness、沙箱、凭证与会话历史），并自行选择将模型请求发往 Anthropic、Amazon Bedrock、Google 的 Agent Platform、Microsoft Foundry 或自有网关；需通过 Anthropic 客户团队申请开通。 _(Anthropic)_

### 2026-11-13

- **[Google 发布 Gemini 4 Hydrogen：面向日常编码与 Agent 工作流](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-hydrogen/)** — 11 月 12 日宣布推出 Gemini 4 Hydrogen，定位日常编码与智能体工作流的快速执行；默认 high 思考档在 Artificial Analysis 指数上以 51 分超过 Argon 的 50 分（xhigh 可达 54），全 100 万 token 上下文统一计价为每百万输入 $1.50 / 输出 $7.50；并在 Google Antigravity 推出 Orchestrator，可在同一会话中动态切换 Carbon 与 Hydrogen，Terminal-Bench 4.0 上接近 Carbon 成功率，同时平均配额减少 24%、完成速度提升 19%。 _(Google)_

---

## Writing

I share observations on AI products, agents, and human–AI collaboration. I'm interested in the decisions behind a product: who it helps, what it gets wrong, and what makes it worth using.

- [Read my posts on RED / Xiaohongshu →](https://www.xiaohongshu.com/user/profile/634fb9e1000000001802b00f)
- I also write on WeChat about AI products and practical experiments.

---

## About me

- AI Product Manager with an interest in agents, AI workflows, and human–AI collaboration.
- Exploring product ideas through prototypes, evaluations, and open-source participation.
- Learning to turn observations into clear questions, testable assumptions, and better product decisions.
- Building a public record of what I try, what I learn, and what I change my mind about.

**Build** something useful · **Test** it in context · **Learn** from evidence · **Improve** with feedback

Think carefully. Build with purpose. Keep learning.
