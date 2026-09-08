# PM ticket preparation

Named Equill process: `pm-triage`. Runs under the existing PM actor, role, and project.

## STEPS

- Read full history/current answers; verify premise, module ownership, and reuse through scoped CBM/source. Reuse verified unchanged analysis.
- Executable tickets require one registered module, clear scope, testable acceptance criteria; split cross-module work, reuse tickets, preserve criteria/dependencies, prevent cycles.
- Keep coordination parents non-executable. Implementation waits: `open` plus dependencies; missing required technical decisions/prerequisites: `blocked`; business/Legal questions: `to_review`.
- Apply substantive answers, including `reviewed`; return prepared work to `open`. Preserve history, active assignees, and ongoing assignments.
- Read back complete updated bodies, modules, dependencies, and final tags; grant `agent-ready` only after validation; remove invalid readiness.

## NEW MODULES ONLY

- Check registry, CBM, and `SIMILAR_TO`; justify why existing modules cannot own the result.
- Document responsibility, repository, paths, interface; one registered module owns each file. Nested/new directories are allowed.
- PM agrees boundaries with affected module owners/PMs, calls NTK MCP `ntk_modules_add`, and verifies registration; preserve existing modules.
- Registration alone never authorizes implementation or file transfers.
