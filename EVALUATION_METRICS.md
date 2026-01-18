# Evaluation Metrics Rules & Constraints

## Purpose
Define how the prompt-compiler system records and preserves evaluation metrics for each user intent and generated CTC.

## Required Data (per user intent)
- Raw user intent
- Generated CTC
- Claude Code execution behavior:
  - Reasoning used
  - Time spent
  - Tokens spent
  - Questions asked to the user
- Efficiency percentage for intent → CTC conversion

## Storage Requirements
- Store all metrics in a database.
- Preserve data for all intents and CTCs.
- Do not delete or overwrite prior records.

## Constraints
- Do not optimize or alter requirements based on metrics.
- Do not infer additional fields beyond those listed above.
