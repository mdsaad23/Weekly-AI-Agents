# CLAUDE.md

Instructions for working in this repository (AI agents collection). See `README.md` for goals and categories.

## 1. Follow Karpathy's principles

- Simplest thing that works end-to-end. Add complexity only when a measurement or real duplication demands it, never speculatively.
- No bloat: no interface for one implementation, no config for values that never change, no boilerplate "for later", no commented-out code.
- Fewest files, shortest diff. Delete over add.
- Names over comments. Comments explain *why*, not *what*.

## 2. Every agent gets a folder

- Each agent lives in its own folder under its category: `<category>/<agent-name>/`.
- Categories: `personal/`, `learning/`, `fun/`, `dev-tools/`.
- Do not create empty category or agent folders in advance.

## 3. Every agent has a README

Each agent folder contains a `README.md` that covers:

- What the agent does and why it exists.
- The technology behind it: LLM provider and model, frameworks, libraries, and any tools it calls.
- Difficulty (Beginner, Intermediate, or Advanced).
- Cost: free tier, existing subscription, or paid credits, with the reason if paid.
- Setup and run steps.
- Source inspiration, if any, and what was changed.
- If the agent was built to test a particular theory or method (for example a prompting technique, an agent architecture, or a retrieval strategy), explain that in detail: the hypothesis, how the agent tests it, what the expected result is, and what was observed.

Add the agent to the Agent Index table in the root `README.md`.

## 4. Commit and push after every completed change

- When a change is complete, commit it and push to `origin main`.
- Do this through a Haiku subagent (`publish-to-github`), not directly in the main session.
- Use a sensible commit message that describes the change. End commit messages with:
  `Co-Authored-By: Claude Haiku 5.5 <noreply@anthropic.com>`
