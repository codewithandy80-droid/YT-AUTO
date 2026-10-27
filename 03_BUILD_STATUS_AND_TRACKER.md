# 3. BUILD STATUS AND TRACKER

## Status definitions
- `NOT_STARTED`: no implementation evidence supplied.
- `IN_PROGRESS`: implementation is underway; not accepted.
- `BLOCKED`: requires missing input, decision, dependency, or access.
- `READY_FOR_REVIEW`: code and test evidence supplied, awaiting compliance review.
- `DONE`: implementation inspected and relevant acceptance tests passed.
- `REJECTED`: does not comply; fix before proceeding.
- `NOT_APPLICABLE`: explicitly approved as not applicable.

## Verified status at package creation
No app source repository or implementation code was provided for audit in this conversation. The uploaded planning material described the AI Provider & Model Manager, not a verified completed application. Thus no app feature can honestly be marked `DONE` yet.

| Area | Initial status | Evidence / next action |
|---|---|---|
| Master plan | PLAN_FINALIZED | This package records finalized decisions summarized in the conversation |
| Existing app/code audit | NOT_STARTED | Obtain repository/source files and inspect |
| Original full four skill prompts | BLOCKED | Import exact authoritative prompts; current plan contains summaries only |
| Project database and isolation | NOT_STARTED | Implement and test per roadmap |
| Project limit and deletion guard | NOT_STARTED | Implement and test |
| Project settings/duration engine | NOT_STARTED | Implement and test |
| Source Adding Panel | NOT_STARTED | Implement and test |
| Source analysis reuse/staleness | NOT_STARTED | Implement and test |
| Script edit/approval | NOT_STARTED | Implement and test |
| Video prompt skill integration | NOT_STARTED | Verify exact skill contract and test |
| Thumbnail prompt skill integration | NOT_STARTED | Verify full-script input and test |
| SEO skill integration | NOT_STARTED | Verify Roman Hindi and project-aware data |
| Provider/model manager | NOT_STARTED | Audit existing implementation; build missing pieces |
| Secret vault/security | NOT_STARTED | Security review and tests |
| Progress/retry/history | NOT_STARTED | Implement and test |
| Project ZIP export | NOT_STARTED | Implement and verify secrets excluded |
| UI/UX | NOT_STARTED | Compare screens and workflow to `08_UI_UX_SPEC.md` |
| Acceptance test suite | NOT_STARTED | Create and run tests |

## Task tracker template
Copy one row per scoped task:
| Task ID | Requirement IDs | Scope | Status | Changed files | Test command/evidence | ChatGPT review | Approved by user |
|---|---|---|---|---|---|---|---|
| TASK-001 | TBD | Initial code audit | NOT_STARTED | — | — | Pending | No |

## Rules
- Do not infer progress from a plan, mockup, or generated explanation.
- A generated file is not verified until inspected.
- A test is not passed unless its actual output/evidence is provided.
- Never mark a whole phase `DONE` when only part of it passed.
- Keep blocked items explicit.
