# second-brain-memory

Give an agent durable, source-linked memory inside a plain markdown vault. Defines session cards, a corrections and rules file (global versus project-scoped, with one-line pointers), threads for open topics, knowledge notes that link to their sources, and receipts. Use when setting up or maintaining a personal knowledge vault, when the user corrects the agent and the correction should stick, or when work should survive across sessions.

An agent skill in the Claude Code / Agent Skills format (`SKILL.md` with YAML frontmatter). Part of a small set of original skills: see [agent-skills](https://github.com/eyupgulcu/agent-skills) for the others.

## Install

```
git clone https://github.com/eyupgulcu/second-brain-memory ~/.claude/skills/second-brain-memory
```

On Windows, clone into `%USERPROFILE%\.claude\skills$n`. For a single project, clone into `<project>/.claude/skills/second-brain-memory`. The skill loads when a task matches its description.

## Requirements

None, text only.

## License

MIT, see `LICENSE`.

## Türkçe

Düz markdown kasa içinde kalıcı, kaynak bağlantılı ajan hafızası: oturum kartları, kurallar, açık konular, bilgi notları, makbuzlar. SKILL.md İngilizcedir. Kurulum: depoyu `~/.claude/skills/second-brain-memory` klasörüne klonlayın.
