# Research-Driven Insights

This repo is shaped by a real user survey — **146 responses** (132 CN + 14 EN), filtered to **94 qualified ICPs** (those who said they'd install today OR would pay $50+/month).

Below are the research findings that directly informed Open Design's product decisions. Each bullet ties a **survey signal** to a **product choice**.

## 🎯 Category anchor: "Agentic Workspace"

- **Signal**: 56% CN + 71% EN picked "Agentic Workspace" as the category label (single highest option across 7 choices; 22pp ahead of #2)
- **Rejected alternative**: "Agent-Native Slack" — only 13.8% picked it
- **Product choice**: Open Design positions as an **Agentic Design Workspace**, not "AI Figma," not "Slack for designers"

## 🗣️ How users talk about the product

Users' own words (from open-ended survey responses):
- *"A digital twin that grows with me"*
- *"A swarm of agents I can coordinate in one space"*
- *"A workspace where one person guides a group of agents"*
- *"Beyond chat — we need project-space concepts, where each project's output can be reviewed and edited"*
- *"Hurry up — I'm about to build my own 'agents + humans in a group chat' version myself"* (from a $1000-5000/mo paying prospect)

**Product choice**: Landing page copy will **mirror these phrases back**. The product isn't positioned in our words — it's positioned in theirs.

## 🚨 The 3 pain points we must solve on Day 1

### Pain 1 — Agent coordination is broken
- **Signal**: 36% said "bots don't talk to each other; one task runs through multiple bots" (comm pain #1). 33% said "AI can't assign tasks to the right person/agent" (PM pain #1). **Both top-1 pains are the same problem from different angles.**
- **Product choice**: Multi-agent orchestration is the **core technical bet**. Agent-to-agent handoff is a first-class primitive, not a plugin.

### Pain 2 — Long memory is missing
- **Signal**: Users literally wrote *"I can't stand AI's amnesia anymore."* 55% picked "persistent memory" as a top capability need.
- **Product choice**: Every agent in Open Design has **persistent workspace memory**. The design system you define, the decisions you make, the conventions you use — agents remember and reference them on return.

### Pain 3 — Cost is a black box
- **Signal**: 28% called out "cost is a black box — I don't know how many tokens a bot burned." Paid-tier users mention it repeatedly.
- **Product choice**: Visible token panel in-product, from day one. Budget alerts. Cost attribution per agent / per project. Transparent pricing.

## ⛔ The red line: "Don't become another configuration hell"

- **Signal** (verbatim, one of the most shared sentiments): *"Don't turn into a new form of overtime-generator. Less configuration hell, more actual effortless collaboration."*
- **Product principle**: **Default-on beats configurable.** We fight the "yet another enterprise tool where you configure for a week before it works" pattern.

## 🧩 Tool stack reality

- **CN comm stack**: Lark/Feishu (52%) > WeChat work groups (46%) > DingTalk (29%) > WeCom (23%). Slack: 2%.
- **EN comm stack**: Slack / Lark / Telegram each ~36%, more distributed
- **PM stack (CN)**: Lark's multidimensional tables (44%), 15% use no PM tool at all
- **PM stack (EN)**: GitHub Projects (50%) > Linear (36%)
- **AI tools across both**: Claude Code 66–71%, OpenClaw/Hermes 62–64%, Codex 56%

**Product choice**:
- CN integrations priority: **Lark → WeChat → DingTalk → WeCom**
- EN integrations priority: **GitHub → Linear → Slack → Telegram**
- **Coding-agent interop** (Claude Code / Codex / Cursor / Cline) is table-stakes

## 🎁 Channel strategy

- **CN**: 40% of survey respondents came from WeChat groups → private channels dominate today; **public channels (Twitter / GitHub / Douyin / Xiaohongshu) are an untapped well**
- **EN**: 43% came from Twitter directly → PLG + DevRel is the standard playbook

## 🧪 Who we're building for (the real ICP)

The 94 qualified ICPs break down as:
- **Developers / software engineers** — 36%
- **Solo founders / OPCs** — 29% (CN) / 64% (EN)
- **Founders / managers** — 16%
- **Growth / marketing / ops** — 16%
- **Students / researchers** — 16%

**Dominant team size**: Solo to 50-person teams (80%+ of the sample)
**Tenure**: 62% have 5+ years of work experience → this is a **senior audience**, low tolerance for toy-level tools

---

**Methodology note**: This is a pre-launch interest survey, not a usage study. Pricing preferences in particular are **directional only** — users' stated willingness to pay correlates weakly with actual paid conversion. We use the pricing question to **segment paying-intent tiers** for user research recruitment, not to set final prices.
