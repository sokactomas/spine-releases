<p align="center">
  <img src="icon-v0.6.1.png" width="128" />
</p>

# Spine

**Persistent memory and a shared brain for your AI coding CLIs.**

![macOS](https://img.shields.io/badge/macOS-13%2B-black) ![Beta](https://img.shields.io/badge/status-beta-orange) ![Free](https://img.shields.io/badge/price-free-brightgreen)

> Currently in beta. Free to use. macOS only.

---

<!-- Replace with a screenshot or GIF of Spine in action -->
<!-- ![Spine screenshot](screenshot.png) -->

---

## The problem

Claude Code, Codex, and other AI coding CLIs forget everything when you close the terminal. Every new session starts cold — no memory of your project decisions, your preferences, what you tried last week, or why you chose one approach over another. You re-explain the same context. You re-derive the same decisions. You paste the same boilerplate into every session.

## What Spine does

Spine is a macOS desktop app with a built-in MCP server that gives your AI coding CLIs — Claude Code, Codex, Antigravity — a shared persistent knowledge graph. It runs in the background, learns from your sessions, and makes sure every agent remembers what matters. Automatically.

**What gets remembered:**
- Project decisions and the reasoning behind them ("we switched to Postgres because X")
- Your preferences and working style ("always prefer editing files over new ones")
- Dead ends and corrections so your agent doesn't retry what already failed
- Team context that every team member's Claude Code or Codex can access

**What Spine does on top of memory:**
- Keeps Claude, Codex and Antigravity wired to the same MCP hub and registry
- Routes hard advisor calls automatically by the CLI that asked — no Claude/Codex switch to manage
- Spots uncovered task patterns passively and treats them as an auto-learn queue, not a manual inbox
- Lets Claude ask Codex (and vice versa) — a different model answering with its own session context
- Learns which recalled decisions you actually use and stops surfacing what you always dismiss

**What it feels like:**
- You open a new session and your agent already knows your stack, your conventions, and what was discussed last week
- You never re-explain the same thing twice
- Claude's and Codex's suggestions get better the longer you use Spine — for you personally, and for your whole team

---

## Install

1. Download the latest `.dmg` from [Releases](../../releases)
2. Open the `.dmg` and drag Spine to Applications
3. Launch Spine — it appears in the menu bar and auto-configures itself as an MCP server for Claude Code and Codex
4. Restart your CLI so it reloads the updated context and skills

That's it. Spine runs passively in the background.

## Latest release

- [v0.6.1](releases/v0.6.1.md)
- Highlights: zero-config advisor routing, passive auto-learn skill handling, safer Codex skill projection, and the refreshed spine icon across app, menu bar and About.

---

## Requirements

- macOS 13 or later
- At least one AI CLI: [Claude Code](https://claude.ai/code) or [Codex](https://github.com/openai/codex)

---

## Beta

Spine is in active beta. Things may break, APIs may change. When something goes wrong or you have an idea:

**→ [Open an issue](../../issues/new/choose)**

I read every issue personally. No Jira, no ticket queues.

---

## License

Free to use during beta. See [LICENSE](LICENSE) for full terms.

Source code is not public. This repository is for distribution and feedback only.
