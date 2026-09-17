# Shared workspace (opt-in for this folder)

This folder is part of Donnie's shared work context. Source of truth:
`~/Documents/Claude/Projects/workspace` (GitHub `ghostbusters-repo/workspace`).

Start: read `CONTEXT.md` there, then the `projects/*.md` and `systems/*.md` the task touches, then the
newest entry in `work/log/<YYYY-MM>.md`. Follow `conventions.md` (PHI rules, ticket style, the review
gate `tools/review.sh` for anything that leaves the repo). Repo beats local memory when they disagree.

End: append a `work/log` entry (tool + machine), put durable facts in `projects/` or `systems/`, rules in
`conventions.md`, decisions in `DECISIONS.md`, then run `tools/sync.sh` and confirm the push.

Never commit secrets or customer identifiers. Tokens live in `~/.*_token` files, read with `$(cat file)`.
