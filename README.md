# Auto Claude Skills Marketplace (acsm)

Plugin marketplace for intelligent skill activation in Claude Code.

## Installation

Add this marketplace to Claude Code:

```
/plugin marketplace add damianpapadopoulos/auto-claude-skills-marketplace
```

## Available Plugins

### auto-claude-skills

**Description:** Intelligent skill activation hook with phase-aware routing and agent team support for the design-plan-implement-review-ship pipeline

**Install:**
```
/plugin install auto-claude-skills@acsm
```

**What you get:**
- Config-driven skill routing with dynamic registry built at session start
- Role-based orchestration: process skills drive, domain skills inform, workflow skills stand alone
- Phase-aware routing (Design, Plan, Implement, Review, Ship, Debug)
- Agent team skills: design-debate (MAD), agent-team-execution, agent-team-review
- Session start health check with setup hints for missing plugins
- 111 tests, graceful fallback for degraded environments
- Optional user configuration via `~/.claude/skill-config.json`
- Works with plugins from any marketplace (superpowers, claude-plugins-official, etc.)
- Zero configuration required — full curated experience out of the box

**Repository:** https://github.com/damianpapadopoulos/auto-claude-skills

## License

MIT