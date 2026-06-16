# Spine

**Persistent memory and a shared brain for your AI coding CLIs.**

> Currently in beta. Free to use. macOS only.

---

## The problem

Claude Code forgets everything when you close the terminal. Every new session starts cold — no memory of your project decisions, your preferences, what you tried last week, or why you chose one approach over another. You re-explain the same context. You re-derive the same decisions. You paste the same boilerplate into every session.

## What Spine does

Spine is a local MCP server that gives Claude Code a persistent knowledge graph. It runs silently in the background, learns from your sessions, and makes sure Claude remembers what matters — automatically.

**What gets remembered:**
- Project decisions and the reasoning behind them ("we switched to Postgres because X")
- Your preferences and working style ("always prefer editing files over new ones")
- Dead ends and corrections so Claude doesn't retry what already failed
- Team context that every team member's Claude can access

**What Spine does on top of memory:**
- Watches live sessions and warns before Claude retries a known dead end
- Spots task types no skill covers and offers to build missing skills automatically
- Lets your Claude ask your Codex — a different model answering with its own context
- Learns which recalled decisions you actually use and stops surfacing what you always dismiss
- Automatically allows frequently-used read-only shell commands so you stop clicking through the same permission prompts

**What it feels like:**
- You open a new session and Claude already knows your stack, your conventions, and what was discussed last week
- You never re-explain the same thing twice
- Claude's suggestions get better the longer you use it — for you personally, and for your whole team

---

## Install

1. Download the latest `.dmg` from [Releases](../../releases)
2. Open the `.dmg` and drag Spine to Applications
3. Launch Spine — it configures itself as an MCP server for Claude Code automatically
4. Restart Claude Code

That's it. Spine runs in the background.

---

## Requirements

- macOS 13 or later
- [Claude Code](https://claude.ai/code) installed

---

## Beta

Spine is in active beta. Things may break, APIs may change. When something goes wrong or you have an idea:

**→ [Open an issue](../../issues/new/choose)**

I read every issue personally. No Jira, no ticket queues.

---

## License

Free to use during beta. See [LICENSE](LICENSE) for full terms.

Source code is not public. This repository is for distribution and feedback only.
