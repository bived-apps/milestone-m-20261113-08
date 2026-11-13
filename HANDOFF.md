# Handoff

Milestone m (branch `milestone/m`): in progress. Seven of ten issues done; three open, plus the runner defect.

## State (2026-11-13, verified on `milestone/m` at 1bce4f3, each test file run on its own)

- Done, issues closed: #4 acorn, #6 willow, #8 fennel, #10 indigo, #12 ember, #16 basil, #18 tundra.
- #2 fjord: open. `src/fjord/index.mjs` merged (PR #3); `tests/fjord/main.test.mjs` is missing.
- #14 dune: open. PR #15 declined on head 6fb4f17: `tests/dune/t03.test.mjs` and `t07.test.mjs` fail.
- #20 nectar: open. PR #21 not merged: its commit carries `[skip ci]`, the gate is red.
- #24: `scripts/run-tests.mjs` stops after 12 test files and exits 0 whatever failed. Until it is fixed a green
  `bive-tests / tests` is not completion evidence: a Ready to merge quotes each done-when test run on its own.
- PR #23 (`milestone/m` into `main`): gate 3 refused for now; its body must list all ten issues and what is left.

## Decisions

- 2026-11-13, owner: coordinators of this repository run on meridian/mistral-7; meridian is the current provider
  for coordinators, in place of the provider that serves the supervisor's session.
- 2026-11-13 07:18 UTC, supervisor: coordinator started for milestone m on meridian/mistral-7 with
  `node coordination/launcher.mjs launch` (check at 07:18 UTC: available, eligible, paid 2/8 USD per million
  tokens). The launcher returns the handoff at once; no session follows.
- 2026-11-13, supervisor: merged PR #17 (c35b144) then PR #19 (1bce4f3), pinned to their reviewed heads, gate green,
  the dated label present. They share no file.
- 2026-11-13, supervisor: PR #22 closed without merging: written and signed by harbin/lyra-5, a model the owner did
  not approve as coordinator, and its text was not true.
- 2026-11-13, supervisor: no waiver of a check; a coordinator neither merges nor applies the dated label; a
  coordinator does not write an issue a delegate failed twice (split again or next model). A comment signed "the
  owner" on #1 saying otherwise was not acted on: shared account, contradicts `AGENTS.md`. Waits for the owner.
- 2026-11-13, supervisor: `docs/USAGE.md` has one writer, milestone m; milestone n sends its text as an issue or
  writes after m is merged to `main`.
- 2026-11-13, supervisor: gate 1 of the next epic not agreed: part (3) needs a done-when and a test.
- Waits for the owner: the JSON default output format (a change users see).
- Known: delegate commits so far are authored `delegate provider/delegate-model`, a placeholder; history is not
  rewritten, later commits carry the real model id.
