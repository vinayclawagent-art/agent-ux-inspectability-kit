---
name: agent-ux-inspectability-review
description: "Reusable checklist for reviewing agent UIs and CLIs for provenance, background work, and state transparency."
status: draft
source_note: "[[Grok Build Inspectability and Background Task UX]]"
---

# agent-ux-inspectability-review

## Trigger
Use when a future task matches this source-backed workflow: The inspectability details are directly reusable as a Hermes/Mission Control UX checklist: show tool origins, stream command output, preserve parent session state, and expose loop cadence.

## Procedure
1. Define the bounded job and the artifact that proves completion.
2. List required tools, data access, constraints, and safety boundaries.
3. Run or delegate the job only when the human explicitly asks for execution.
4. Capture evidence: commands, links, screenshots, cost/time, failure modes, and verification output.
5. End with a decision: promote, iterate once, hold, or retire.

## Pitfalls
- Do not confuse a polished plan with a validated workflow.
- Do not execute installs or third-party tools just because a tweet mentioned them.
- Preserve source links and evidence paths so the artifact remains auditable.

## Verification
- A real trial has a filled evidence packet.
- The output artifact is inspectable by someone who did not run the task.
- The decision block names the next action and owner.
