# Startup OS Template

> **A Git-powered command center for building startups — from vision to code.**

Built on frameworks from: *The Startup Owner's Manual*, *Inspired*, *Working Backwards*, *Start with Why*, *The Mom Test*, *Hooked*, *Good Strategy Bad Strategy*, and *Continuous Discovery Habits*.

---

## What is Startup OS?

Startup OS is a repository template that organizes your entire startup journey in Git:

- **Strategy & Vision** — Why you exist, where you're going
- **Customer Discovery** — Who you're building for, what problems you're solving
- **Product Development** — From PR/FAQ to roadmap to specs
- **Validation Tracking** — Customer Development stages, metrics, pivots
- **Business Model** — Revenue, GTM, unit economics
- **Engineering** — Architecture, ADRs, code
- **Operations** — Team, processes, rituals

Everything version-controlled. Everything in one place.

---

## Quick Start

### Option 1: AI-Assisted Setup (Recommended)

Use an AI coding agent to interview you and set up your customized repo.

**Step 1: Clone this template**

```bash
git clone https://github.com/kev52/startup-os-template.git my-startup
cd my-startup
```

**Step 2: Open with your AI coding agent**

| Tool | Command |
|------|---------|
| **Cursor** | Open folder → Press `Cmd+I` (Mac) or `Ctrl+I` (Windows) |
| **Claude Code** | `claude code my-startup/` |
| **GitHub Copilot** | Open in VS Code → Use Copilot Chat |
| **Windsurf** | Open folder → Use AI chat |
| **ChatGPT/Claude Web** | Copy-paste the prompt manually |

**Step 3: Initialize your Startup OS**

Paste this to your AI agent:

```
Read WIZARD_PROMPT.md and help me set up my startup
```

**Step 4: Complete the interview**

The AI will ask you questions about your startup:
- Why does it need to exist?
- Who are you building for?
- What problem are you solving?
- Where are you in the journey?

Answer conversationally — the AI will create your customized documents.

**Step 5: Start your journey**

Begin with `03_product/pr_faq.md` — your future press release.

---

### Option 2: Manual Setup

If you prefer to set up manually:

1. Clone this template
2. Fill in the core documents (see "Documents to Start With" below)
3. Use the templates in each folder as you progress

---

## Repository Structure

```
my-startup/
├── 00_why/                    # Start with Why (Simon Sinek)
├── 01_strategy/               # Good Strategy Bad Strategy (Rumelt)
├── 02_discovery/              # Continuous Discovery + The Mom Test
├── 03_product/                # Working Backwards + Inspired + Hooked
├── 04_validation/             # The Startup Owner's Manual (Blank)
├── 05_business/               # Business model and monetization
├── 06_design/                 # Design system and UX
├── 07_engineering/            # Technical docs and ADRs
├── src/                       # Source code
├── 08_growth/                 # Marketing and growth
├── 09_operations/             # Team and processes
├── 10_finance/                # Financial planning
├── journal/                   # Decision logs and learnings
└── .github/                   # Issue and PR templates
```

---

## Documents to Start With

Don't try to fill everything at once. Start with these:

| Priority | Document | Purpose |
|----------|----------|---------|
| 1 | `00_why/why.md` | Your core belief — everything flows from here |
| 2 | `03_product/pr_faq.md` | Future press release — clarifies vision |
| 3 | `02_discovery/customers/personas.md` | Who you're building for |
| 4 | `02_discovery/problems/jobs_to_be_done.md` | What job you're hired for |
| 5 | `04_validation/current_stage.md` | Where you are in the journey |

Everything else fills in as you progress.

---

## Why Start with PR/FAQ?

> "Working Backwards" is how Amazon built a $1.5 trillion company.

Before writing code, write the press release announcing your product's launch — **as if it already exists**.

This forces you to:

1. **Think from the customer's perspective** — What headline would make them care?
2. **Clarify the value proposition** — What problem, for whom, why now?
3. **Identify assumptions** — The FAQ reveals what you don't know
4. **Align everyone** — One document, one vision

