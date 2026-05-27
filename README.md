<div align="center">

<img src="https://img.shields.io/badge/TOKEN-OPTIMIZER-6C63FF?style=for-the-badge&labelColor=0D0D0D&logo=anthropic&logoColor=white" alt="Token Optimizer" height="40"/>

# Token Optimizer — Claude AI Skill

### Maximum Output. Minimum Input. Zero Waste.

[![Version](https://img.shields.io/badge/Version-1.0.0-6C63FF?style=flat-square)](https://github.com/samibajwaisking/token-optimizer-skill/releases)
[![License](https://img.shields.io/badge/License-Star%20Required-FF6B6B?style=flat-square)](LICENSE)
[![Claude Skill](https://img.shields.io/badge/Claude-AI%20Skill-FF8C00?style=flat-square&logo=anthropic)](https://claude.ai)
[![Stars](https://img.shields.io/github/stars/samibajwaisking/token-optimizer-skill?style=flat-square&color=FFD700&label=Stars)](https://github.com/samibajwaisking/token-optimizer-skill/stargazers)
[![By Sami Bajwa](https://img.shields.io/badge/By-Sami%20Bajwa-00C896?style=flat-square)](https://samioutic.com)

**⭐ Star this repo to unlock usage rights**

*Built by [Sami Bajwa](https://samioutic.com) — AI Educator & Automation Builder*

---

</div>

## 🧠 What Is This?

**Token Optimizer** is a production-ready Claude AI Skill that teaches you how to extract the **highest-quality, most complete responses** from Claude using the **fewest possible input tokens**.

> 💡 Most people waste **60–80%** of their tokens on filler, bad formatting, and unstructured prompts — and get worse results because of it. This skill fixes that.

A fully optimized session uses **3–8x fewer tokens** than an unoptimized one — for the **same or better output quality**.

---

## ✨ What This Skill Covers

<table>
<tr>
<td width="50%">

### 🗜️ Pillar 1 — Prompt Compression
Turn 50-token verbose prompts into 8-token precision instructions. Shorthand syntax for every common task type.

### 📐 Pillar 2 — Output Format Control
Eliminate 30–50% of response bloat. Tell Claude exactly what format, length, and structure you want.

### 🏷️ Pillar 3 — XML Tag Structuring
The most underused prompting technique. Reduce clarification rounds to zero with structured input.

</td>
<td width="50%">

### 📦 Pillar 4 — Instruction Density
Bundle 4 messages into 1 structured prompt. Stop the back-and-forth.

### 🚫 Pillar 5 — Negative Space Instructions
Tell Claude what NOT to do. Cuts filler by 20–35% instantly.

### 🎯 One-Shot Examples
One perfect example replaces 100 tokens of style instructions. Ready-made examples for 10 domains included.

</td>
</tr>
</table>

---

## 📁 Repository Structure

```
token-optimizer-skill/
│
├── SKILL.md                              # 🧠 Core skill file — load this into Claude
│
├── references/
│   ├── compression-patterns.md           # 50+ shorthand patterns across 6 categories
│   ├── output-formats.md                 # 10 format templates + Anti-Filler Block
│   ├── system-prompt-templates.md        # 10 production-ready system prompts (<200 tokens each)
│   ├── one-shot-examples.md              # Ready-made examples for 10 domains
│   └── context-management.md            # 7 techniques for conversation pruning
│
├── examples/
│   └── before-after.md                   # 20 real prompts with token counts (avg 65% savings)
│
├── .github/workflows/
│   └── star-reminder.yml                 # Auto-reminds contributors to star
│
├── LICENSE                               # Star-Required License
├── CONTRIBUTING.md                       # How to contribute
├── CHANGELOG.md                          # Version history
└── README.md                             # This file
```

---

## 📊 Proven Results

<div align="center">

| Technique | Average Token Savings |
|:---|:---:|
| Prompt Compression | **40–70%** input reduction |
| Output Format Control | **30–50%** response reduction |
| XML Structuring | Eliminates **2–3** clarification rounds |
| Instruction Bundling | **60–80%** fewer messages |
| Negative Instructions | **20–35%** shorter responses |
| One-Shot Examples | Replaces **~100 tokens** of style description |
| Context Pruning | **70–90%** history token reduction |
| **Combined Effect** | **3–8x fewer tokens. Same quality.** |

</div>

---

## 🚀 How to Use

### Option 1 — Claude.ai Projects (Recommended)

1. Go to [claude.ai](https://claude.ai) → **Projects**
2. Create or open a project
3. Upload `SKILL.md` as a project instruction file
4. Claude now uses all optimization techniques automatically

### Option 2 — Claude Skills (if available in your plan)

1. Go to **Settings → Skills**
2. Upload `SKILL.md`
3. Done — skill activates when relevant

### Option 3 — Paste as System Prompt

```
Copy the full contents of SKILL.md → paste into Claude's system prompt field
```

### Option 4 — API Integration

```python
with open("SKILL.md", "r") as f:
    system_prompt = f.read()

# Pass as system_prompt in your Anthropic API call
response = client.messages.create(
    model="claude-sonnet-4-20250514",
    max_tokens=1024,
    system=system_prompt,
    messages=[{"role": "user", "content": "Your task here"}]
)
```

---

## 💬 Example Prompts After Loading This Skill

```
"Optimize this prompt for me: [your verbose prompt]"
"Help me write a system prompt for a customer support bot"
"Show me the compressed version of this instruction"
"How do I structure this multi-part request efficiently?"
"Reduce tokens in this conversation history"
"Write a one-shot example for [my use case]"
```

---

## 🔥 Quick Start Formula

The fastest way to improve any prompt immediately:

```
[ROLE (1 line)] + [TASK (compressed)] + [FORMAT (explicit)] + [CONSTRAINTS (negative)]
```

**Example — Before (74 tokens):**
```
I have a Python script that I wrote and it's having some issues. Can you please 
review it carefully and tell me what's wrong with it and also suggest how I could 
improve it to make it better and more efficient?
```

**After (12 tokens):**
```
You are a Python expert. debug+optimize: [code]
Format: issues list → fixed code. No intro.
```

**Same output. 84% fewer tokens.**

---

## 📚 Reference Files Overview

| File | Contents |
|---|---|
| `compression-patterns.md` | 50+ shorthand patterns: analysis, writing, code, extraction, research, ideation |
| `output-formats.md` | 10 format templates + Universal Anti-Filler Block + length modifiers |
| `system-prompt-templates.md` | Code assistant, content writer, data analyst, support bot, researcher, summarizer, translator, creative, tutor, business automation |
| `one-shot-examples.md` | Code review, email, data extraction, simplification, summaries, social media, meeting notes, product descriptions, SEO, feedback |
| `context-management.md` | State Summary Method, Rolling Compression, Stateless Design, Role Pinning, Reference Injection, Checkpoint Commits, Context Scoping |

---

## ⚠️ License — Read Before Using

This repository uses a **Star-Required License**.

> ⭐ You must **star this repository** before using, copying, or distributing this skill.
> Attribution to **Sami Bajwa / samioutic.com** must appear in any product that uses this skill.

See [LICENSE](LICENSE) for full terms.

**[⭐ Click here to star and unlock usage →](https://github.com/samibajwaisking/token-optimizer-skill)**

---

## 👤 About the Creator

<div align="center">

<img src="https://img.shields.io/badge/Sami%20Bajwa-AI%20Educator-6C63FF?style=for-the-badge" alt="Sami Bajwa"/>

</div>

**Sami Bajwa** is an AI Educator, web developer, and digital entrepreneur based in **Sargodha, Pakistan**. He operates under the brand **SAMIOUTIC** ([samioutic.com](https://samioutic.com)) and is dedicated to helping Pakistani freelancers and learners master AI tools and earn online.

### Credentials & Expertise

- 🏆 **Anthropic Academy Certified** — Claude 101 · Claude Code in Action · AI Fluency Framework & Foundations · Introduction to Agent Skills
- 📚 **Author** — 100+ books on AI, automation, and digital skills
- 🌐 **Full-Stack Developer** — Production websites for clients in Pakistan, Dubai, Georgia, and beyond
- 🤖 **AI Automation Builder** — n8n, Claude API, ManyChat, TikTok automation systems
- 🎓 **Community Educator** — Teaching AI literacy to thousands of Pakistani learners via social media

### Projects & Work

| Project | Description |
|---|---|
| [Samioutic.com](https://samioutic.com) | Personal brand — AI education, web development, digital services |
| CIPHER Trading Skill | Claude skill for institutional-grade crypto/forex trading signals |
| HabitQuest Pro | Gamified habit tracking system (GitHub Pages) |
| VoiceScribe AI | Bilingual Urdu/English voice-to-text prototype |
| Universal AI Chat | Single-file app supporting 8 AI providers (Claude, GPT, Gemini, Groq...) |

### Connect

<div align="center">

[![Website](https://img.shields.io/badge/Website-samioutic.com-6C63FF?style=for-the-badge&logo=googlechrome&logoColor=white)](https://samioutic.com)
[![Facebook](https://img.shields.io/badge/Facebook-samibajwaisking-1877F2?style=for-the-badge&logo=facebook&logoColor=white)](https://www.facebook.com/samibajwaisking)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-samibajwa106-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/samibajwa106)
[![WhatsApp Channel](https://img.shields.io/badge/WhatsApp-AI%20Channel-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://whatsapp.com/channel/0029VbCNzQeISTkQR04DvX3r)
[![GitHub](https://img.shields.io/badge/GitHub-samibajwaisking-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/samibajwaisking)

</div>

---

## 🤝 Contributing

Contributions that improve token efficiency are welcome. Before contributing:

1. Star the repository (required by license)
2. Read [CONTRIBUTING.md](CONTRIBUTING.md)
3. Check open issues for current priorities

---

## 📄 Versions

| Version | Date | Description |
|---|---|---|
| **v1.0.0** *(Latest)* | 2025-05-28 | Initial release — 5 pillars, 6 reference files, 20 before/after examples |

See [CHANGELOG.md](CHANGELOG.md) for full version history and roadmap.

---

<div align="center">

**If this skill saves you tokens and time — drop a ⭐ on the repo.**

*It helps other developers and AI users find it.*

---

[![Star This Repo](https://img.shields.io/badge/⭐%20Star%20This%20Repo-Required%20to%20Use-FFD700?style=for-the-badge)](https://github.com/samibajwaisking/token-optimizer-skill)

**Built by [Sami Bajwa](https://samioutic.com) · [Samioutic](https://samioutic.com) · Pakistan 🇵🇰**

</div>
