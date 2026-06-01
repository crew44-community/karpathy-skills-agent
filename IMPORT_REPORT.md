# Import Report: Karpathy Skills

- Source: https://github.com/multica-ai/andrej-karpathy-skills
- Version: 1.0.0
- Upstream commit: 2c606141936f1eeef17fa3043a72095b4765b9c2
- Imported at: 2026-06-01T06:39:35Z
- Layout: upstream-wrapper

## Detected skills (1)
- karpathy-guidelines — `upstream/skills/karpathy-guidelines/SKILL.md`

## Files included in the install payload (11)
- AGENT.md
- crew44-agent.json
- upstream/.claude-plugin/marketplace.json
- upstream/.claude-plugin/plugin.json
- upstream/.cursor/rules/karpathy-guidelines.mdc
- upstream/CLAUDE.md
- upstream/CURSOR.md
- upstream/EXAMPLES.md
- upstream/README.md
- upstream/README.zh.md
- upstream/skills/karpathy-guidelines/SKILL.md

## Files filtered out by the importer (1)
- IMPORT_REPORT.md

## Human review

Before publishing:

1. Read `AGENT.md` and rewrite the placeholder role paragraph so the
   agent has a concrete job description.
2. Confirm the detected `skills[]` actually point at real `SKILL.md`
   files (and remove any that are stale or empty).
3. Trim `crew44-agent.json` payload globs to keep the installed payload
   small. The default wrapper exclude list is conservative; large
   repos usually need more excludes.
4. Tag the repo with `v1.0.0` once the wrapper is published.
