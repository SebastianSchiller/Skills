# Skills

A place to keep AI skills for your own use and share them with others.

## Repository layout

Put each skill in its own folder under `skills/`. The folder should contain a
`SKILL.md` with YAML frontmatter for the skill's name and description. Add
supporting files, such as references or scripts, alongside it when needed.

```text
skills/
  my-skill/
    SKILL.md
    references/
```

Use [`templates/SKILL.md`](templates/SKILL.md) as a starting point. Give each
skill a concise, lowercase, hyphen-separated folder and name, and write a
description that helps an AI assistant decide when to use it.

## Use and share

Follow the installation instructions for your AI tool to make a skill available
to it; tools may use different skill directories or formats. To share a skill,
send someone the GitHub link to its folder or share the repository. They can
copy the skill folder into a compatible tool's configured skills location.

## Contributing a skill

1. Create `skills/<skill-name>/SKILL.md`.
2. Describe the skill's purpose and instructions in `SKILL.md`.
3. Keep any supporting files in that skill's folder and link to them from the
   instructions.
4. Commit the skill and share the repository or folder link.
