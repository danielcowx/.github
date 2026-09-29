# `.github` — golden org-level defaults

This is the **golden source** for every fleet owner's `.github` repository. The `ISSUE_TEMPLATE/` forms here are copied byte-for-byte into `<owner>/.github` when a fleet owner is provisioned (`repo-init --org <owner>`).

- `ISSUE_TEMPLATE/task.yml` — the Task form (identical to `goldenmasters/fleet-repo-template@main:.github/ISSUE_TEMPLATE/task.yml`).
- `ISSUE_TEMPLATE/epic.yml` — the Epic form (identical to `goldenmasters/fleet-repo-template@main:.github/ISSUE_TEMPLATE/epic.yml`).
- `ISSUE_TEMPLATE/config.yml` — turns off the blank-issue option so every UI-typed GHI arrives shaped.

`goldenmasters/fleet-repo-template` holds per-repo defaults (`.mcp.json`, `.loop-session`, `.claude/rules/`, `.gitignore`); this repo holds org-level community-health defaults that GitHub applies to every repo in the org without templates of its own.

Edit here; then re-copy into each fleet owner's `.github`. Never edit a downstream copy in place.
