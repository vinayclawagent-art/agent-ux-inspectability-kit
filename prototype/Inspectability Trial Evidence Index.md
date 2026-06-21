# Inspectability Trial Evidence Index

Status: template-ready; evidence pending.

Use this index during the next real Hermes/Mission Control inspectability review to map every proof link to the exact claim it is allowed to support. Do not upgrade README, prototype, or skill wording until the linked evidence is attached and graded by [[Inspectability Evidence Quality Rubric]].

## Trial metadata

| Field | Fill during trial |
|---|---|
| Operator |  |
| Review surface | Hermes TUI / Mission Control / other: |
| Date/time |  |
| Trial packet | [[Hermes TUI Inspectability Trial Packet]] |
| Debrief | [[Post-Trial Debrief Template]] |
| Rubric | [[Inspectability Evidence Quality Rubric]] |
| Promotion card | [[Inspectability Promotion Decision Card]] |

## Evidence-to-claim map

| Proof item | Required link / attachment | Claim it can support | Rubric score | Allowed wording before proof | Patch target after proof |
|---|---|---|---|---|---|
| Tool/provenance screenshot |  | Agent surface exposes tool origins and command provenance. |  | "Checklist prepared for provenance review." | package README, prototype README, skill draft |
| Streaming output/log capture |  | Review can verify live command/output state without hidden background work. |  | "Evidence capture slot prepared." | prototype README, infographic caption |
| Parent/session state record |  | Parent session state remains inspectable across delegated work. |  | "State-preservation criterion defined." | package README, skill draft |
| Human decision note |  | Operator can choose promote / pilot-only / iterate / hold from evidence. |  | "Promotion gate is template-ready." | package README, root repo README |
| Follow-up patch diff |  | Claims were narrowed or upgraded only where proof supports them. |  | "Patch ledger pending real evidence." | README, prototype, skill draft |

## Minimum proof bar

- At least one screenshot or log for each major inspectability claim.
- A completed rubric row for provenance, state visibility, background task visibility, and operator decisionability.
- A completed promotion card before any wording changes from "template-ready" to "validated".
- Links to exact commits or notes for any patched README/prototype/skill claim.

## Current allowed wording

Until this index is filled with real proof, use only: **template-ready, evidence-pending, prepared for next real inspectability trial**.
