# Agent Context Compression

Generic instructions for reducing token usage across an agent system without reducing correctness, safety, or task completion quality.

## Purpose

Use this when you want an agent to:

- be concise by default
- minimize total system-wide token usage
- avoid redundant retrieval and delegation
- preserve correctness, safety, and completion quality

## What this is

This repo contains a reusable instruction file that can be dropped into many agent harnesses or used as a system/developer prompt fragment.

It is intentionally:

- harness-agnostic
- provider-agnostic
- identity-neutral
- focused on token efficiency without unsafe shortcuts

## Files

- `AGENT_CONTEXT_COMPRESSION.md` — the reusable instruction set
- `LICENSE` — MIT license
- `.gitignore` — basic exclusions

## When to use it

Use these instructions when:

- the agent runs often and token cost matters
- multiple agents may duplicate work
- prompts tend to bloat over time
- you want stricter discipline around delegation, retrieval, and verbosity

Do not use it to justify guessing, hiding uncertainty, or skipping critical warnings.

## How to use it

Option 1: paste it into a system prompt.

Option 2: include it as a developer instruction file.

Option 3: merge selected sections into an existing orchestration prompt.

## Quick install

1. Copy `AGENT_CONTEXT_COMPRESSION.md` into your prompt or instruction layer.
2. Place it after role/identity instructions and before task-specific rules.
3. Keep local tool, safety, and product constraints in separate files or sections.
4. Test with one simple task and one multi-step task to confirm the shorter style still preserves correctness.

## Copy-paste example

```text
Your operating priority is to minimize total token usage across the whole agent system without reducing correctness, safety, or task completion quality.

[Paste AGENT_CONTEXT_COMPRESSION.md here]
```

## Compatibility

Works best with:

- system prompts
- developer prompts
- agent policy files
- orchestrator instruction blocks

It is not tied to any specific model provider, framework, agent runtime, or tool harness.

## Adaptation guidance

You can safely customize:

- default verbosity
- delegation thresholds
- when to ask clarifying questions
- output formatting preferences

Keep these parts intact:

- correctness over brevity
- no unsafe guessing
- no hiding uncertainty
- no omission of critical constraints or failure conditions

## Safety notes

- Do not use token efficiency as a reason to skip verification where verification is required.
- Do not suppress warnings that materially affect decisions.
- Do not remove context that changes correctness.
- If brevity and correctness conflict, preserve correctness.

## Suggested use cases

- orchestrator agents
- coding agents
- task-routing agents
- tool-using assistants
- multi-agent systems with shared budgets

## License

MIT
