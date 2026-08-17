# personal-skills

Skills I use with AI agents. Each skill is a folder with a SKILL.md.

## Structure

- `<skill-name>/SKILL.md` is the skill itself and is the only thing that gets pushed.
- `<skill-name>/test/`, `<skill-name>/comparisons/`, and `<skill-name>/scratch/` are local working folders for iterating on a skill. They are gitignored because they can contain personal data.

## Installing a skill

Copy the skill folder to `~/.agents/skills/` and symlink it into `~/.claude/skills/`:

```sh
cp -r <skill-name> ~/.agents/skills/<skill-name>
ln -s ../../.agents/skills/<skill-name> ~/.claude/skills/<skill-name>
```
