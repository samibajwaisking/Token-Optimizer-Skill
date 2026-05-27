# Contributing to Token Optimizer Skill

Thank you for your interest in improving this skill. Contributions that make
Claude more efficient and powerful are always welcome.

---

## Before You Contribute

1. **Star the repository** — required by the license before any use or contribution
2. **Read SKILL.md** — understand the existing patterns before adding new ones
3. **Check open issues** — your idea might already be in progress

---

## What We Welcome

### High-Priority Contributions
- New compression patterns with token count evidence
- Additional system prompt templates for untested domains
- Before/after examples with real token measurements
- Improved one-shot examples for existing domains
- Bug fixes in existing reference files

### Medium-Priority Contributions
- New domain-specific output format templates
- Edge case handling in context management techniques
- Performance benchmarks comparing techniques

### Not Accepted
- Unverified claims about token savings (provide measurements)
- Domain-specific content that narrows the skill's applicability
- Redundant patterns already covered in compression-patterns.md
- Changes that break the skill's language consistency (English only)

---

## Contribution Process

### Step 1 — Fork and Branch

```bash
git clone https://github.com/samibajwaisking/token-optimizer-skill
cd token-optimizer-skill
git checkout -b feature/your-improvement-name
```

**Branch naming convention:**
- `feature/add-[thing]` — new content
- `fix/[what-was-wrong]` — corrections
- `improve/[what-improved]` — enhancements

---

### Step 2 — Make Your Changes

Follow these standards:

**For new compression patterns:**
- Add to the correct category in `references/compression-patterns.md`
- Format: `| Verbose phrase (N tokens) | Compressed form | Savings % |`
- Include token counts measured with a standard tokenizer

**For new system prompt templates:**
- Add to `references/system-prompt-templates.md`
- Must be under 200 tokens
- Must include: role + rules + default format
- Test it with at least 3 prompts before submitting

**For new before/after examples:**
- Add to `examples/before-after.md`
- Must include: before (with token count), after (with token count), savings %, quality note

**Language rule:** All content must be in English. No exceptions.

---

### Step 3 — Test Your Changes

Before submitting:
- [ ] Load the modified SKILL.md into Claude and verify it triggers correctly
- [ ] Run at least 3 test prompts using any new patterns you added
- [ ] Confirm token savings are real (not theoretical)
- [ ] Check that no existing content was accidentally modified

---

### Step 4 — Submit Pull Request

```bash
git add .
git commit -m "type: brief description of change"
git push origin feature/your-improvement-name
```

**Commit message types:**
- `feat:` — new content or feature
- `fix:` — correction
- `improve:` — enhancement to existing content
- `docs:` — documentation only

**PR description must include:**
- What you changed and why
- Token savings evidence (if applicable)
- Test prompts you used

---

## Code of Conduct

- Be constructive, not critical
- Provide evidence for claims
- Respect the existing architecture — don't restructure without discussion
- Credit your sources if you reference external research

---

## Questions?

Open an issue or reach out via [samioutic.com](https://samioutic.com)
