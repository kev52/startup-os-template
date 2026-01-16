# Startup OS

> **Your startup's command center. Strategy, product, and business docs in one place.**
>
> **No coding required.** Works beautifully with AI assistants.

Built on proven frameworks from the world's best startup books.

---

## Who Is This For?

| You Are... | This Helps You... |
|------------|-------------------|
| **Non-technical Founder** | Organize strategy, validate ideas, track progress (no code needed) |
| **Technical Founder** | Connect business docs to code, maintain architecture decisions |
| **Co-founder Team** | Single source of truth, every decision tracked and searchable |
| **Solo Creator** | Think clearly, build systematically, stay organized |

---

## Quick Start

### Path A: I'm Not a Coder (Recommended)

*Perfect for founders, product people, and business folks. Takes about 15 minutes.*

<details>
<summary><strong>What You'll Need (click to expand)</strong></summary>

| Tool | What It Is | Get It |
|------|------------|--------|
| **GitHub Account** | Free cloud storage for your startup docs | [Sign up free](https://github.com/signup) |
| **GitHub Desktop** | Simple app to sync files (no command line) | [Download free](https://desktop.github.com/) |
| **Claude Max** | AI assistant with Cowork feature | [Get Claude Max](https://claude.ai/upgrade) |

**Don't have Claude Max?** See [Alternative Tools](#alternative-tools-for-non-coders) below.

</details>

---

#### Step 1: Create Your Startup's Home

1. Make sure you're logged into GitHub
2. Click the green **"Use this template"** button at the top of this page
3. Click **"Create a new repository"**
4. **Name it** something like `acme-startup` or `my-company`
5. Select **Private** (keeps your docs confidential)
6. Click **"Create repository"**

You now have your own copy of Startup OS!

---

#### Step 2: Download to Your Computer

1. **Open GitHub Desktop** (download it first if you haven't)
2. Click **File** then **Clone Repository**
3. Click the **GitHub.com** tab
4. Find your new repo in the list and select it
5. Choose where to save it (like your Documents folder)
6. Click **Clone**

Your startup folder is now on your computer!

---

#### Step 3: Open with Cowork

[Cowork](https://claude.com/blog/cowork-research-preview) is Claude's new feature that works directly with your files. It's like having an AI co-founder who can read and edit your documents.

1. **Open the Claude macOS app**
2. Click **"Cowork"** in the left sidebar
3. Click **"Add Folder"**
4. Navigate to your startup folder and select it
5. **Type this message to Claude:**

```
Read WIZARD_PROMPT.md and help me set up my startup
```

---

#### Step 4: Have a Conversation

Claude will interview you about your startup:

- *"Why does your startup need to exist?"*
- *"Who are you building for?"*
- *"What problem are you solving?"*
- *"Where are you in your journey?"*

**Just answer naturally.** Claude will create customized documents based on your answers.

---

#### Step 5: Save Your Progress

When you're done for the day, save your work to the cloud:

1. **Open GitHub Desktop**
2. You'll see a list of changed files on the left
3. At the bottom, write a short note describing what you did (e.g., "Initial startup setup")
4. Click **"Commit to main"**
5. Click **"Push origin"** (the button at the top)

Your work is safely backed up in the cloud!

---

#### Step 6: Keep Building

Come back anytime and pick up where you left off:

1. Open GitHub Desktop and click **"Fetch origin"** (syncs latest changes)
2. Open Cowork (your folder is still there)
3. Ask Claude things like:
   - *"Help me write customer interview questions"*
   - *"Review my PR/FAQ and suggest improvements"*
   - *"What should I focus on this week?"*

---

### Alternative Tools for Non-Coders

Don't have Claude Max? These alternatives also work great:

| Tool | Cost | Best For |
|------|------|----------|
| [ChatGPT Plus](https://chat.openai.com) | $20/mo | Upload the WIZARD_PROMPT.md file and chat |
| [Claude Free](https://claude.ai) | Free | Copy-paste WIZARD_PROMPT.md content |
| [Notion AI](https://notion.so) | $10/mo | If you prefer Notion's interface |

**How to use without Cowork:**
1. Complete Steps 1-2 above (create repo, download with GitHub Desktop)
2. Open any AI chat and paste the contents of WIZARD_PROMPT.md
3. Answer the questions, then manually copy Claude's outputs into the files
4. Save your changes with GitHub Desktop (Step 5)

---

### Path B: I'm a Developer

*For technical founders comfortable with Git and command line.*

```bash
# 1. Use the template button above, then:
git clone https://github.com/YOUR-USERNAME/YOUR-REPO.git
cd YOUR-REPO

# 2. Open with your preferred tool
cursor .              # Cursor IDE
claude                # Claude Code (in the repo directory)
code .                # VS Code + Copilot

# 3. Ask your AI: "Read WIZARD_PROMPT.md and help me set up my startup"
```

**Recommended AI Tools for Developers:**

| Tool | Best For |
|------|----------|
| [Cursor](https://cursor.sh) | Full IDE with AI built-in |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Terminal-based, powerful for both docs and code |
| [GitHub Copilot](https://github.com/features/copilot) | If you're already in VS Code |
| [Windsurf](https://codeium.com/windsurf) | Alternative AI-native IDE |

---

## New to Git? You're in Good Hands

Don't let "Git" intimidate you. Think of it as **"Track Changes" for your entire startup.**

### Why This Matters

| Benefit | What It Means |
|---------|---------------|
| **Complete History** | See every decision you ever made, when, and why |
| **Undo Anything** | Made a mistake? Roll back to any previous version |
| **Collaborate Safely** | Multiple people can work without overwriting each other |
| **Automatic Backup** | Your work lives safely in the cloud |
| **Search Everything** | Find that idea you had 6 months ago |

### Git Vocabulary (Plain English)

| Term | What It Really Means |
|------|----------------------|
| **Repository (repo)** | Your project folder with superpowers (it remembers every change) |
| **Clone** | Download a copy to your computer |
| **Commit** | Save a checkpoint with a note about what you did |
| **Push** | Upload your saves to the cloud |
| **Pull / Fetch** | Download the latest changes from the cloud |

### Learning Resources

| Resource | Time | Best For |
|----------|------|----------|
| [Git for Non-Programmers (Video)](https://www.youtube.com/watch?v=BCQHnlnPusY) | 20 min | Video walkthrough (great starting point) |
| [GitHub Desktop Docs](https://docs.github.com/en/desktop/overview/getting-started-with-github-desktop) | 15 min | Official guide, very beginner-friendly |
| [GitHub Skills](https://skills.github.com/) | 1 hour | Interactive hands-on learning |
| [Oh Shit, Git!](https://ohshitgit.com/) | 5 min | When things go wrong (they won't, but just in case) |

---

## What's Inside

Your Startup OS is organized into numbered folders that guide your journey:

```
your-startup/
├── 00_why/           # Your purpose and values
├── 01_strategy/      # Strategic decisions
├── 02_discovery/     # Customer research and interviews
├── 03_product/       # Product vision, specs, roadmap
├── 04_validation/    # Stage tracking and metrics
├── 05_business/      # Business model and monetization
├── 06_design/        # Design system and brand
├── 07_engineering/   # Technical docs (for when you're ready)
├── src/              # Source code (for when you're ready)
├── 08_growth/        # Marketing and growth
├── 09_operations/    # Team and processes
├── 10_finance/       # Financial planning
└── journal/          # Decision logs and learnings
```

### Start Here (Don't Try to Fill Everything)

| Priority | Document | Why It Matters |
|:--------:|----------|----------------|
| 1 | 00_why/why.md | Your core belief — everything flows from here |
| 2 | 03_product/pr_faq.md | Future press release — clarifies your vision |
| 3 | 02_discovery/customers/personas.md | Who you're building for |
| 4 | 02_discovery/problems/jobs_to_be_done.md | What job you're hired for |
| 5 | 04_validation/current_stage.md | Where you are in the journey |

Everything else fills in as you progress. **Don't overwhelm yourself.**

---

## The Frameworks Behind This

Startup OS is built on battle-tested frameworks from these books:

| Book | What You'll Use | Where |
|------|-----------------|-------|
| *Start with Why* (Sinek) | Golden Circle: WHY then HOW then WHAT | 00_why/ |
| *Good Strategy Bad Strategy* (Rumelt) | Strategy Kernel: diagnosis, policy, actions | 01_strategy/ |
| *The Mom Test* (Fitzpatrick) | Customer interview techniques | 02_discovery/ |
| *Continuous Discovery Habits* (Torres) | Opportunity Solution Trees | 02_discovery/ |
| *Working Backwards* (Bryar and Carr) | PR/FAQ method from Amazon | 03_product/ |
| *Inspired* (Cagan) | Product vision and principles | 03_product/ |
| *Hooked* (Eyal) | Building habit-forming products | 03_product/ |
| *The Startup Owner's Manual* (Blank) | Customer Development stages | 04_validation/ |

---

## Why Start with PR/FAQ?

> *"Working Backwards" is how Amazon built a 1.5 trillion dollar company.*

Before building anything, write the press release announcing your product's launch — **as if it already exists**.

This forces you to:

1. **Think from the customer's perspective** — What headline would make them care?
2. **Clarify the value proposition** — What problem, for whom, why now?
3. **Identify assumptions** — The FAQ reveals what you don't know
4. **Align everyone** — One document, one vision

**Your PR/FAQ is your North Star.** When stuck on any decision, ask: *"Does this belong in the press release?"*

---

## Your Startup Journey

This repo follows Steve Blank's Customer Development model:

```
        YOU ARE HERE
             |
             v
+----------------------------------------------------------------+
|    SEARCH                              EXECUTE                  |
+----------------+----------------+----------------+--------------+
|   CUSTOMER     |   CUSTOMER     |   CUSTOMER     | COMPANY      |
|   DISCOVERY    |   VALIDATION   |   CREATION     | BUILDING     |
+----------------+----------------+----------------+--------------+
| Problem/       | Product/       | Business       | Scale        |
| Solution Fit   | Market Fit     | Model Fit      |              |
+----------------+----------------+----------------+--------------+
| "Do people     | "Will people   | "Can we grow   | "Can we      |
|  have this     |  pay for       |  efficiently?" |  scale?"     |
|  problem?"     |  this?"        |                |              |
+----------------+----------------+----------------+--------------+
```

Track your progress in 04_validation/current_stage.md.

---

## Working with Your AI Assistant

### Recommended: Cowork (for Non-Coders)

[Cowork](https://claude.com/blog/cowork-research-preview) is Claude's new agentic feature, specifically designed for working with documents and files. It's like having an AI co-founder who can:

- Read, edit, and create your documents directly
- Work autonomously while keeping you in control
- Feel like messaging a coworker, not prompting a chatbot

**How to get it:** Cowork is available in the Claude macOS app for [Claude Max subscribers](https://claude.ai/upgrade).

### All Supported Tools

| Tool | Type | Best For |
|------|------|----------|
| [Cowork](https://claude.com/blog/cowork-research-preview) | Desktop App | Non-coders, document-heavy work |
| [Cursor](https://cursor.sh) | IDE | Developers, mixed code and docs |
| [Claude Code](https://docs.anthropic.com/en/docs/claude-code) | Terminal | Power users, full autonomy |
| [GitHub Copilot](https://github.com/features/copilot) | VS Code Extension | Developers already using VS Code |
| [Windsurf](https://codeium.com/windsurf) | IDE | Alternative to Cursor |
| [ChatGPT](https://chat.openai.com) | Web | Manual copy-paste workflow |
| [Claude Web](https://claude.ai) | Web | Manual copy-paste workflow |

---

## For Developers: Git Workflow

<details>
<summary><strong>Click to expand developer-specific Git conventions</strong></summary>

### Branches

- main — Stable, reviewed content
- develop — Integration branch
- feature/* — New features
- docs/* — Documentation updates
- experiment/* — Experiments

### Commit Convention

```
<type>(<scope>): <description>

Types: feat, fix, docs, biz, strategy, discovery, experiment
```

Examples:
- feat(auth): add OAuth2 login
- docs(product): update PR/FAQ
- discovery(customers): add interview notes
- biz(finance): add Q1 projections

### Tags for Milestones

- v0.1-mvp — Version milestones
- psf-achieved — Problem/Solution Fit
- pmf-achieved — Product/Market Fit
- seed-round — Funding milestones

</details>

---

## For Developers: Documentation Site

<details>
<summary><strong>Click to expand MkDocs setup instructions</strong></summary>

This template includes [MkDocs](https://www.mkdocs.org/) with [Material theme](https://squidfunk.github.io/mkdocs-material/) for building a documentation site.

### Local Development

```bash
pip install -r requirements-docs.txt
mkdocs serve    # http://localhost:8000
mkdocs build    # generates site/ folder
```

### Deployment Options

Note: GitHub Pages is public by default — not suitable for confidential startup docs.

| Platform | Privacy | Cost | Notes |
|----------|---------|------|-------|
| **Cloudflare Pages** | Access policies | Free | Best free private option |
| **Vercel** | Password protection | Pro plan | Easy setup |
| **Netlify** | Team access | Pro plan | Good CI/CD |
| **Self-hosted** | Full control | Varies | nginx, internal servers |

</details>

---

## Frequently Asked Questions

<details>
<summary><strong>I'm not technical. Can I really use this?</strong></summary>

Absolutely! That's exactly who this is designed for. Follow Path A above — you'll use GitHub Desktop (a simple app with buttons, no command line) and Cowork (Claude's document assistant). The AI will guide you through everything.

</details>

<details>
<summary><strong>Do I need to learn Git?</strong></summary>

Not really. GitHub Desktop handles the technical parts. You just click "Commit" to save and "Push" to backup. That said, understanding the basic vocabulary helps you feel confident.

</details>

<details>
<summary><strong>What if I mess something up?</strong></summary>

That's the beauty of Git — you can always go back! Every save (commit) is a checkpoint. If something goes wrong, GitHub Desktop lets you restore previous versions. You literally cannot permanently break anything.

</details>

<details>
<summary><strong>Can my co-founder work on this too?</strong></summary>

Yes! Add them as a collaborator on GitHub (Settings then Collaborators). They clone the same repo, and Git merges everyone's changes. It's like Google Docs but more powerful.

</details>

<details>
<summary><strong>Is my startup info private?</strong></summary>

Yes, if you chose "Private" when creating the repo. Only you (and anyone you invite) can see it. GitHub is trusted by millions of companies for confidential code and docs.

</details>

<details>
<summary><strong>I don't have Claude Max. What are my options?</strong></summary>

See Alternative Tools for Non-Coders above. The short version: you can use any AI (ChatGPT, Claude Free, etc.) — you'll just copy-paste instead of having the AI edit files directly.

</details>

---

## Get Help

- **GitHub Discussions** — Ask questions, share learnings
- **GitHub Issues** — Report bugs or suggest features
- **This README** — Bookmark it for reference

### Reach Out Directly

Have questions or want to chat about your startup? I'm happy to help!

| Channel | Contact |
|---------|---------|
| **Website** | [kevin-luecke.com](https://www.kevin-luecke.com) |
| **Email** | [kevin.luecke@me.com](mailto:kevin.luecke@me.com) |
| **Telegram** | [@kevinbatumshi](https://t.me/kevinbatumshi) |
| **WhatsApp** | [+49 162 758 2289](https://wa.me/491627582289) |

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
- Colin Bryar and Bill Carr — *Working Backwards*
- Simon Sinek — *Start with Why*
- Rob Fitzpatrick — *The Mom Test*
- Nir Eyal — *Hooked*
- Richard Rumelt — *Good Strategy Bad Strategy*
- Teresa Torres — *Continuous Discovery Habits*

---

**Ready to build something amazing? Start with your WHY.**
