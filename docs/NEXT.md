# codex-connector-test Next Actions

The next goal is archive or deletion review, not expansion.

## Next Tasks

1. Confirm whether this repository is still needed for connector testing.
2. Confirm whether any useful notes should be moved to `rts-dev-protocol`.
3. Confirm that no secrets, credentials, private links, customer material, or runtime behavior are present.
4. Confirm that no active repository depends on this test fixture.
5. Decide whether to archive, delete, or keep as a tiny public test fixture.

## Suggested Outcomes

Prefer one of these final outcomes:

| Outcome | Meaning |
|---|---|
| Delete | Remove the repository if it has no remaining value |
| Archive | Preserve it read-only as connector-test history |
| Keep Minimal | Keep only if future connector checks still need a public sandbox |

## Do Not Do Yet

Do not:

- add product behavior
- add RTS implementation behavior
- add component shelf material
- add external system mutation logic
- add customer information
- add secrets, credentials, tokens, or private links
- expand the repository beyond connector-test scope

## Next Recommended Task

If this repository is kept, add a short note to `rts-dev-protocol` explaining when to use a connector-test sandbox.

If it is not kept, delete or archive it after human confirmation.
