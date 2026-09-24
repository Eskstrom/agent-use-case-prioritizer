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

<!-- portfolio-future-plans:start -->
## Future plans and PRD direction

*Planning review: 24 September 2026. These are proposed next steps, not completed work or measured outcomes.*

**Priority recommendation:** Recommend consolidation before further standalone development.

Preserve the workflow scoring rubric, assumptions and alternative choices within Enterprise LLM Model Hub.

### Next scope

- [ ] Inventory unique requirements and planning notes before moving anything.
- [ ] Use Enterprise LLM Model Hub as the proposed destination; record the destination and retained source history after an actual migration.
- [ ] Update incoming portfolio links before considering archive status. No consolidation or archival is implied by this planning note.

### Validation and decision criteria

Explain one automate, augment or decline decision and how changing an assumption alters it. Reopen a standalone PRD only if user discovery establishes a distinct problem that the retained project cannot cover.
<!-- portfolio-future-plans:end -->
