# Agent Etna — Contract & Guardrails

This file is maintained automatically by **Agent Etna** for **CS370 Current Emerging Trends**.
It is this agent's behavioral **contract**: what it's for, who it serves, what's
in and out of scope, plus a log of every change Etna has applied — so the whole
footprint is visible and auditable in your own repo.

_Maintained by Agent Etna. Don't edit by hand — it is rewritten on every shipped change._

## Agent
- **Repo:** `giuerr/CS370-Current-Emerging-Trends` (branch `main`)

## Behavioral contract
_No calibration set yet — Agent Etna uses general defaults until you calibrate this agent._

## Guardrails
- No behavioral calibration set yet — Agent Etna uses general defaults until you calibrate this agent.

## Change history

### 2026-08-20 · Cycle 2 · 1 change · merged
- **behavior:honest-limits** — The agent needs a concrete example to guide its refusal of out-of-scope requests, especially regarding code implementation.

### 2026-08-20 · Cycle 2 · 1 change · merged
- **intent-comprehension** — The agent failed to identify ambiguity and provided a summary; this prompt update explicitly directs it to clarify such ambiguities.

### 2026-08-20 · Cycle 2 · 1 change · merged
- **context-retention** — The agent denied the repo covered 'reward_shaping_function' while the instructions themselves list 'reward assignment' as a provided starter game function, so the fix is to require a synonym scan before declaring a topic absent.

### 2026-08-20 · Cycle 1 · 1 change · merged
- **safety:input-jailbreak** — The agent needs to explicitly decline requests for creative content to prevent potential jailbreaks.

### 2026-08-20 · Cycle 1 · 1 change · merged
- **behavior:tone-under-pressure** — The agent's tone guide needs to explicitly cover challenging interactions to maintain professionalism.
