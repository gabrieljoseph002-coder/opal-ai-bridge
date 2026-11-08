# Second-Brain Repository Workflow

Canonical reference for AI agents working on O-Bot / Antigravity's Obsidian-backed second-brain implementation. Read this before relevant work.

## Required upstream repositories

| Repository | Purpose |
|---|---|
| https://github.com/kepano/kepano-obsidian | Primary reference vault: structure, templates, Bases, sample notes. |
| https://github.com/obsidianmd/jsoncanvas | Open JSON Canvas specification for .canvas files. |
| https://github.com/obsidianmd/obsidian-releases | Official plugin, theme, and public release metadata; not Obsidian source code. |
| https://github.com/obsidianmd/obsidian-sample-plugin | Official starter template for community plugin development. |
| https://github.com/kepano/40-questions | Annual and decade reflection questions; optional review workflow. |
| https://github.com/kepano/obsidian-minimal | Minimal Obsidian theme. |
| https://github.com/kepano/flexoki | Flexoki color system and palettes. |

## Mandatory instructions for agents

1. At the start of work involving Obsidian, persistent memory, the Galaxy Map, Canvas, graph ingestion, Bases, or plugins, read this file.
2. Inspect the existing O-Bot implementation and vault before proposing or making changes. This is an integration task, not a redesign or replacement.
3. Check each upstream repository's current README, license, default branch, and relevant files before relying on it. Do not assume upstream contents are unchanged.
4. Keep the seven upstream repositories separate. Do not merge them into one repository or blindly overwrite the user's existing vault or .obsidian settings.
5. Treat Markdown and YAML as source knowledge; parse [[wiki-links]] and JSON Canvas according to their documented formats. Preserve metadata and provenance.
6. Keep the Obsidian vault authoritative. Derived indexes and Galaxy Map state must be reproducible from source files.
7. Make agent memory writes scoped, attributable, validated, and version-controlled.
8. Never commit secrets, credentials, tokens, private customer data, or other sensitive information to this public repository.
9. Before changes, identify target files and intended modifications. Run relevant validation and report verified results; never claim untested functionality works.
10. If GitHub/network access is unavailable to an agent, state that limitation and request the minimum needed access or a local checkout. Do not pretend to have read a repository.

## Access and scope

All seven upstream repositories are public, but public visibility does not guarantee that every AI runtime has network access or GitHub tools. Each agent must verify its own access. Review current license and attribution terms before copying code or assets.

This workflow applies to Obsidian vault structure, templates, properties, Bases, graph and Canvas; Hippocampus memory ingestion and retrieval; Galaxy Map graph extraction; and plugin/theme integration. It is not necessary to load these repositories for unrelated tasks.