**Your PR/FAQ is your North Star.** When you're stuck on a decision, ask: "Does this belong in the press release?"

---

## Customer Development Stages

This repo is organized around Steve Blank's Customer Development model:

```
        YOU ARE HERE
             ↓
┌────────────────────────────────────────────────────────────────┐
│    SEARCH                              EXECUTE                  │
├─────────────────┬─────────────────┬─────────────────┬──────────┤
│   CUSTOMER      │   CUSTOMER      │   CUSTOMER      │ COMPANY  │
│   DISCOVERY     │   VALIDATION    │   CREATION      │ BUILDING │
├─────────────────┼─────────────────┼─────────────────┼──────────┤
│ Problem/        │ Product/        │ Business        │ Scale    │
│ Solution Fit    │ Market Fit      │ Model Fit       │          │
├─────────────────┼─────────────────┼─────────────────┼──────────┤
│ "Do people      │ "Will people    │ "Can we grow    │ "Can we  │
│  have this      │  pay for        │  efficiently?"  │  scale?" │
│  problem?"      │  this?"         │                 │          │
└─────────────────┴─────────────────┴─────────────────┴──────────┘
```

Use `04_validation/current_stage.md` to track where you are and what's next.

---

## Git Workflow

### Branches

- `main` — Stable, reviewed content
- `develop` — Integration branch
- `feature/*` — New features
- `docs/*` — Documentation updates
- `experiment/*` — Experiments

### Commit Convention

```
<type>(<scope>): <description>

Types: feat, fix, docs, biz, strategy, discovery, experiment
```

Examples:
- `feat(auth): add OAuth2 login`
- `docs(product): update PR/FAQ`
- `discovery(customers): add interview notes`
- `biz(finance): add Q1 projections`

### Tags for Milestones

- `v0.1-mvp` — Version milestones
- `psf-achieved` — Problem/Solution Fit
- `pmf-achieved` — Product/Market Fit
- `seed-round` — Funding milestones

---

## Frameworks Reference

| Book | Framework | Used In |
|------|-----------|---------|
| Start with Why | Golden Circle (WHY/HOW/WHAT) | `00_why/` |
| Good Strategy Bad Strategy | Strategy Kernel | `01_strategy/` |
| The Mom Test | Interview questions | `02_discovery/customers/` |
| Continuous Discovery Habits | Opportunity Solution Trees | `02_discovery/opportunities/` |
| Working Backwards | PR/FAQ | `03_product/pr_faq.md` |
| Inspired | Product Vision | `03_product/product_vision.md` |
| Hooked | Hook Model | `03_product/hook_model.md` |
| The Startup Owner's Manual | Customer Development | `04_validation/` |

---

## Supported AI Tools

| Tool | How to Use |
|------|------------|
| [Cursor](https://cursor.sh) | Open folder → `Cmd+I` → paste wizard prompt |
| [Claude Code](https://claude.ai) | `claude code my-startup/` → reference WIZARD_PROMPT.md |
| [GitHub Copilot](https://github.com/features/copilot) | Open in VS Code → Copilot Chat |
| [Windsurf](https://codeium.com/windsurf) | Open folder → AI chat |
| [ChatGPT](https://chat.openai.com) | Copy-paste WIZARD_PROMPT.md content |
| [Claude Web](https://claude.ai) | Copy-paste WIZARD_PROMPT.md content |

---

## Contributing

See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

---

## License

MIT — Use this template freely for your startup.

---

## Acknowledgments

Built on the shoulders of giants:

- Steve Blank — *The Startup Owner's Manual*
- Marty Cagan — *Inspired*
- Colin Bryar & Bill Carr — *Working Backwards*
- Simon Sinek — *Start with Why*
- Rob Fitzpatrick — *The Mom Test*
- Nir Eyal — *Hooked*
- Richard Rumelt — *Good Strategy Bad Strategy*
- Teresa Torres — *Continuous Discovery Habits*

---

**Ready to build something amazing? Start with your WHY.** 🚀

