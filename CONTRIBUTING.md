# Contributing to Unqor repositories

Thank you for your interest in contributing. This document describes how we work and how to make contributions that can be reviewed and merged efficiently.

If you are contributing for the first time, please read these guidelines carefully.

## Get started
1. Read the repository README and any repository-specific CONTRIBUTING notes.
2. Check open issues and pull requests — your work may already be underway.
3. If you're unsure, open a discussion or issue to propose the change before doing heavy work.

## Issue guidelines
- Use a short, descriptive title.
- Provide a clear description including:
  - The problem or request
  - Steps to reproduce (for bugs)
  - Expected vs actual behavior
  - Environment and versions, if relevant
- Tag the issue appropriately (bug, enhancement, docs, question).

## Pull request process
1. Fork the repository and create a branch named with a short descriptive path:
   - feature/<short-description>
   - fix/<short-description>
   - docs/<short-description>
2. Keep each pull request focused on a single logical change.
3. Include tests that validate the change and update documentation as needed.
4. Run linters and automated checks locally before creating a PR.
5. In the PR description include:
   - What the change is and why it is necessary
   - Related issues (use "Closes #123" when appropriate)
   - Test plan and how to verify
6. Use small, descriptive commits. Squash and rebase as needed for a clean history when requested.

## Code style and quality
- Follow the repository's existing style and lint rules.
- Write meaningful names and short functions.
- Prefer clarity over cleverness.
- Add tests for behavior, not implementation details.

## Tests & CI
- Unit and integration tests are required for changes that affect logic.
- If your change requires environment setup, document the steps for the reviewer or include lightweight mocks.
- All GitHub Actions or CI checks must pass before merging.

## Security & sensitive data
- Do not include secrets (tokens, passwords, private keys) in code, commits, or issues.
- For sensitive disclosures, email contact@unqor.com instead of using public issues.

## Code of Conduct
We expect contributors to follow our Code of Conduct. See CODE_OF_CONDUCT.md.

## Maintainers and reviews
- Maintainers assign reviewers and will give timely feedback.
- Be responsive to review comments and engage constructively.
- If a PR is stalled, maintainers may request changes, close, or take over the work.

## Licensing and copyright
- By contributing, you agree that your contributions will be made available under the repository license.
- If your employer requires an agreement, ensure you have permission to contribute under the project license.

Thank you for contributing — clear, testable, and well-documented contributions help everyone move faster.
