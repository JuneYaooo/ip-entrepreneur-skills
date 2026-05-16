<div align="center">

# ip-entrepreneur-skills

**Claude Code / Codex Skill. One sentence — "diagnose this IP" — and get a full six-dimension IP entrepreneurship diagnostic report covering Positioning, Persona, Content, Data, Monetization, and Growth, with both executive summary and comprehensive versions.**

> 🧠 **Recommended pairing: [opencli](https://github.com/jackwener/opencli)** — enable web search for your AI agent so it can gather public information about the IP (media coverage, community discussions, competitor activity) across the entire internet, far beyond what a single social profile shows.

[![GitHub stars](https://img.shields.io/github/stars/JuneYaooo/ip-entrepreneur-skills?style=flat)](https://github.com/JuneYaooo/ip-entrepreneur-skills/stargazers)
[![License](https://img.shields.io/badge/license-Apache%202.0-blue.svg)](../LICENSE)
[![Claude Code](https://img.shields.io/badge/Claude%20Code-Skill-orange.svg)](https://www.anthropic.com/claude-code)

🌐 **中文** → [../README.md](../README.md)

</div>

---

## ✨ What it does

- 📊 **Six-dimension deep diagnostics** — Positioning × Persona × Content × Data × Monetization × Growth, covering the full IP entrepreneurship value chain
- 🌐 **Web-wide intelligence** — Paired with opencli for web search, auto-collects multi-platform data, media coverage, and community sentiment about the IP
- 🔍 **Competitive landscape analysis** — Auto-focuses on 5-8 players in the same track, breaking down persona, content, monetization, and livestream strategies
- 📈 **Data-driven decisions** — Revenue formula decomposition, conversion funnel diagnosis, growth stage positioning — replace intuition with data
- 💰 **Monetization path planning** — Pricing strategy, product matrix, revenue model — complete conversion path from brand influence to revenue
- 🗺️ **Death zone analysis** — Pinpoints your position in the IP lifecycle, identifies core risks, and delivers crossing strategies
- ⚡ **Dual-output mode** — Executive brief (5-minute read + action checklist) + comprehensive report (full six-dimension analysis), delivered together

---

## 🚀 Install

### Option 1: let your AI install it (recommended)

Paste this prompt into your AI assistant (Claude Code / Codex / Cursor — all work) and it will handle the install:

```
Please install ip-entrepreneur-skills for me:
https://github.com/JuneYaooo/ip-entrepreneur-skills
```

### Option 2: manual install

```bash
git clone git@github.com:JuneYaooo/ip-entrepreneur-skills.git
# Claude Code auto-discovers skills under .claude/skills/ in the current directory
# Or place it under ~/.claude/skills/ip-entrepreneur/
```

> 🧠 **Strongly recommend also installing [opencli](https://github.com/jackwener/opencli)**, which gives Claude Code web search capabilities. With web access enabled, the AI can search for real-time public information about the IP across all platforms, rather than relying solely on what you describe.

---

## 🛠 How to use inside Claude Code

Once installed, just say it in plain language. For best results, pair with opencli to enable web search.

### Mode A — Diagnose an existing IP

> Diagnose `https://github.com/alchaincyf`'s IP across positioning, persona, content, data, monetization, and long-term strategy. First search the web for their public presence.

Drop in a GitHub profile, a social media link, or even just a name. The AI uses opencli to gather public information across the web and auto-generates a full report.

### Mode B — Start from scratch

> I want to build a personal IP in [niche]. First search the web for top players in this space, then help me with positioning, persona design, and the first 30 content topics.

### Mode C — Break through a plateau

> My IP is at [current state] and stuck at [bottleneck]. Search the web for how competitors are handling this, then diagnose the problems and suggest optimization strategies.

---

## 📁 File structure

```
ip-entrepreneur-skills/
├── SKILL.md                    # Core skill entry (with YAML frontmatter)
├── AGENTS.md                   # Thin index for codex / aider / cursor agents
├── README.md                   # Project documentation
├── docs/
│   ├── README.en.md            # English README
│   └── assets/                 # Demo screenshots
└── references/                 # Six-dimension methodology deep dives
    ├── 01-positioning.md       # IP Positioning
    ├── 02-content.md           # Viral Content
    ├── 03-data.md              # Data-Driven Operations
    ├── 04-livestream.md        # Livestream Strategy
    ├── 05-monetization.md      # Monetization
    └── 06-growth.md            # Growth & Mindset
```

---

## License

Apache License 2.0
