# kondo-ramsay

Skill for auditing work artifacts.

Core pair: **Ramsay** (quality bar) + **Kondo** (does this still earn its place).
Optional extras: **Feynman** (can you explain it simply) + **Cal Newport** (what does this cost in attention).

Work only. Not people.

Verdicts: `KEEP` / `FIX` / `PARK` / `KILL`.
Output is prose, not tables.

## Voices

Core pair always on. Feynman and Cal are extra passes; the user may keep or drop them.

1. **Ramsay** — quality and competence. Would a serious professional ship this?
2. **Kondo** — earned place. Does this still serve the current work life? If not, thank the role it played and release it.
3. **Feynman** (optional) — understanding. Can you explain what this is and why it exists in plain language?
4. **Cal Newport** (optional) — attention. What does keeping this cost in focus, context switching, and maintenance?

## Verdicts

Exactly one per item. No fifth status. Vague `FIX` is `PARK`. No pep talk.

- `KEEP` — meets the bar and earns its place
- `FIX` — worth keeping if a concrete, bounded change happens
- `PARK` — not now; capture where it lives and a revisit condition
- `KILL` — release it (archive, delete, close, stop maintaining)

## Install

Copy `skill/` into your agent's skills folder as `ramsay-kondo/`. This is the open Agent Skills format (`SKILL.md` + YAML frontmatter). It works in Claude Code, Codex, Cursor, Grok, Gemini CLI, and any other agent that loads skills — or as a system prompt in any chat.

Examples:

- Claude Code: `~/.claude/skills/ramsay-kondo/`
- Cursor: `.cursor/skills/ramsay-kondo/` or `~/.cursor/skills/ramsay-kondo/`
- Codex: `.agents/skills/ramsay-kondo/` and a pointer in `AGENTS.md`
- Gemini CLI: `~/.gemini/skills/ramsay-kondo/`
- Grok: that agent's skills directory
- Any chat agent (Claude, ChatGPT, Gemini, etc.): paste `skill/SKILL.md` as a system prompt or project instructions

The folder should look like:

```
ramsay-kondo/
  SKILL.md
  references/
    voices.md
```

## Triggers

ramsay kondo, RK, auditar, filtrar.

## Sibling

To judge whether something has startup or revenue potential: [luloxi/draper-graham](https://github.com/luloxi/draper-graham).

## License

MIT. Use it, fork it, kill the parts that do not spark joy.
