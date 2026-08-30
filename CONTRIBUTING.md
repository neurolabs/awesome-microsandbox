# Contribution Guidelines

Thanks for helping keep this list useful.

## Inclusion criteria

A project qualifies if it:

- Uses, extends, wraps, packages, or integrates with [microsandbox](https://github.com/superradcompany/microsandbox) (the microVM runtime by superradcompany), and
- Is publicly available with a README that explains what it does, and
- Works, or is clearly marked as experimental/WIP.

Not accepted:

- Plain forks or mirrors of the upstream repository or SDKs.
- Bug reproduction repos.
- Unrelated projects that happen to share the name.
- Placeholder or name-squatting packages.

## Format

- One entry per line: `- [Name](link) - Description ending with a period.`
- Keep descriptions short (under ~100 characters), in English, and free of marketing language.
- Prefer the GitHub repository link; use the package registry link only when there is no repo.
- Add new entries to the end of the most specific section, or propose a new section in the PR.
- Run `npx awesome-lint` locally before opening a PR.

## Pull requests

- One project per PR (or one logical change).
- Title: `Add <project name>`.
- Explain in the PR body why the project belongs in this list.
