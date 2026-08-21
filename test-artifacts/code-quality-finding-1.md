# Code quality finding reference

Attempted to fetch GitHub code quality finding **#1** on `sperez-source/build820`.

- MCP `get_code_quality_finding`: 403 Resource not accessible by integration
- REST `/code-quality/findings` and `/code-quality/findings/1`: 404 Not Found
- No code scanning analysis, Dependabot disabled, no secret-scanning alerts

Closest in-repo findings (manual TODO scan):
- `apps/cli/meridian_cli/main.py` — export_tasks unimplemented (3 TODOs)
- `lib/partial-implementations/webhook-retry/dispatcher.py` — HTTP dispatch TODOs

This file exists only to attach a PR to that lookup. Safe to delete.
