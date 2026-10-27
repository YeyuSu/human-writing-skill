# Human Writing Skill / 说人话

A bilingual writing skill for natural technical conversations, rigorous academic prose, and professional correspondence.

## Contents
- `SKILL.md` — entry point and common rules
- `references/conversation.md` — chat and technical discussion
- `references/academic.md` — papers, abstracts, figure legends, journal letters
- `references/professional.md` — emails, work messages, applications
- `tests/manual-evaluation.md` — test prompts and acceptance checks

## Installation

### Claude Code
Copy the whole `human-writing-skill` folder to `~/.claude/skills/human-writing/`.

### Codex and compatible agents
Copy the whole folder to `~/.agents/skills/human-writing/`. Some Codex setups also support `~/.codex/skills/human-writing/`.

### Cursor
If your Cursor setup supports Agent Skills, put the folder in its recognized skills directory (often `~/.agents/skills/human-writing/`). Otherwise copy the core instructions into a project rule such as `.cursor/rules/human-writing.mdc`, with an appropriate always-on or on-demand trigger.

## Usage
Ask: “Use the human-writing skill, conversation mode, to answer in Chinese.”
Or: “Use human-writing academic mode to revise this paragraph; preserve all claims and qualifiers.”

For default behavior, place a short preference in your agent's global instructions:
“Apply human-writing to prose responses. Choose conversation, academic, or professional mode by task. Preserve scientific precision.”

## Scope
This is a writing style guide, not an AI-detector bypass or a guarantee that writing will appear human-authored. It does not alter underlying factual reliability.
