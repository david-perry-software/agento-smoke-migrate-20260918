# agento-smoke-migrate-20260918

Throwaway repository seeded to smoke `/agento agento-init --migrate`.

## Agento

Delivery work in this repository is driven by the Agento plugin (slash commands
/agento start-session, /agento new-initiative, /agento next-feature, /agento new-feature, /agento new-issue,
/agento build-feature, /agento build-issue, /agento review-feature, /agento review-issue, /agento ap, /agento ship,
/agento continue, /agento close-session, /agento start-freehand, /agento finish-freehand, /agento doctor; /agento ship audits
a finished build in place and tears its worktree down, /agento close-session is for
plan and freehand sessions and abandoned builds). Artifacts live in the companion
repository `david-perry-software/agento-smoke-migrate-20260918-docs` cloned at `../agento-smoke-migrate-20260918-docs` —
`features/YYYY/MM/<slug>/`, `issues/YYYY/MM/<slug>/`, and
`initiatives/YYYY/MM/<slug>/` there; configuration is this repository's
`.github/agento.json`.
Commands are always written `/agento <name>`; a bare `/<name>` or a `.prompt`/`.md`
suffix is read as the canonical command and proceeds without confirmation.

### Commands

- Install: `none`
- Test: `none`
- Typecheck: `none`
- Lint: `none`
- Full verification: `none — no CI`

### Verification strategy

none — no runnable code

### Shared resources

none

### Skills

| Domain | Skill |
|---|---|
| none | none installed |
