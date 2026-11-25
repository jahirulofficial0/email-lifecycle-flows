<p align="center"><a href="https://cloudskillhub.com"><img src="assets/banner.png" alt="Email Lifecycle Flows" width="100%"></a></p>

# email-lifecycle-flows

🌐 **Website:** [cloudskillhub.com](https://cloudskillhub.com) · 📦 **All skills:** [skillhub](https://github.com/jahirulofficial0/skillhub)

Complete email lifecycle flows in one run — welcome, abandoned cart, post-purchase, win-back — full copy, subject lines, send timing and segment logic for every email.

**Works with:** Claude (Code, Desktop, claude.ai) · ChatGPT custom GPT · Gemini Gem

## Install

### Claude Code — this skill only
```
/plugin marketplace add jahirulofficial0/skillhub
/plugin install email-lifecycle-flows@skillhub
```
Or directly from this repo: copy `skills/email-lifecycle-flows/` into `~/.claude/skills/`.

### All 10 skills at once
See **[skillhub](https://github.com/jahirulofficial0/skillhub)** — one marketplace, or one MCP server that serves all 10 skills.

### claude.ai
Download `skills/email-lifecycle-flows/` as a ZIP → **Settings → Capabilities → Skills → Upload skill**.

### ChatGPT / Gemini
- ChatGPT GPT: [`prompts/chatgpt-gpt.md`](prompts/chatgpt-gpt.md)
- Gemini Gem: [`prompts/gemini-gem.md`](prompts/gemini-gem.md)

## Usage
Just describe the task — the skill activates when relevant. Example:

> Online store selling routers and mesh Wi-Fi. AOV $120. Klaviyo. Max discount 10%. Reorder cycle ~180 days.

See [`examples/`](examples/) for a full input → output sample.

## What you get
```
## Flow Overview
| Flow | Trigger | Emails | Exit condition |
## Segment Logic
## Welcome Flow
### Email 1 — send: immediately — goal: …
Subjects: 1) … 2) … 3) …
Preview: …
Body: …
CTA: …
## Abandoned Cart / Post-Purchase / Win-Back (same format)
## What to Test First
```

## Repository layout
```
.claude-plugin/plugin.json   Claude Code plugin manifest
skills/email-lifecycle-flows/SKILL.md       The skill
prompts/                     ChatGPT GPT and Gemini Gem versions
examples/                    Sample input and output
assets/banner.png            Social preview image
```

## Author
**Jahirul** — [cloudskillhub.com](https://cloudskillhub.com) · [github.com/jahirulofficial0](https://github.com/jahirulofficial0)

## License
MIT — see [LICENSE](LICENSE).
