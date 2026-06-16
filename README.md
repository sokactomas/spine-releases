# Spine

**Persistent memory for Claude Code — across every session.**

> Currently in beta. Free to use. macOS only.

---

## The problem

Claude Code forgets everything when you close the terminal. Every new session starts cold — no memory of your project decisions, your preferences, what you tried last week, or why you chose one approach over another.

## What Spine does

Spine runs as a local MCP server alongside Claude Code and gives it a persistent knowledge graph. Claude can remember facts, decisions, and context — and recall them in future sessions, automatically.

**What gets remembered:**
- Project decisions and the reasoning behind them ("we switched to Postgres because X")
- Your preferences and working style ("always prefer editing files over new ones")
- Cross-project knowledge that carries over between codebases
- Team context that every team member's Claude can access

**What it feels like:**
- You open a new session and Claude already knows your stack, your conventions, and what was discussed last week
- You never re-explain the same thing twice
- Claude's suggestions get better the longer you use it

---

## Install

1. Download the latest `.dmg` from [Releases](../../releases)
2. Open the `.dmg` and drag Spine to Applications
3. Launch Spine — it will configure itself as an MCP server for Claude Code automatically
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

## Roadmap

- [ ] Windows / Linux support
- [ ] Team sync (shared knowledge graph across a team)
- [ ] Web dashboard to browse and edit memories
- [ ] Support for other AI coding assistants (Cursor, Windsurf)

---

## License

Free to use during beta. See [LICENSE](LICENSE) for full terms.

Source code is not public. This repository is for distribution and feedback only.
