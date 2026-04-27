# AI Agent Skill List

> A GitHub-ready list of notable Claude / OpenClaw / Agent Skills packs, including author/source info, what each is useful for, compatibility notes, install hints, and live GitHub star badges.
>
> **Last reviewed:** 2026-04-26  
> **Tip:** The star badges below use Shields.io, so if this file is published to GitHub they will auto-refresh periodically instead of becoming stale.

---

## How to read this file

- **Live stars** are dynamic badges, not hardcoded counts.
- **Official** means published by the company/project named in the row.
- **Community** means a third-party repo, even if it is inspired by a famous person.
- **Audit first** means inspect `SKILL.md`, scripts, install commands, and required permissions before installing.

### Live star badge template

```md
[![GitHub stars](https://img.shields.io/github/stars/OWNER/REPO?style=social)](https://github.com/OWNER/REPO)
```

---

## Shortlist: install first

| Priority | Skill / pack | Why install first | Repo / source | Live stars |
|---:|---|---|---|---|
| 1 | Skill vetter / scanner | Check untrusted skills before using them | [`Feahter/openclaw-tools`](https://github.com/Feahter/openclaw-tools) | [![GitHub stars](https://img.shields.io/github/stars/Feahter/openclaw-tools?style=social)](https://github.com/Feahter/openclaw-tools) |
| 2 | Agent Browser | Browser automation, screenshots, extraction, form-filling | [`vercel-labs/agent-browser`](https://github.com/vercel-labs/agent-browser) / [`openclaw/skills`](https://github.com/openclaw/skills/tree/main/skills/thesethrose/agent-browser) | [![GitHub stars](https://img.shields.io/github/stars/vercel-labs/agent-browser?style=social)](https://github.com/vercel-labs/agent-browser) |
| 3 | Tavily Search | Live web search and research for agents | [`tavily-ai/skills`](https://github.com/tavily-ai/skills) / [Tavily docs](https://docs.tavily.com/documentation/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/tavily-ai/skills?style=social)](https://github.com/tavily-ai/skills) |
| 4 | Anthropic webapp-testing | Playwright-style local app testing, screenshots, browser logs | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) |
| 5 | Addy Osmani agent-skills | Full coding lifecycle: spec, plan, build, test, review, ship | [`addyosmani/agent-skills`](https://github.com/addyosmani/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/addyosmani/agent-skills?style=social)](https://github.com/addyosmani/agent-skills) |
| 6 | Garry Tan gstack | Opinionated startup/product-engineering workflow pack | [`garrytan/gstack`](https://github.com/garrytan/gstack) | [![GitHub stars](https://img.shields.io/github/stars/garrytan/gstack?style=social)](https://github.com/garrytan/gstack) |
| 7 | Karpathy read-arxiv-paper | Reads arXiv TeX source and writes technical paper summaries | [`karpathy/nanochat`](https://github.com/karpathy/nanochat/tree/master/.claude/skills/read-arxiv-paper) | [![GitHub stars](https://img.shields.io/github/stars/karpathy/nanochat?style=social)](https://github.com/karpathy/nanochat) |
| 8 | Product Manager Skills | PRDs, roadmaps, discovery, story mapping, prioritization | [`deanpeters/Product-Manager-Skills`](https://github.com/deanpeters/Product-Manager-Skills) | [![GitHub stars](https://img.shields.io/github/stars/deanpeters/Product-Manager-Skills?style=social)](https://github.com/deanpeters/Product-Manager-Skills) |
| 9 | Marketing Skills | Copywriting, SEO, CRO, analytics, growth workflows | [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills) | [![GitHub stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills?style=social)](https://github.com/coreyhaines31/marketingskills) |
| 10 | Hugging Face Skills | Dataset creation, model training, evaluation, HF Hub workflows | [`huggingface/skills`](https://github.com/huggingface/skills) | [![GitHub stars](https://img.shields.io/github/stars/huggingface/skills?style=social)](https://github.com/huggingface/skills) |

---

## Famous people / influencer / creator skill packs

| # | Skill / pack | Author / source | Repo / source | Live stars | Useful for | Notable skills / components | Works with / likely portable to OpenClaw? | Install hint | Notes |
|---:|---|---|---|---|---|---|---|---|---|
| 1 | `gstack` | Garry Tan | [`garrytan/gstack`](https://github.com/garrytan/gstack) | [![GitHub stars](https://img.shields.io/github/stars/garrytan/gstack?style=social)](https://github.com/garrytan/gstack) | Startup/product engineering, review loops, deployment discipline | CEO review, engineering review, design review, QA, security, deploy, browse, retro, guard/freeze safety tools | High; skill folders can be inspected and adapted | `npx skills add garrytan/gstack` | Very broad pack; audit commands before using on production repos. |
| 2 | `agent-skills` | Addy Osmani | [`addyosmani/agent-skills`](https://github.com/addyosmani/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/addyosmani/agent-skills?style=social)](https://github.com/addyosmani/agent-skills) | Full software-development lifecycle | Spec, plan, build, test, review, ship, TDD, code review, browser testing, simplification | Very high; designed around Agent Skills conventions | `npx skills add addyosmani/agent-skills` | Strong first install for coding agents. |
| 3 | `web-quality-skills` | Addy Osmani | [`addyosmani/web-quality-skills`](https://github.com/addyosmani/web-quality-skills) | [![GitHub stars](https://img.shields.io/github/stars/addyosmani/web-quality-skills?style=social)](https://github.com/addyosmani/web-quality-skills) | Frontend quality, performance, SEO, accessibility | Lighthouse, Core Web Vitals, framework-agnostic audits | Very high for web projects | `npx skills add addyosmani/web-quality-skills` | Best for frontend audit/fix workflows. |
| 4 | `impeccable` | Paul Bakaus | [`pbakaus/impeccable`](https://github.com/pbakaus/impeccable) | [![GitHub stars](https://img.shields.io/github/stars/pbakaus/impeccable?style=social)](https://github.com/pbakaus/impeccable) | UI taste, frontend polish, avoiding generic AI-generated UI | Typography, spacing, color, motion, UX writing, audits, anti-patterns | High; supports multiple coding agents | `npx impeccable` or follow repo instructions | Good companion to frontend-design/web-quality skills. |
| 5 | `read-arxiv-paper` | Andrej Karpathy, inside `nanochat` | [`karpathy/nanochat/.claude/skills/read-arxiv-paper`](https://github.com/karpathy/nanochat/tree/master/.claude/skills/read-arxiv-paper) | [![GitHub stars](https://img.shields.io/github/stars/karpathy/nanochat?style=social)](https://github.com/karpathy/nanochat) | Reading ML/AI research papers from source TeX | Normalize arXiv URL, download source, inspect LaTeX, write project-focused summary | High; copy the skill folder if your agent supports `SKILL.md` | Manual copy from `.claude/skills/read-arxiv-paper` | This is the most directly Karpathy-owned skill found. |
| 6 | `karpathy-guidelines` | Forrest Chang; Karpathy-inspired, not authored by Karpathy | [`forrestchang/andrej-karpathy-skills`](https://github.com/forrestchang/andrej-karpathy-skills) | [![GitHub stars](https://img.shields.io/github/stars/forrestchang/andrej-karpathy-skills?style=social)](https://github.com/forrestchang/andrej-karpathy-skills) | Better coding behavior and safer changes | Think before coding, simplicity first, surgical changes, goal-driven verification | Medium-high; more of a behavior/rules skill | Follow repo plugin instructions or copy `skills/karpathy-guidelines` | Useful guardrail; clearly label as “inspired by,” not official Karpathy. |
| 7 | Datasette skill | Simon Willison / Datasette project | [`datasette/skill`](https://github.com/datasette/skill) | [![GitHub stars](https://img.shields.io/github/stars/datasette/skill?style=social)](https://github.com/datasette/skill) | Datasette plugin/project work | Project-specific guidance for Datasette | Medium; niche but useful if you use Datasette | Manual install/copy | Best for Datasette-specific development. |
| 8 | `marketingskills` | Corey Haines | [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills) | [![GitHub stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills?style=social)](https://github.com/coreyhaines31/marketingskills) | Marketing, growth, product marketing, CRO | Copywriting, content strategy, social content, SEO, analytics, growth engineering | High; follows Agent Skills spec | `npx skills add coreyhaines31/marketingskills` | Very useful for technical founders and marketers. |
| 9 | `Product-Manager-Skills` | Dean Peters | [`deanpeters/Product-Manager-Skills`](https://github.com/deanpeters/Product-Manager-Skills) | [![GitHub stars](https://img.shields.io/github/stars/deanpeters/Product-Manager-Skills?style=social)](https://github.com/deanpeters/Product-Manager-Skills) | Product management and strategy | PRD development, roadmap, discovery, story mapping, pricing, workshops | High; docs mention Claude, Cowork, Codex, AI agents | `npx skills add deanpeters/Product-Manager-Skills --list` | Good for product specs and planning. |
| 10 | `advertising-skills` | Kim Barrett | [`realkimbarrett/advertising-skills`](https://github.com/realkimbarrett/advertising-skills) | [![GitHub stars](https://img.shields.io/github/stars/realkimbarrett/advertising-skills?style=social)](https://github.com/realkimbarrett/advertising-skills) | Direct-response advertising and paid acquisition | Ads, funnels, positioning, copy systems, campaign workflows | High; repo describes Open Claw and Claude Code support | `npx skills add realkimbarrett/advertising-skills` | Good for ads/funnel work; validate claims before running campaigns. |
| 11 | BMAD Method skills | BMAD Method / bmad-code-org | [`bmad-code-org/BMAD-METHOD`](https://github.com/bmad-code-org/BMAD-METHOD) | [![GitHub stars](https://img.shields.io/github/stars/bmad-code-org/BMAD-METHOD?style=social)](https://github.com/bmad-code-org/BMAD-METHOD) | Agentic agile/software workflows | PR review, file-reference audit, workflow agents, project methods | Medium-high; copy/adapt individual skill folders | Manual copy of relevant `.claude/skills/*` | Large framework; avoid installing everything blindly. |

---

## Official / company / platform skill packs

| # | Skill / pack | Author / source | Repo / source | Live stars | Useful for | Notable skills / components | Works with / likely portable to OpenClaw? | Install hint | Notes |
|---:|---|---|---|---|---|---|---|---|---|
| 1 | Official Claude / Agent Skills | Anthropic | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | General Claude/agent productivity | `docx`, `pdf`, `pptx`, `xlsx`, `frontend-design`, `webapp-testing`, `skill-creator`, `mcp-builder`, `internal-comms` | High for Agent Skills-compatible tools | Follow Anthropic repo/plugin instructions | Best reference implementation for skill structure. |
| 2 | `webapp-testing` | Anthropic | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Local web app testing | Playwright-style tests, browser logs, screenshots, frontend behavior checks | High; useful in OpenClaw if path/tooling is adapted | Copy `webapp-testing` folder to your skills directory | Good companion to Agent Browser. |
| 3 | Vercel Agent Skills | Vercel Labs | [`vercel-labs/agent-skills`](https://github.com/vercel-labs/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/vercel-labs/agent-skills?style=social)](https://github.com/vercel-labs/agent-skills) | Vercel deployments and web app workflows | Deployment, project setup, web design guidelines, platform guidance | High if you use Vercel | `npx skills add vercel-labs/agent-skills` | Official Vercel collection. |
| 4 | Vercel `skills` CLI/tool | Vercel Labs | [`vercel-labs/skills`](https://github.com/vercel-labs/skills) | [![GitHub stars](https://img.shields.io/github/stars/vercel-labs/skills?style=social)](https://github.com/vercel-labs/skills) | Discovering/installing skills | `npx skills add`, `find-skills`, marketplace-style discovery | High; useful as installer/discovery utility | `npx skills add OWNER/REPO` | Useful meta-tool, not just a skill pack. |
| 5 | Agent Browser | Vercel Labs / OpenClaw archive | [`vercel-labs/agent-browser`](https://github.com/vercel-labs/agent-browser), [`openclaw/skills`](https://github.com/openclaw/skills/tree/main/skills/thesethrose/agent-browser) | [![GitHub stars](https://img.shields.io/github/stars/vercel-labs/agent-browser?style=social)](https://github.com/vercel-labs/agent-browser) | Browser automation | Open pages, click, fill, scrape, screenshot, PDFs, network, tabs, state | Very high for OpenClaw/browser work | `clawhub install thesethrose/agent-browser` or `npx skills add vercel-labs/agent-browser` | Prefer official/upstream repo where possible. |
| 6 | Tavily Agent Skills | Tavily | [`tavily-ai/skills`](https://github.com/tavily-ai/skills) / [docs](https://docs.tavily.com/documentation/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/tavily-ai/skills?style=social)](https://github.com/tavily-ai/skills) | Live web search, extraction, crawling, research | Search API, extract, crawl, research workflows | High, but needs Tavily API key | Follow Tavily docs or CLI instructions | Free tier may have limits; good research skill. |
| 7 | Hugging Face Skills | Hugging Face | [`huggingface/skills`](https://github.com/huggingface/skills) | [![GitHub stars](https://img.shields.io/github/stars/huggingface/skills?style=social)](https://github.com/huggingface/skills) | ML/AI development | Dataset creation, model training, evaluation, experiment workflows, Hub tasks | High for ML projects | `npx add-skill huggingface/skills` or repo instructions | Strong for AI builders. |
| 8 | Hugging Face kernel skills | Hugging Face Kernels | [`huggingface/kernels`](https://github.com/huggingface/kernels) | [![GitHub stars](https://img.shields.io/github/stars/huggingface/kernels?style=social)](https://github.com/huggingface/kernels) | GPU kernel optimization | CUDA kernels, ROCm kernels, benchmarking | Medium-high for ML infra | `kernel-builder skills add` | Specialized but valuable for performance work. |
| 9 | MongoDB Agent Skills | MongoDB | [`mongodb/agent-skills`](https://github.com/mongodb/agent-skills) | [![GitHub stars](https://img.shields.io/github/stars/mongodb/agent-skills?style=social)](https://github.com/mongodb/agent-skills) | MongoDB / Atlas workflows | MCP setup, schema/query guidance, connection workflows, Atlas usage | High for MongoDB users | `/plugin install mongodb` or repo docs | Official MongoDB collection. |
| 10 | Testcontainers Claude Skills | Testcontainers | [`testcontainers/claude-skills`](https://github.com/testcontainers/claude-skills) | [![GitHub stars](https://img.shields.io/github/stars/testcontainers/claude-skills?style=social)](https://github.com/testcontainers/claude-skills) | Container-based integration testing | Docker/Testcontainers testing patterns | Medium-high for backend projects | Follow repo instructions | Good for integration test generation/debugging. |
| 11 | Figma / design-to-code skills | Figma ecosystem / community | [Figma MCP skills docs](https://help.figma.com/hc/en-us/articles/39166810751895-Figma-skills-for-MCP) / [`ihlamury/design-skills`](https://github.com/ihlamury/design-skills) | [![GitHub stars](https://img.shields.io/github/stars/ihlamury/design-skills?style=social)](https://github.com/ihlamury/design-skills) | Design systems, Figma-to-code, UI consistency | Design-system rules, Figma MCP workflows, design constraints | Medium-high; depends on MCP setup | `npx skills add ihlamury/design-skills` | Use with Figma MCP for best results. |

---

## OpenClaw-focused and utility skills

| # | Skill / pack | Author / source | Repo / source | Live stars | Useful for | Notable skills / components | Works with / likely portable to Claude? | Install hint | Notes |
|---:|---|---|---|---|---|---|---|---|---|
| 1 | OpenClaw skills archive | OpenClaw | [`openclaw/skills`](https://github.com/openclaw/skills) | [![GitHub stars](https://img.shields.io/github/stars/openclaw/skills?style=social)](https://github.com/openclaw/skills) | Finding ClawHub-hosted skills | Archived skill versions, `SKILL.md` files | Medium-high; inspect individual folders | Browse and copy only trusted skills | Use as source-of-truth archive, not automatic install list. |
| 2 | Awesome OpenClaw Skills | VoltAgent | [`VoltAgent/awesome-openclaw-skills`](https://github.com/VoltAgent/awesome-openclaw-skills) | [![GitHub stars](https://img.shields.io/github/stars/VoltAgent/awesome-openclaw-skills?style=social)](https://github.com/VoltAgent/awesome-openclaw-skills) | Discovery | Categorized OpenClaw skills registry, safety warnings | N/A; directory/list | Browse categories | Good for discovery; still audit each skill. |
| 3 | Capability Evolver | EvoMap / OpenClaw ecosystem | [`EvoMap/evolver`](https://github.com/EvoMap/evolver) | [![GitHub stars](https://img.shields.io/github/stars/EvoMap/evolver?style=social)](https://github.com/EvoMap/evolver) | Agent self-evolution / improvement | Runtime-history analysis, protocol-constrained evolution | Medium; high-risk category | Manual review first | **Audit carefully**: self-modifying/network/shell skills are sensitive. |
| 4 | Self-improving agent | Peterskoett / OpenClaw community | [`peterskoett/self-improving-agent`](https://github.com/peterskoett/self-improving-agent) | [![GitHub stars](https://img.shields.io/github/stars/peterskoett/self-improving-agent?style=social)](https://github.com/peterskoett/self-improving-agent) | Capturing learnings/errors/preferences | Persistent learning notes, corrections, feature-request memory | Medium-high, privacy-sensitive | Manual install from repo | Check where it stores memory and what it reads. |
| 5 | OpenClaw master skills | LeoYeAI | [`LeoYeAI/openclaw-master-skills`](https://github.com/LeoYeAI/openclaw-master-skills) | [![GitHub stars](https://img.shields.io/github/stars/LeoYeAI/openclaw-master-skills?style=social)](https://github.com/LeoYeAI/openclaw-master-skills) | Big OpenClaw skills bundle | Tavily search, multi-search, local search, scraping, research tools | Medium; pick individual skills | Manual pick/copy | Avoid bulk-installing all skills. |
| 6 | OpenClaw tools | Feahter | [`Feahter/openclaw-tools`](https://github.com/Feahter/openclaw-tools) | [![GitHub stars](https://img.shields.io/github/stars/Feahter/openclaw-tools?style=social)](https://github.com/Feahter/openclaw-tools) | OpenClaw utilities and safety | `skill-vetter`, `skill-web-search`, auto-updater, retrieval templates | Medium-high | Manual pick/copy | Good source for vetting and utility patterns. |
| 7 | Web Search Pro | Zjianru | [`Zjianru/web-search-pro`](https://github.com/Zjianru/web-search-pro) | [![GitHub stars](https://img.shields.io/github/stars/Zjianru/web-search-pro?style=social)](https://github.com/Zjianru/web-search-pro) | Multi-engine web search | Tavily, Exa, Serper, SerpAPI, filtering, date ranges, news mode | Medium-high; requires API keys | Follow repo instructions | Use when one search provider is not enough. |
| 8 | OpenClaw skill-agent-browser wrapper | clawdbrunner | [`clawdbrunner/skill-agent-browser`](https://github.com/clawdbrunner/skill-agent-browser) | [![GitHub stars](https://img.shields.io/github/stars/clawdbrunner/skill-agent-browser?style=social)](https://github.com/clawdbrunner/skill-agent-browser) | OpenClaw wrapper for Agent Browser | Browser automation CLI instructions for OpenClaw | High for OpenClaw | Follow repo instructions | Wrapper points to `vercel-labs/agent-browser`; prefer upstream for code review. |
| 9 | Skill of Skills | the911fund | [`the911fund/skill-of-skills`](https://github.com/the911fund/skill-of-skills) | [![GitHub stars](https://img.shields.io/github/stars/the911fund/skill-of-skills?style=social)](https://github.com/the911fund/skill-of-skills) | Discovery and meta-skill workflows | Skill discovery, evaluation, registry-like metadata | Medium | Follow repo instructions | Useful as a catalog, but verify downstream sources. |
| 10 | Acontext | memodb-io | [`memodb-io/Acontext`](https://github.com/memodb-io/Acontext) | [![GitHub stars](https://img.shields.io/github/stars/memodb-io/Acontext?style=social)](https://github.com/memodb-io/Acontext) | Agent memory layer | Captures learnings from agent runs and stores them as skill files | Medium; privacy-sensitive | Follow repo instructions | Inspect storage location and data captured. |

---

## Specific Claude / Agent Skills worth tracking

| Skill | Source repo | Live stars | Useful for | Why it matters | Portability note |
|---|---|---|---|---|---|
| `docx` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Word document creation/editing | One of the official document skills | Usually portable if runtime tools exist |
| `pdf` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | PDF generation/analysis | Official document skill | Check dependencies and sandbox rules |
| `pptx` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Slide generation/editing | Official presentation skill | Portable if slide tooling exists |
| `xlsx` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Spreadsheet work | Official spreadsheet skill | Portable if spreadsheet runtime exists |
| `skill-creator` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Creating new skills | Helps write well-structured skills | Useful in any `SKILL.md` ecosystem |
| `mcp-builder` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | MCP server creation | Helps agent connect to tools | Useful if your workflow uses MCP |
| `frontend-design` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Better frontend UI | Base design skill; complements `impeccable` | Portable as guidance |
| `webapp-testing` | [`anthropics/skills`](https://github.com/anthropics/skills) | [![GitHub stars](https://img.shields.io/github/stars/anthropics/skills?style=social)](https://github.com/anthropics/skills) | Browser-based app tests | Great for local UI testing | Needs Playwright/browser tools |
| `find-skills` | [`vercel-labs/skills`](https://github.com/vercel-labs/skills) | [![GitHub stars](https://img.shields.io/github/stars/vercel-labs/skills?style=social)](https://github.com/vercel-labs/skills) | Skill discovery | Helps identify/install relevant skills | Good meta-skill |
| `core-web-vitals` | [`addyosmani/web-quality-skills`](https://github.com/addyosmani/web-quality-skills) | [![GitHub stars](https://img.shields.io/github/stars/addyosmani/web-quality-skills?style=social)](https://github.com/addyosmani/web-quality-skills) | Web performance | Focused on LCP, INP, CLS style fixes | Needs project/build access |
| `copywriting` | [`coreyhaines31/marketingskills`](https://github.com/coreyhaines31/marketingskills/tree/main/skills/copywriting) | [![GitHub stars](https://img.shields.io/github/stars/coreyhaines31/marketingskills?style=social)](https://github.com/coreyhaines31/marketingskills) | Marketing copy | Practical for landing pages and campaigns | Guidance skill, low tooling risk |
| `prd-development` | [`deanpeters/Product-Manager-Skills`](https://github.com/deanpeters/Product-Manager-Skills) | [![GitHub stars](https://img.shields.io/github/stars/deanpeters/Product-Manager-Skills?style=social)](https://github.com/deanpeters/Product-Manager-Skills) | PRDs and product specs | Helps structure requirements | Guidance skill, low tooling risk |

---

## Suggested install snippets

### Generic Skills CLI

```bash
# List available skills in a repo, if supported
npx skills add OWNER/REPO --list

# Install a specific skill globally for Claude/Codex-style agents, if supported
npx skills add OWNER/REPO --skill SKILL_NAME -g
```

### OpenClaw / ClawHub style

```bash
# Example: install OpenClaw Agent Browser from ClawHub
clawhub install thesethrose/agent-browser

# Or with npx
npx clawhub@latest install thesethrose/agent-browser
```

### Manual copy style

```bash
# Claude-style global skills
mkdir -p ~/.agents/skills
cp -R ./some-skill-folder ~/.agents/skills/some-skill

# OpenClaw-style skill folder; adjust path to your OpenClaw setup
mkdir -p ~/.openclaw/skills
cp -R ./some-skill-folder ~/.openclaw/skills/some-skill
```

---

## Security checklist before installing skills

- Read the full `SKILL.md`.
- Search for hidden shell commands, curl/wget pipes, obfuscated code, and external network calls.
- Check scripts under `scripts/`, `bin/`, `hooks/`, `.claude/`, `.agents/`, and install files.
- Avoid skills that ask for broad access to `.env`, SSH keys, browser profiles, crypto wallets, or session logs.
- Run high-risk skills in a sandbox, container, or throwaway VM.
- Prefer official repos or well-known maintainers.
- Pin a commit SHA for production use instead of installing from a moving `main` branch.
- Do not bulk-install a large skill pack into a sensitive machine.
- For OpenClaw, be extra cautious because skills may guide an agent with local file, shell, network, browser, and account access.

---

## Maintenance notes for this README

- Star badges auto-update via Shields.io, but GitHub and Shields may cache them.
- If a repo moves or is renamed, update both the link and badge URL.
- For source credibility, prefer rows with a direct GitHub repo containing `SKILL.md`.
- For non-GitHub or marketplace-only skills, use a plain link and mark live stars as `N/A`.
- Re-check security issues before recommending any OpenClaw skill pack publicly.

