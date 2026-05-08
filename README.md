# 🧠 Claude Humanizer — E-E-A-T Affiliate Edition

A Claude Code skill that transforms generic AI-generated affiliate content into human-written, Google E-E-A-T optimized articles that rank and convert.

---

## What This Skill Does

- **Humanizes** AI text by stripping robotic patterns and injecting natural rhythm
- **Optimizes for E-E-A-T** (Experience, Expertise, Authoritativeness, Trustworthiness)
- **Engineers for affiliate SEO** — product reviews, comparison tables, CTAs, disclosures
- **Preserves** your keyword architecture, internal links, and semantic structure

---

## Quick Install

### Claude Code (Project-Scoped)
```bash
mkdir -p .claude/skills/humanizer-eeat-affiliate
curl -sL https://raw.githubusercontent.com/YOURNAME/claude-humanizer-eeat-affiliate/main/skills/humanizer-eeat-affiliate/SKILL.md   -o .claude/skills/humanizer-eeat-affiliate/SKILL.md
```

### Claude Code (Global)
```bash
mkdir -p ~/.claude/skills/humanizer-eeat-affiliate
curl -sL https://raw.githubusercontent.com/YOURNAME/claude-humanizer-eeat-affiliate/main/skills/humanizer-eeat-affiliate/SKILL.md   -o ~/.claude/skills/humanizer-eeat-affiliate/SKILL.md
```

### Cursor
```bash
mkdir -p .cursor/skills/humanizer-eeat-affiliate
curl -sL https://raw.githubusercontent.com/YOURNAME/claude-humanizer-eeat-affiliate/main/skills/humanizer-eeat-affiliate/SKILL.md   -o .cursor/skills/humanizer-eeat-affiliate/SKILL.md
```

### Claude.ai Web App
1. Zip the `skills/humanizer-eeat-affiliate/` folder
2. Go to **Settings → Skills → Upload a Skill**
3. Drop the zip file

---

## Usage

Once installed, invoke in Claude Code:

```
/humanizer-eeat-affiliate
```

Then paste your AI draft. The skill will:
1. Scan for AI patterns
2. Inject E-E-A-T signals
3. Affiliate-optimize CTAs and tables
4. Return publication-ready markdown

---

## Why E-E-A-T + Affiliate?

Google's **Helpful Content Updates** and **Product Reviews Updates** specifically target thin affiliate content. This skill ensures your articles demonstrate:

| E-E-A-T Pillar | How This Skill Enforces It |
|----------------|---------------------------|
| **Experience** | First-person testing narratives, specific usage scenarios, "I've been using X for 6 months" hooks |
| **Expertise** | Technical depth, jargon used correctly, comparison nuance, pros/cons with real trade-offs |
| **Authoritativeness** | Citing sources, linking to official docs, mentioning credentials, quoting real user reviews |
| **Trustworthiness** | Honest negatives, balanced scoring, clear affiliate disclosure, updated dates, correction notes |

---

## Anti-AI Patterns Detected

The skill scans for and strips 20+ robotic patterns including:

- Significance inflation ("marks a pivotal moment")
- Hedging clusters ("could potentially be argued")
- Chatbot openers ("Great question!")
- Generic conclusions ("the future looks bright")
- Perfect symmetry (exactly 3 bullets every time)
- Passive voice piles
- Dictionary definition openers
- Filler phrases ("It's important to note that...")
- And more — see `SKILL.md` for the full table

---

## Affiliate-Specific Features

- **Comparison tables** that don't look auto-generated
- **CTA placement** after value delivery, not at every heading
- **Disclosure language** that's compliant but not intrusive
- **Price/context anchoring** with real-world usage scenarios
- **Alternatives section** that doesn't just list competitors — it explains *who* each is for

---

## Customization

### Voice Calibration
Paste a 200-word sample of your best-performing article into the chat. The skill will analyze:
- Sentence length variance
- Contraction frequency
- Formality level
- Transition style
- Slang/idiom usage

...and match that voice in all rewrites.

### Niche Packs (Coming Soon)
- `humanizer-eeat-saas/` — B2B software reviews
- `humanizer-eeat-fitness/` — Supplement and gear reviews
- `humanizer-eeat-finance/` — Credit cards, tools, apps

---

## Contributing

See [CONTRIBUTING.md](./CONTRIBUTING.md). We especially need:
- New AI pattern detections
- Niche-specific E-E-A-T examples
- A/B test data on humanized vs. raw AI content

---

## License

MIT — see [LICENSE](./LICENSE).

---

## Credits

Inspired by the original [blader/humanizer](https://github.com/blader/humanizer) skill. Expanded with E-E-A-T framework and affiliate marketing optimization.
