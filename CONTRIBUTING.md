# Contributing to MOHAA Cooperative

## Before you write code

1. **Open an issue first.** Describe the problem you want to solve or the change you want to make. Wait for acknowledgment before starting a PR.
2. PRs without a linked issue will be closed.

## Pull requests

- Small, focused changes only (< 200 lines preferred).
- One logical change per PR. Don't mix refactoring with new features.
- Follow existing code conventions and naming patterns.
- Test your changes before submitting.
- Write a clear PR description: what changed, why, how you tested it.

## Commit messages

Format: `type: short description`

Types: `feat`, `fix`, `refactor`, `test`, `docs`, `chore`

Example:
```
fix: prevent crash when player count exceeds max slots

Server crashed on map change when more than 16 players
were connected. Added bounds check before allocation.
```

## Scope

This project targets **OpenMoHAA only**. PRs adding support for the original retail engine will be closed.

## Architecture decisions

Architecture and technical direction are decided by the project maintainer. If you want to propose a significant change in approach, open an issue for discussion first. Do not submit large refactoring PRs without prior agreement.

## Code of conduct

Be respectful. Keep discussions technical. Personal attacks, passive-aggressive tone, and off-topic drama will result in locked threads or bans. See [CODE_OF_CONDUCT](https://www.contributor-covenant.org/version/2/1/code_of_conduct/) (Contributor Covenant v2.1).

## Response time

This is a volunteer project. There are no guaranteed response times. Patience is expected.
