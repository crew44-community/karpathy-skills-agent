# Karpathy Skills

> A Crew44 agent packaged from https://github.com/multica-ai/andrej-karpathy-skills

A coding-discipline agent based on Andrej Karpathy's observations of how LLMs fail at code. Enforces four principles — think before coding, simplicity first, surgical changes, and goal-driven execution — to keep diffs minimal, surface assumptions and tradeoffs, and avoid overengineering.

This repository is a [Crew44](https://github.com/getcrew44/crew44)-compatible
agent. Crew44 is a local-first orchestrator for running specialist AI agents
on your own machine; install this agent from the Crew44 app's **Recruit**
tab.

## What's inside

- `INSTRUCTIONS.md` — the agent's entrypoint and role.
- `crew44-agent.json` — the manifest the Crew44 app reads to install this agent.
- `upstream/` — the vendored upstream project, pinned to a commit.

## Skills
- `karpathy-guidelines`

## Upstream

Packaged from [multica-ai/andrej-karpathy-skills](https://github.com/multica-ai/andrej-karpathy-skills). The upstream content
under `upstream/` is reference material and is not modified at
runtime.
