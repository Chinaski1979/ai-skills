# AI Skills

A collection of reusable agent skills and instructions. Add a skill here once, then reuse it instead of rewriting the prompt.

Each skill lives in `.cursor/skills/<skill-name>/SKILL.md`. Opening this repository in Cursor makes those skills available in this project. To use one everywhere, copy or symlink its folder into `~/.cursor/skills/`.

## Skills

| Skill | Invoke when |
| --- | --- |
| [Adversarial Code Review](.cursor/skills/adversarial-code-review/SKILL.md) | You want a hostile review that only looks for reasons to reject the current changes. |

## Adding a skill

1. Create `.cursor/skills/<skill-name>/SKILL.md`.
2. Put `name` and `description` in the frontmatter. Set `disable-model-invocation: true` when the skill should run only if you name it.
3. Keep the instruction body verbatim.
4. Add a row to the table above.
