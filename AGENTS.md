# AGENTS.md

## Required reading

Before editing, read:

1. `README.md`
2. `docs/STATUS.md`
3. `docs/NEXT.md`

## Purpose

This repository is a **sandbox-only test fixture** for validating Codex GitHub connector behavior, AGENTS.md adherence, and RTS-style routing output format.

It is now an archive/delete candidate.

- This is **not** a production RTS repository.
- Do **not** import RTS / Skills / MCP Packs / Hermes / Talent Registry / Signal Feeds implementations here.
- Do **not** add API keys, secrets, credentials, private links, or runnable integration code.
- Do **not** add SNS publishing flows or any external system mutation logic.
- Do **not** add product behavior, customer information, or production responsibilities.

## Authority and references

- External repositories, signal feeds, registries, and docs are **reference/candidate inputs only**.
- They must not be treated as source-of-truth authority in this sandbox.

## Scope of changes

- Keep this repository minimal.
- Prefer archive or deletion review over expansion.
- Add only test tasks, minimal registry references, and result/log placeholders needed for pre-test checks.
- Do not absorb responsibilities that belong to the real production RTS repository.

## Reporting format after changes

When producing change summaries for this repository, separate output into:

1. Confirmed facts
2. Assumptions
3. Unverified items
4. Risks

For documentation-only changes, also confirm that no production behavior, external mutation behavior, customer material, secrets, credentials, private links, or runtime integration was added.
