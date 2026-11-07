# AI Agents

A collection of AI agents built for day-to-day use, learning, and fun. Each agent is either a personal tool, a hands-on way to understand a concept, or a playful experiment. Where useful, we start from ideas in existing open-source repositories and adapt them to our needs.

## Principles

- **Free first.** Use free LLM access wherever it works well: NVIDIA's hosted models (build.nvidia.com), other free-tier APIs, and free credits.
- **Use existing subscriptions.** Prefer the Claude or Codex subscriptions over paid API credits.
- **Buy credits only when necessary.** Paid API usage needs a clear reason, and the reason is noted in the agent's README.
- **Simplest thing that works.** Start small, add complexity only when it is needed.

## Categories

Agents are grouped by what they are for:

| Category | Purpose |
|---|---|
| `personal/` | Tools for everyday life and work |
| `learning/` | Agents built to understand a concept (RAG, tool use, agent loops, evals) |
| `fun/` | Playful and experimental agents |
| `dev-tools/` | Agents that help with coding and building other agents |

## Difficulty

Each agent is also tagged with a difficulty level:

- **Beginner:** one model call or a short script, no external services beyond one API.
- **Intermediate:** multiple tools, memory, or a simple multi-step loop.
- **Advanced:** multi-agent coordination, retrieval over large data, or evaluation pipelines.

## Layout

Each agent lives in its own folder under its category:

```
<category>/<agent-name>/
├── README.md      # what it does, difficulty, free-tier setup, how to run
├── ...            # code
```

Each agent README should state:

1. What the agent does and why it exists.
2. Difficulty level.
3. Which LLM it uses and whether that is free, subscription-based, or paid.
4. Setup and run steps.
5. Source inspiration, if any, and what was changed.

## Agent Index

| Agent | Category | Difficulty | LLM / cost | Status |
|---|---|---|---|---|
| _None yet_ | | | | |

## Inspiration

Ideas are taken from public repositories. Credit the original project in the agent's README and note what was adapted.
