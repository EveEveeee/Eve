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

### 2026-11-25

- **[Meta 个人 AI 智能体 Muse 登陆英国，可代为完成购物与出行等任务](https://about.fb.com/news/2026/11/introducing-muse-in-the-uk-a-personal-ai-agent-you-control/)** — 11 月 23 日，Meta 宣布其个人 AI 智能体 Muse 在英国上线：18 岁及以上用户可通过 iOS、Android、muse.ai 和 WhatsApp 免费使用（另有可选订阅）。Muse 由 Meta Superintelligence Labs 首款面向真实 agent 任务的模型 Muse Spark 驱动，可在用户批准后发送邮件、下单或规划行程，且无法查看密码或银行卡信息；每位用户的 Muse 拥有独立的云端虚拟电脑，登录与信息不与 Meta 其他服务混用。上线同时接入 Marks & Spencer、ASOS、Currys、easyJet、Jet2 等英国品牌与零售商，结账可使用 Stripe 的 Onelink 或 Shopify 的 Shop Pay。 _(Meta)_
- **[Anthropic 推出 Claude Ship：可按仓库策略自动完成 PR 审查、修复与批准](https://claude.com/resources/articles/introducing-claude-ship)** — 11 月 23 日，Anthropic 发布 Claude Ship（目前为 beta）：由已正式可用的 Code Review，以及仍处 beta 的 PR Steward 与 Claude Approvals 组成，可对 GitHub 仓库中的拉取请求进行审查、修复失败检查与冲突，并按仓库内的策略文件决定哪些变更可由 Claude 批准。开发者可在 Claude Code 中使用 `/ship` 命令；管理员也可按仓库开启并设置审查深度与支出上限。该能力面向 Claude Team 与 Enterprise 计划，符合条件的 Enterprise 组织可在 2027 年 1 月 15 日前领取至少 1 万美元额度（须在领取后 30 天内使用）；启用 Zero Data Retention、HIPAA 配置或客户托管加密密钥的组织暂不可用。 _(Anthropic)_
- **[Cognition 发布 SWE-2.1：编码与网络安全能力提升，并推出 10 倍速 Ultrafast 版本](https://cognition.com/blog/swe-2-1)** — 11 月 24 日，Cognition 发布 SWE-2.1，该模型在 Kimi K3 上以纯强化学习训练，是对 SWE-2 的重大升级。官方评测中，Terminal-Bench 4.1 由 24.2 升至 50.0，FrontierCode 2.0 由 24.1 升至 41.3；在网络安全方面，ExploitBench 达到 80%，ExploitGym 上按既定漏洞利用路径捕获 flag 的成功率为 27.3%。公司同时为 Devin Security 推出防护更宽松的 SWE-2.1 Cyber，并与 Cerebras 合作发布同模型的 SWE-2.1 Ultrafast，官方称推理速度约为原来的 10 倍。 _(Cognition)_
- **[Google DeepMind 用 Gemini 4 智能体团队改进量子算法，聚变模拟计算成本降低 11.8 倍](https://deepmind.google/blog/finding-faster-quantum-algorithms-with-agents-and-formal-verification/)** — 11 月 23 日，Google DeepMind 与 Google Quantum AI 合作发表研究：由多支独立的 Gemini 4 智能体团队改进已知量子算法，并用 Lean 形式化验证每项结果；各团队每 4 小时在虚拟会议中交流比较方案。在惯性约束聚变的一项关键计算上，智能体将综合量子比特与操作次数的计算成本降低 11.8 倍，所需纠错量子比特内存由 5,650 个降至 4,338 个。官方同时开源 Lean 库、问题规格与已验证解，并指出这些算法在科学模拟中仍可能超出首批纠错量子计算机的资源能力。 _(Google DeepMind)_
- **[蚂蚁 inclusionAI 开源 Ling-3.2-air：1240 亿总参数原生多模态 MoE，工作流自动化得分大幅提升](https://huggingface.co/inclusionAI/Ling-3.2-air)** — 11 月 24 日，蚂蚁集团 inclusionAI 发布开源权重模型 Ling-3.2-air，沿用 Ling-3.0-flash-VL 的原生多模态架构，支持文本、图像与视频输入，采用混合线性 MoE，总参数 1240 亿、每个 token 激活 55 亿参数。与上一代相比，AutomationBench-AA 由 15.7% 升至 61%，专业文档任务 GDP.pdf 全通过率由 8.4% 升至 16%，AA-Briefcase v1.1 的 Elo 由 987 升至 1340，Terminal-Bench 4.0 通过率由 0% 升至 27%。官方推荐以 256K 上下文部署，并提供 SGLang 与 vLLM 的推理方案。 _(inclusionAI / Hugging Face)_

### 2026-11-24

- **[智谱发布旗舰模型 GLM-5.4：首个 Loop Transformer，宣称智能水平可比 2 万亿至 3 万亿参数模型](https://z.ai/blog/glm-5.4)** — 11 月 23 日，智谱（Z.ai）发布首款采用 Loop Transformer 架构的旗舰模型 GLM-5.4：在约 7500 亿参数规模上，将 GLM-5 基座中的 28 层循环执行两次，以加深推理而不增加参数，官方称其智能水平可与 2 万亿至 3 万亿参数级模型相比。公司称非高峰推理速度最高约每秒 200 token、高峰负载下维持每秒 70 至 80 token；现已在 GLM Coding Plan、ZCode 和 Z.ai Chat 提供，API 将在安全评估后开放，并计划在完成安全加固后开源权重。 _(Z.ai)_
- **[OpenAI 与思科联合推出开源运行时 Shirudo，可在不停机的情况下为 Linux 系统加临时防护](https://openai.com/index/introducing-shirudo)** — 11 月 23 日，OpenAI 与思科发布开源项目 Shirudo（日语「盾」）：基于 eBPF，帮助安全团队在正式补丁上线前，为正在运行的 Linux 系统部署经测试的临时防护（shield），无需重启服务。在一次受控测试中，由 Codex 生成的 shield 在 Elasticsearch 服务保持运行的情况下阻断了 Java4Shell 利用尝试。Shield 在加载前需经密码学签名与校验，并可用 TPM 记录防护的加载与移除；智能体可协助研判漏洞、编写并验证 shield，但部署仍由安全人员批准。 _(OpenAI)_
- **[亚马逊签约收购 Decart 优化栈技术并引入其创始团队，以提升自研芯片与推理效率](https://www.aboutamazon.com/news/company-news/amazon-decart-ai-optimization)** — 11 月 23 日，亚马逊宣布已签署协议，收购 Decart Optimization Stack（DOS）的专有技术，并引入联合创始人 Dean Leitersdorf、Moshe Shalev、Orian Leitersdorf 及其 AI 研究与工程团队。亚马逊称自 2025 年起双方已在 Trainium 上合作，该技术将用于进一步优化推理与自研芯片性能，使客户能以更低成本更快地训练和运行模型；交易尚待包括监管批准在内的交割条件完成。 _(Amazon)_
- **[Gemini API 上线文件切片控制，可按需加载文档、表格与音视频片段](https://blog.google/innovation-and-ai/technology/developers-tools/file-slicing-controls/)** — 11 月 23 日，Google 宣布 Gemini API 新增原生文件切片控制，开发者可指定只需模型查看的页面、表格单元格区域或音视频片段，由服务端完成切片、渲染和分词，并且只为实际检视的部分计费。同时新增对 Microsoft Office 与 OpenDocument 格式的原生上传；Agent 也可在函数返回中直接指定要检视的文件片段。该能力面向所有 Gemini 4 模型，在 Google AI Studio 和 Gemini 平台提供。 _(Google)_

### 2026-11-23

- **[OpenAI 首席科学家提议以困惑度为共同指标，并为前沿模型开发设定行业上限](https://openai.com/index/perplexity-and-intelligence/)** — 11 月 22 日，OpenAI 首席科学家 Jakub Pachocki 发表文章，主张将困惑度（或等价的交叉熵损失）作为比较各实验室预训练进展、并据此制定共享安全标准的共同指标，同时公布了公司内部的困惑度测量：GPT-3.5 约为 0.99、GPT-4 约为 0.91，当前损失已低于 0.8，并在网络安全和数学等领域出现变革性能力。他预计进入约 0.68–0.7 的对数困惑度区间时还会出现新的变革性能力，并提议各前沿模型开发者共同承诺：在对模型行为的理解和监测达到具体里程碑（例如开发出思维链监测的后继方案）之前，不以困惑度等关键指标越过约定上限。 _(OpenAI)_
- **[印度 Sarvam 发布开源权重模型 Sarvam-105B-1711，面向客服、语音与 Agent 任务](https://www.sarvam.ai/blogs/sarvam-105b-1711)** — 11 月 22 日，Sarvam AI 发布 Sarvam 105B 的新开源权重点，基于升级后的 B200 基础设施训练，定位为面向客服、语音 Agent 和工具调用等大规模任务的 Flash-Lite 模型。与 2 月版本相比，八项对话式 Agent 基准的平均分从 42.6 升至 73.9，混合定价由每百万 token 0.44 美元降至 0.15 美元；权重已在 Hugging Face 提供 BF16 以及约 65GB、可在单张工作站 GPU 上运行的 NVFP4 版本。 _(Sarvam AI)_
- **[蚂蚁集团领投中国具身智能公司至简动力 1 亿美元 Pre-A 轮，估值 16 亿美元](https://news.bloomberglaw.com/capital-markets/ant-group-bets-on-simplexity-to-thrive-in-chinas-humanoid-race)** — 11 月 22 日，Bloomberg 报道，杭州具身智能创业公司至简动力（Simplexity Robotics）完成 1 亿美元 Pre-A 轮融资，由马云支持的蚂蚁集团领投，投后估值 16 亿美元；阿里巴巴、腾讯、红杉中国（HongShan Capital）和蓝驰创投等现有投资方跟投。董事长兼联合创始人王凯向 Bloomberg 证实了本轮估值与投资方信息。 _(Bloomberg)_
- **[AWS Quick 支持以插件一次性打包 Agent、技能、连接器与流程](https://aws.amazon.com/about-aws/whats-new/2026/11/aws-quick-plugins-bundle-agents-skills-connectors-flows/)** — 11 月 21 日宣布，AWS Quick 新增插件（plugins），可将面向特定任务、角色或场景的 Agent、技能、连接器和流程打包，用户一次安装即可获得完成该工作所需的能力。用户可浏览并安装 AWS 官方插件（如日程与会议助手、销售开发插件），目前有 100 多项技能和插件覆盖日常效率、财务营销法务等岗位及常用商务应用；也可在对话中描述工作内容，让 Quick 组装自定义插件并分享给团队。该能力已在所有提供 AWS Quick 的区域上线。 _(AWS)_
- **[Google 向印度理工学院卡拉格普尔分校提供 500 万美元，用于 AI 研究与人才培养](https://blog.google/intl/en-in/company-news/supporting-ai-research-and-talent-development-with-iit-kharagpur/)** — 11 月 21 日，Google 印度团队宣布向 IIT Kharagpur 提供 500 万美元资金，支持其推进高级 AI 研究并培养科学与技术人才。资金将用于三个方向：面向印度语言、材料科学、农业和教育科技等实际问题的 AI 研究；面向学生、教师和师资的 AI 培训与课程建设；以及提升校园 AI 框架与工具能力。 _(Google)_
- **[联合国常规武器公约会议未能就自主武器达成具有法律约束力的谈判授权](https://www.theguardian.com/technology/2026/nov/21/international-talks-control-ai-autonomous-weapons-collapse)** — 11 月 21 日，《卫报》报道，在日内瓦举行的联合国《特定常规武器公约》（CCW）会议经过通宵谈判，未能就制定具有法律约束力的自主武器国际条约达成谈判授权。由于该论坛需 128 个缔约方协商一致，会议最终通过较弱授权，要求各国“以协商一致方式拟订”一项可能不具法律义务的文书；报道称俄罗斯以拖延策略带头反对，美国等一些投入 AI 作战的军事大国也不愿承诺有约束力的议定书。 _(The Guardian)_

### 2026-11-22

- **[Lean 与 Mathlib 社区确认 Alpöge 的黎曼猜想 Lean 形式化证明正确](https://leanprover-community.github.io/blog/posts/riemann-hypothesis/)** — 11 月 21 日，Lean 与 Mathlib 社区发表联合声明（获 Lean FRO 与 Mathlib Initiative 背书）：对 Levent Alpöge 于 11 月 20 日发布、约 1700 万行的黎曼猜想 Lean 证明库有充分信心，认定其正确。社区已核验该库可正确编译、所证定理与 Mathlib 中的 RiemannHypothesis 陈述一致，并由 Lean 官方内核及多个独立证明检查器验证导出证明有效。Alpöge 此前表示该证明在 Claude 协助下完成，可读性写作成稿仍待后续。 _(Lean / Mathlib Community)_
- **[OpenAI 公布对抗性蒸馏防护：GPT-6.2 受保护推理提取成功率降至 0.2%](https://openai.com/index/combatting-adversarial-distillation/)** — 11 月 20 日发布，介绍如何检测并阻断未经授权的对抗性蒸馏，并加强对受保护推理（思维链）的防护。在内部自适应红队评估中，从更早一次请求中恢复受保护推理的平均攻击成功率，从 GPT-6 Astra 原有防护下的 54.0%，降至 GPT-6.2 Astra 更新防护后的 0.2%。OpenAI 称新防护将推理与对话前缀绑定，并结合对抗测试、模型训练、分类器与 API 层保护。 _(OpenAI)_
- **[METR 发布 2026 年四季能力更新：前沿模型 50% 时间跨度约 40 小时](https://metr.org/blog/2026-11-20-q4-2026-capability-update/)** — 11 月 20 日公布对公开模型（截至 GPT-6 Astra 与 Opus 5.5）的评测。在合并的 TH1.1 与 TH2 任务集上，50% 时间跨度约每 3.6 个月翻倍；GPT-6 Astra 为 40 小时（95% 置信区间 13–2645 小时），Opus 5.5 为 39 小时（12–1253 小时）。报告同时指出，在缺少清晰经验反馈的判断类任务上，模型仍弱于人类专家，且对是否会在未来数年出现剧烈的 AI 研发加速仍有较大不确定性。 _(METR)_
- **[AWS Quick 推出网页版：浏览器中可创建并调度同一套 Agent 与技能](https://aws.amazon.com/about-aws/whats-new/2026/11/aws-quick-launches-new-web-experience-updated-browser-extension-microsoft-365-add-ins/)** — 11 月 21 日宣布，AWS Quick 网页应用将桌面端体验带到浏览器，可创建、分享并使用与桌面相同的 Agent、技能和连接器；对话、Agent 与文件在网页、桌面和移动端同步，从网页启动或调度的 Agent 在关闭浏览器后仍会继续运行，并可在 Mission Control 查看进度与待确认事项。同时更新了浏览器扩展，以及面向 Word、Excel、PowerPoint 和 Outlook 的 Microsoft 365 加载项。已在美东（弗吉尼亚北部）、美西（俄勒冈）、欧洲（法兰克福、爱尔兰、伦敦）和亚太（悉尼、东京）等区域上线。 _(AWS)_
- **[Amazon Bedrock Web Search 新增五门语言并支持按国家偏向检索](https://aws.amazon.com/about-aws/whats-new/2026/11/web-search-amazon-bedrock/)** — 11 月 21 日宣布，用于为 Agent 和应用提供带引用的即时网页信息的 Web Search，现已在 Amazon Bedrock AgentCore 与 Amazon Bedrock 上新增西班牙语、法语、德语、意大利语和日语，以及非美国英语支持，结果可来自当地语言来源。同时新增可选的国家字段，传入 ISO 3166-1 alpha-2 代码（如 JP、DE）即可偏向特定国家的来源。现有客户自动获得新语言能力、无需改代码，各语言定价相同；查询在调用区域处理。 _(AWS)_

### 2026-11-21

- **[Google 在 Mac 版 Gemini 应用推出 Computer Use，可代为操作桌面应用和网页](https://blog.google/innovation-and-ai/products/gemini-app/computer-use-mac/)** — 11 月 19 日宣布，Mac 版 Gemini 应用新增 Computer Use：用户描述任务后，Gemini 可在独立后台窗口中点击、输入、浏览菜单并填写表单，完成跨本地文件、桌面应用和网页的多步操作，主屏幕与光标不受占用；用户可选择应用权限、观看实时预览，并在关键操作前批准。即日起以英语向美国的 Google AI Plus / Pro / Ultra 个人用户推出，需搭载 Apple Silicon 且运行 macOS Sequoia 15.0 或更高版本。 _(Google)_
- **[Gemini API 预览上线 Tool Retrieval：按需加载工具参数模式](https://blog.google/innovation-and-ai/technology/developers-tools/gemini-api-tool-retrieval/)** — 11 月 19 日宣布，Tool Retrieval 已在 Gemini Interactions API 中以预览形式推出。当 Agent 连接数十甚至上百个工具时，不必在每次请求中发送完整参数 schema，而是将工具库待命、仅在当前任务需要时加载，以降低输入 token 与延迟，并在候选工具增多时保持选择准确率。启用方式为在请求中加入 `tool_search` 工具，并对暂缓加载的工具设置 `defer_loading: true`；模型仍能看到这些工具的名称与描述，需要时由 API 在同一次请求中加载完整 schema 并完成调用。该能力对 Gemini 3.6 及之后的模型（含 Gemini 4 全系列）在 Interactions API 中可用，无单独收费。 _(Google)_
- **[Anthropic 宣布 IPO 与同步私募交割完成，合计募集约 1195 亿美元](https://www.anthropic.com/news/ipo-close)** — 11 月 20 日宣布，Anthropic, PBC 已完成首次公开发行交割：共发行 11.27 亿股 Class A 普通股，定价每股 83.00 美元，含承销商全额行使的 1.47 亿股超额配股权；其中公司出售 1,103,351,354 股，股东出售 23,648,646 股。IPO 总募集资金约 935 亿美元（公司获得约 916 亿美元，未获得股东售股所得）。股票已于 11 月 19 日在纳斯达克全球精选市场以代码 ANT 上市。同期向 AMD、Broadcom、Google、Micron、Microsoft、NVIDIA 和 TSMC Partners 私募出售 313,253,007 股 Class N 普通股，金额约 260 亿美元；IPO（含股东售股）与私募合计总募集资金约 1195 亿美元（扣除承销折扣与发行费用前）。 _(Anthropic)_
- **[OpenAI 发布 MedChemBench：评估模型在药物化学推理中的表现](https://openai.com/index/introducing-medchembench/)** — 11 月 20 日推出包含 99 道题的评测基准 MedChemBench，考察模型能否结合分子结构与实验证据解释结果、比较化合物并预测性质。题目来自 117 篇论文和专利，覆盖 761 种不同分子结构。在 xhigh 推理档位上，GPT-6.2 Astra 获得 84.5% 的可得分数，高于 GPT-6 Astra 的 83.3%、GPT-6.1 Sol 的 82.0% 和 GPT-5.6 Sol 的 58.2%。官方同时指出，该评测基于历史证据而非真实药物发现，不能证明模型能发现新药或改善实验室决策。 _(OpenAI)_
- **[AWS DevOps Agent 扩展聊天能力：支持 MCP 客户端与 Slack、Teams](https://aws.amazon.com/about-aws/whats-new/2026/11/devops-agent-new-chat-capabilities/)** — 11 月 20 日宣布，AWS DevOps Agent 的聊天能力现已扩展到 Kiro、Claude Code 等 MCP 客户端，以及 Slack 和 Microsoft Teams。借助 MCP，Agent 可按指令调用 GitHub、GitLab、Azure DevOps、ServiceNow 和 PagerDuty 等工具，直接在常用聊天界面完成工作流自动化。此次还支持按事故自动创建 Slack 代码频道、在 Teams 中双向聊天，并为 Agent 提供可执行脚本和访问网络的计算沙箱；用户可在所有支持的平台上重命名和归档聊天。 _(AWS)_

### 2026-11-20

- **[Google 通过 Gemini API 向开发者开放世界模型 Genie 4](https://blog.google/innovation-and-ai/technology/developers-tools/genie-4-in-gemini-api/)** — 11 月 19 日宣布，继前一天发布后，Genie 4 现已通过 Gemini API（Interactions API）和 Google AI Studio 向开发者开放。开发者可用文本提示、参考图或两者生成带同步原生音频的连续 720p（24fps）世界，并用实时键盘控制与即时文本提示导航、改变天气、光照、物体或事件；由 Gemini 推理保持世界状态一致。每份输出含不可感知的 SynthID 水印。可在 Google AI Studio 试用交互画布和入门应用。 _(Google)_
- **[OpenAI 公布 Performance Factory：用 Codex Agent 自动排查并修复性能回退](https://openai.com/index/how-openai-performance-factory-keeps-chatgpt-fast/)** — 11 月 19 日介绍基于 Codex 的云端系统 Performance Factory，用于自动发现并修复性能问题。其中 Regression Workflow 在性能告警触发后由 Agent 调查、记录结论并提出修复方案供工程师审核，部署后再由另一个 Agent 核验是否恢复基线；该工作流运行三个多月以来，追踪了超过 1,700 次调查并定位了 600 多起根因，相当于每天约 17 次自动调查。人工复核 100 条根因建议中，70% 被评为准确。 _(OpenAI)_
- **[AWS Marketplace 支持通过 AgentCore 让 Agent 按次付费采购](https://aws.amazon.com/about-aws/whats-new/2026/11/marketplace-agentic-payments-agentcore/)** — 11 月 19 日宣布，AWS Marketplace 现已支持通过 x402 协议进行 agentic payments：AI Agent 可发现并购买部分软件、API、数据和内容，按次以美元支付，费用记入开发者已有的 AWS 账单，无需稳定币钱包，也无需为每个卖家单独申请 API key。用户可预先设置消费限额、批准的卖家和护栏，交易可在 AWS CloudTrail 与 AWS Cost Explorer 中审计。该能力在所有已提供 AgentCore payments 的 AWS 区域可用。 _(AWS)_

### 2026-11-19

- **[Google 发布 Gemini 4 Neon：面向复杂工程、知识工作与科学工作流的快速前沿模型](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-neon/)** — 11 月 18 日宣布推出 Gemini 4 Neon，强调在复杂软件工程、知识工作与科学流程中更快完成端到端任务。在 Artificial Analysis Intelligence Index 的 xhigh 思考档位上总分为 61、整体排名第 3，并在 Vals Index 排名第 2；API 定价为每百万输入 token 3 美元（缓存输入 0.15 美元，折扣 95%）、输出 15 美元，上下文窗口 100 万 token。即日起在 Google AI Studio 的 Gemini API、Gemini for business，以及付费 Google AI Pro / Ultra 用户的 Google Antigravity 与 Gemini 应用中逐步上线。 _(Google)_
- **[Anthropic 公布 IPO 定价：每股 83 美元，股票代码 ANT](https://www.anthropic.com/news/anthropic-prices-initial-public-offering)** — 11 月 18 日宣布，Anthropic, PBC 的 Class A 普通股 IPO 定价为每股 83.00 美元，共发行 9.80 亿股（其中公司出售 956,351,354 股，其余 23,648,646 股由股东出售，公司不获得股东售股所得）。股票预计于 11 月 19 日在纳斯达克全球精选市场上市，代码 ANT，发行预计于 11 月 20 日交割；另给予承销商 30 天内最多加购 1.47 亿股的期权。 _(Anthropic)_
- **[OpenAI 发布 GPT-6.2 Astra 与 Sol：提升专业任务表现并降低成本](https://openai.com/index/introducing-gpt-6-2-astra-sol)** — 11 月 17 日宣布推出面向高难度项目的前沿模型 GPT-6.2 Astra，以及面向日常工作与多步 Agent 流程的高效模型 GPT-6.2 Sol。官方称 Astra 在 Agents’ Last Exam 上比 GPT-6 Astra 高 5.2 分、单任务成本不到三分之一，并比 Claude Fable 5.2 高 5.5 分、成本约为其 5%；API 中 Astra 的输入与输出价格较 GPT-6 Astra 低 20%，为每百万输入 8 美元、缓存输入 0.40 美元、输出 40 美元，Sol 仍沿用 GPT-6.1 Sol 的 API 定价。即日起向 ChatGPT Plus、Pro、Enterprise 和 Edu 用户在 ChatGPT Work 与 Codex 中开放，开发者可通过 API 使用 `gpt-6.2-astra` 与 `gpt-6.2-sol`。 _(OpenAI)_
- **[Microsoft 发布七款新模型：MAI Code 2 等以更低价格覆盖编码与多模态](https://microsoft.ai/news/microsoft-ignite-2026/)** — 11 月 17 日在 Ignite 上宣布推出七款新模型，强调以更低价格支撑可规模化的 Agent 工作。其中 MAI Code 2 在面向 GitHub Copilot 日常企业编码的四项基准上，编码质量约为 GPT-6.1 Sol 的 98%、价格约为其 40%，相对 Claude Opus 5.5 为 96% 性能、约 5% 价格，现已登陆 GitHub Copilot；MAI Code 2 Flash 面向高频日常改代码任务，已在 Copilot 上线，并在 Microsoft Foundry 提供有限预览。同期还有 MAI Image 2.7（Artificial Analysis 图像编辑榜第 1）等模型。 _(Microsoft AI)_

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
