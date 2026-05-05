# CODEX CONNECTOR TEST PLAN

## Objective
Validate the minimum behavior of Codex in this sandbox:
- instruction loading from `AGENTS.md`
- local registry lookup from `registry/talent-registry.yaml`
- task execution intent from `tasks/*.md`
- result artifact creation in `results/` and `rts-records/`
- RTS-style reporting sections

## Preconditions
- Repository is cloned and writable.
- No secrets are required.
- No network calls are required for baseline tests.

## Test cases
1. `tasks/001-codex-smoke-test.md`
2. `tasks/002-talent-routing-test.md`
3. `tasks/003-signal-routing-test.md`

## Pass criteria
- Codex can identify sandbox constraints.
- Codex can read local registry entries as references.
- Codex can produce result files without external mutation.
- Codex can separate facts / assumptions / unverified / risks.
