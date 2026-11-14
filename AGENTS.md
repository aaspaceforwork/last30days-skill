# last30days fork

This checkout is aaspaceforwork/last30days-skill, a public fork of mvanhorn/last30days-skill. Read README.md, docs/fork.md and docs/development-reference.md for the subsystem being edited. Test in the checkout; do not install global skills. Keep version changes for release PRs; use a changelog fragment or the documented skip-changelog path. Never commit credentials or private project data.

Save completed and in-progress changes to a separate GitHub branch. Preserve unrelated work.

For onboarding changes only: Step 0 has THREE branches: Claude Code Modal Flow, Non-Modal Prose Flow, and Grok Bot Prose Flow. Details are in docs/development-reference.md.

## Security hygiene

Never commit real API keys. Use skills/last30days/scripts/lib/env.py for environment-based auth; fixtures must contain dummy values only.
