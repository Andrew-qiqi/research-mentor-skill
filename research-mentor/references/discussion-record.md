# Discussion Record

Use this when the user asks to save, record, summarize consensus, or produce meeting notes.

The record is a deterministic summary of what was decided in this discussion. It is not hidden memory and should not include unsupported embellishment.

## Default File Policy

Do not write files unless the user asks to save or record.

If writing and no destination is specified:

1. Prefer an existing `research-notes/` directory.
2. Otherwise prefer an existing `.research/meeting-notes/` directory.
3. If neither exists, create `research-notes/`.

Name files with date and topic:

```text
YYYY-MM-DD-short-topic.md
```

Use the current conversation date/time when available. If exact local time is not available, record the known date and timezone context.

## Required Content

Include:

- Discussion time.
- Topic.
- Confirmed conclusions.
- Shared consensus.
- Assumptions and constraints.
- Evidence checked, if any.
- Reasonable inferences.
- Speculative ideas.
- Hypotheses to verify.
- Next actions.
- Open questions.

## Style

Write like lab meeting notes:

- concise
- conclusion-forward
- clear about confidence
- explicit about what changed because of the discussion
- no generic recap of every conversational turn

## Integrity Rules

- Do not treat unverified ideas as conclusions.
- Do not invent evidence or decisions.
- Do not include private personal details unless relevant to the research decision and provided by the user.
- Preserve uncertainty when the discussion did not resolve it.
