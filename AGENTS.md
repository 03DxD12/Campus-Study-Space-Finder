# Repository Engineering Directives

These instructions apply to all work in this repository. Follow higher-priority
platform and user instructions when they conflict with this file.

## Workflow

- Decompose complex work into small, ordered steps. Keep simple work direct.
- Before editing, inspect the relevant code and preserve unrelated user changes.
- Make surgical edits. Do not rewrite intact files or modules without a concrete
  reason.
- After editing, run the most relevant available checks. Review failures, correct
  issues caused by the change, and repeat until the acceptance criteria pass or a
  genuine blocker is documented.
- Before completion, review the changed code for logic errors, edge cases,
  security risks, type-safety issues, regressions, and missing validation.

## Implementation Quality

- Deliver complete, runnable implementations. Do not leave placeholder logic,
  fake data presented as final, or `TODO` comments in place of required work.
- Prefer the simplest solution that fully meets the request. Avoid unnecessary
  dependencies, abstraction layers, wrappers, and file growth.
- Reuse the project's existing patterns and dependencies where appropriate.
- Add comments only when they clarify non-obvious intent or constraints.
- Never claim a check passed unless it was actually run. State any checks that
  could not be run and why.

## UI and UX

- Build responsive interfaces that work across common viewport sizes.
- Use semantic HTML, accessible labels, keyboard-operable controls, visible
  focus states, sufficient contrast, and reduced-motion support where relevant.
- Preserve a clear visual hierarchy and consistent spacing, typography, and
  interaction states.
- Verify primary user flows and meaningful empty, loading, error, and success
  states when the feature requires them.

