# Agent Use-Case Prioritizer

**Status: Concept brief.** The features below are proposed; this repository does not yet contain an implemented application or measured results.

[Portfolio](https://eskstrom.github.io/) · [Related projects](https://eskstrom.github.io/?category=tools-play#library)

## Product brief

An interactive scoring tool that helps product teams decide whether a workflow should be automated, augmented with AI, or deliberately declined.

## Design focus

A transparent rubric for choosing automation, assistance, or no intervention.

## Proposed scope

- Workflow intake form: user value, frequency, data access, error cost, trust, integration effort.
- Weighted rubric with editable weights.
- Recommendation: automate, augment, investigate, or decline.
- Decision record listing assumptions and required guardrails.

## Validation targets

- Every recommendation is traceable to inputs.
- Compare several sample workflows and explain prioritization trade-offs.

## Potential implementation

TypeScript, Next.js, SQLite/Supabase.

## Guardrails

Do not present the score as a universal truth; label it as a configurable prioritization aid.

[Implementation planning notes](notes/IMPLEMENTATION-NOTES.md)
