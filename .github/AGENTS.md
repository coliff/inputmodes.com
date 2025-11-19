# Agents

<!-- https://agents.md -->

## GitHub Actions

- Always use the latest version
- YML files should begin with --- on the first line.
- All GitHub Actions should use SHA-1 pinned versions.
- If using `actions/checkout`, it should have `persist-credentials: false` set.
- All should be formatted with Prettier.

## Dependabot

- GitHub Actions updates should be grouped and updated monthly.
- npm packages should be grouped and updated monthly.
- Limit number of Dependabot PRs to be open to 2.
- Dependabot config should be formatted with Prettier.
