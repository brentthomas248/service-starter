## Required verification commands (must pass before opening a PR)

- Install: `uv sync --dev --frozen`
- Lint: `uv run ruff check .`
- Typecheck: `uv run mypy .`
- Tests: `uv run pytest`

## PR rules

- Link a GitHub issue
- Keep PRs small and scoped
- Update or add tests for behavior changes
- Paste command output in the PR description
