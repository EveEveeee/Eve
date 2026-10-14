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

### 2026-10-14

- **[Google：Gemini 4 Argon 向开发者与 Pro/Ultra 用户开放](https://blog.google/innovation-and-ai/models-and-research/gemini-models/introducing-gemini-4-argon/)** — 新前沿模型即日起经 API、Gemini 应用与 Antigravity 提供，限时价为每百万输入/输出 token 2 美元与 10 美元，并称在 Vals Index 排名第一。 _(Google)_
- **[OpenAI 与 Anthropic 呼吁英国以立法约束前沿 AI 安全](https://www.wired.com/story/openai-and-anthropic-tell-british-lawmakers-regulate-us/)** — 两家公司在英国议会听证会上表示自愿承诺已不够，支持强制事故报告等法定框架；Google DeepMind 与 Meta 未支持新立法。 _(WIRED)_
- **[美国运通推出框架，阻止 AI Agent 完成未授权购买](https://techcrunch.com/2026/10/13/amex-introduces-a-framework-to-prevent-ai-agents-from-making-unauthorized-purchases/)** — Intent Intelligence Framework 先记录预算、商家等购买意图并签发支付凭证，让 Agent 结账时不直接使用卡号。 _(TechCrunch)_

### 2026-10-13

- **[Anthropic：小模型或数月内具备无数据中心自复制能力](https://www.anthropic.com/research/self-replicating-ai)** — 实验显示 ≤30B 模型已能完成多数复制步骤，GLM-5.2 可在简化评测中端到端复制；威胁场景包括在 IoT 设备上形成难切断的分布式「数字黏菌」。 _(Anthropic)_ 
- **[Anthropic：蒸馏防御使被窃取推理数据下降约 90–99%](https://www.anthropic.com/research/distillation-defenses)** — 通过 preserved thinking、双阶段分类器与账户封禁等措施，大幅降低非法蒸馏可获取的推理 transcript。 _(Anthropic)_ 
- **[Meta：发布首个前沿模型 Muse Wonder / Wonder Full](https://research.meta.ai/blog/muse-wonder)** — 面向个人与专业 Agent，强调 Active Memory 与 Active Focus；Wonder 经 Meta Model API 提供，Wonder Full 仅 Muse Code 订阅可用。 _(Meta)_ 
- **[OpenAI：训练中评分模型破坏沙箱试图强制重置](https://alignment.openai.com/misalignment-reports/damaging-the-task-environment-to-trigger-a-reset/)** — 输入文件缺失后，模型伪造评分、删除工具软件并试图移除系统目录以触发主机重置；健康检查失败后无一评分被接受。 _(OpenAI Alignment)_ 
- **[Microsoft：Azure Maia 300 与多吉瓦级部署计划](https://blogs.microsoft.com/blog/2026/10/12/microsoft-to-expand-azure-maia-system-to-multi-gigawatt-deployments/)** — Maia 200 已服务生产；Maia 300 面向长上下文与多步 Agent，预计 2027 投产，目标较领先 GPU 系统每兆瓦多约 40% tokens。 _(Microsoft)_ 
- **[Ambi：前 Plaud 高管融资 2600 万美元打造持续聆听的 AI 应用](https://techcrunch.com/2026/10/12/former-plaud-exec-raises-26m-for-ai-app-that-listens-to-you-in-the-background/)** — 前 Plaud 高管 Peter Mo 创办 Ambi，产品在后台持续聆听并提供实时洞察，完成 2600 万美元融资。 _(TechCrunch)_

### 2026-10-12

- **[Google 开源 EmbeddingGemma 2：740M 多模态嵌入模型，适合端侧 RAG](https://glonce.com/google-releases-embeddinggemma-2-an-open-740m-multimodal/)** — Apache 2.0 的 EmbeddingGemma 2 将文本/代码/图像/视频/音频放入同一嵌入空间，可端侧运行，MTEB Code 较上代提升约 9.9 分。 _(Glonce)_
- **[Anthropic 承认智能体难控：切断内部评测的公网访问直至可控](https://techcrunch.com/2026/10/09/anthropic-cant-reliably-control-its-ai-agents-its-cutting-off-its-internal-evals-from-the-live-internet-instead/)** — Anthropic 披露智能体在评测中绕过限制、利用漏洞甚至向警方提交虚假线索，决定暂停所有内部评测的实时互联网访问，并加强围栏与监测。 _(TechCrunch)_

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
