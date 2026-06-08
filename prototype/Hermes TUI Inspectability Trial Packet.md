# Agent UX Inspectability Kit — Trial Packet

Source package: [[Agent UX Inspectability Kit]]  
Improvement loop: [[Agent UX Inspectability Kit Loop]]  
Source note: [[Grok Build Inspectability and Background Task UX]]

## When to use
Use this packet during the next real Hermes TUI or Mission Control inspectability review. It sequences the existing prototype and proof fields so the future run can produce source-backed evidence without pretending validation has already happened.

## Ordered packet steps

| Step | Artifact / action | Owner | Evidence to attach | Status |
| --- | --- | --- | --- | --- |
| 1 | Open `inspectability-checklist.html` and fill it for the real target workflow. | _TBD during live run_ | Completed builder/checklist markdown export. | _TBD_ |
| 2 | Capture the real run context and constraints before acting. | _TBD during live run_ | Source URL, repo/task link, target surface, blocked paths, budget/timebox. | _TBD_ |
| 3 | Attach proof from the run. | _TBD during live run_ | screenshots or notes for tool-origin labels, command-output streaming, background-loop state, and parent-session recovery. | _TBD_ |
| 4 | Make the explicit gate decision. | _TBD during live run_ | One of: promote checklist / pilot-only / iterate checklist / hold. | _TBD_ |
| 5 | Update package, loop, and skill-draft notes only after the real evidence exists. | _TBD during live run_ | Changelog line and links to filled proof artifacts. | _TBD_ |

## Trial fields

- Trial date: _TBD during live run_
- Target workflow / surface: _TBD during live run_
- Human reviewer: _TBD during live run_
- Agent/model/tooling used: _TBD during live run_
- Inputs provided: _TBD during live run_
- Output artifact link: _TBD during live run_
- Evidence attachment links: _TBD during live run_
- Decision: _TBD — choose promote checklist / pilot-only / iterate checklist / hold_
- Follow-up owner/date: _TBD during live run_

## Minimum evidence checklist

- [ ] Source or task link is captured.
- [ ] The prototype export is attached without editing away failures.
- [ ] At least one real output artifact, screenshot, log excerpt, or review note is linked.
- [ ] The decision is written as promote / pilot-only / iterate / hold-style language.
- [ ] Package and loop changelogs are updated only after the real run.

## Copyable handoff block

```markdown
### Agent UX Inspectability Kit trial handoff
- Target: 
- Source/task link: 
- Prototype export: 
- Evidence links: 
- Decision: 
- Reviewer: 
- Follow-up: 
```

## Copyable changelog line after the real run

```markdown
- YYYY-MM-DD: Filled [[Hermes TUI Inspectability Trial Packet]] during a real Hermes TUI or Mission Control inspectability review and recorded the promote checklist / pilot-only / iterate checklist / hold decision with linked evidence.
```

## Next action
Packet ready for the next real trial. No validation evidence was invented in this cron improvement.
