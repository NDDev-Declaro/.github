# Organization profile maintenance

This repository owns the public organization profile and cover in `profile/README.md` and
`profile/assets/`. Keep the profile in English and website links on `nddev.ai`. Do not publish
private system details, customer data or confidential material. Preserve the organization avatar
unless requested otherwise.

Run `just --list` for commands (`just check` validates formatting and local Markdown links).
Work on task branches from `dev` and merge with merge-commit pull requests into `dev`; once
the full check on `dev` passes, promotion moves `main` forward to the checked commit.
