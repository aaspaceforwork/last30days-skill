# Local fork

Repository: https://github.com/aaspaceforwork/last30days-skill
Upstream: https://github.com/mvanhorn/last30days-skill

The upstream README and translations describe the product for its users. They do not require installing it globally to work on this checkout in T3 Code.

- Work in a branch and push completed and unfinished work to this fork.
- Run `uv run pytest` for Python changes; MCP changes additionally use `bash mcp/scripts/sync-engine.sh` and `(cd mcp && go test -race ./...)`.
- See [development-reference.md](development-reference.md) for release/changelog contracts and subsystem guidance.
- Tasks: https://github.com/aaspaceforwork/last30days-skill/issues

Credentials and data from private projects must not enter this public fork. No new deployment or installation is part of this documentation change.
