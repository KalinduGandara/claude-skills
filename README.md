# claude-skills

My personal [Claude Code skills](https://docs.claude.com/en/docs/claude-code/skills).

## Skills

| Skill | Description |
| --- | --- |
| [`sdd`](skills/sdd/SKILL.md) | Spec-driven development from an SRS: clarify, specify, design, plan, then implement task by task. Usage: `/sdd <path-to-srs-file>` |

## Install

Symlink a skill into your personal skills directory so edits here take effect immediately:

```sh
ln -s "$PWD/skills/sdd" ~/.claude/skills/sdd
```

Or copy it into a project's `.claude/skills/` to share it with that project's collaborators.
