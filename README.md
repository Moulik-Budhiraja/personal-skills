# personal-skills

Skills I use with AI agents. Each skill is a folder with a SKILL.md.

## Structure

- `<skill-name>/SKILL.md` is the skill itself and is the only thing that gets pushed.
- `<skill-name>/test/`, `<skill-name>/comparisons/`, and `<skill-name>/scratch/` are local working folders for iterating on a skill. They are gitignored because they can contain personal data.

## Installing a skill

From this repo:

```sh
npx skills add Moulik-Budhiraja/personal-skills -g -a claude-code -s <skill-name> -y
```

From a local checkout:

```sh
npx skills add ./<skill-name> -g -a claude-code -y
```

`-g` installs globally, `-a claude-code` targets Claude Code, `-s` picks a skill from the repo (use `-s '*'` for all). If the CLI copies the skill directly into `~/.claude/skills/` instead of placing it in `~/.agents/skills/` with a symlink, fix the layout:

```sh
mv ~/.claude/skills/<skill-name> ~/.agents/skills/<skill-name>
ln -s ../../.agents/skills/<skill-name> ~/.claude/skills/<skill-name>
```
