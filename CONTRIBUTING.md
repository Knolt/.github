# Contributing to Knolt

These rules apply to every Knolt repository unless its own `CONTRIBUTING.md` or `AGENTS.md` says otherwise.

## Plan first

1. Open an issue, or pick one, that states the goal and what done looks like.
2. For anything larger than a small fix, write the plan before changing code and get it agreed.
3. Keep the plan's current state (status, next step, open items) true as the work moves.

## Branches and commits

- Name the branch after the task, such as `ask_the_case` or `fix_alert_toast`. No personal or tool prefixes.
- Keep each commit to one logical change, with a message that says what changed and why.
- Commit and push only work the owner of the change has approved.

## Pull requests

- Fill in the pull request template: purpose, what changed, and how it was checked.
- Run the repository's documented checks before asking for review, and say what you could not check.
- A passing syntax check is not product validation. For behaviour changes, run the app and record what you saw.

## Never commit

Credentials, `.env` files, keys, customer or camera footage, model weights, indexes, crops, caches, logs or backups. If one slips in, tell a maintainer at once; removing it from the latest commit is not enough.

## Data and privacy

- Treat every flag as a candidate for human review, never as a verdict about a person.
- Use only staged, licensed or approved footage for demos, tests and screenshots.
- Don't connect new cameras, call paid services or expose an app outside the local network without approval.
