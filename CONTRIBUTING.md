# Contributing Guide

Thank you for contributing to Nucleo LDAP. This guide explains how to contribute across the organization repositories.

This repository stores the organization-level defaults. Repository-specific rules can extend this guide.

## Before You Start

- Check open issues to avoid duplicates
- Open an issue in the target repository before implementing large changes
- Use the bug report template for bugs
- Use the feature request template for new ideas

## Recommended Workflow

1. Fork the target repository and create a branch from its default branch
2. Keep commits small, readable, and focused
3. Add or update tests related to your change
4. Open a pull request using the provided template
5. Address review feedback until approval
6. For cross-repository work, open linked PRs and keep them synchronized

## Branch Naming

- `feature/<short-description>`
- `fix/<short-description>`
- `docs/<short-description>`
- `refactor/<short-description>`
- `hotfix/<short-description>`
- `chore/<short-description>`

Example:

```text
feature/ldap-group-sync
```

## Commit Message Convention

This project follows Conventional Commits:

- `feat: add LDAP group synchronization`
- `fix: resolve nested DN parsing`
- `docs: update LDAP configuration guide`
- `test: add user mapping tests`

Recommended format:

```text
<type>: <short description>
```

Common types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `ci`.

## Cross-Repository Changes

- Split changes by repository responsibility
- Open companion PRs instead of mixing unrelated concerns
- Link related PRs in each PR description
- Mention merge order when one PR depends on another

## Code Quality

- Follow the existing code style
- Avoid unrelated changes in the same PR
- Prefer short and explicit functions
- Add comments only when logic is not self-explanatory

## Tests

- Each bug fix should include a test when possible
- New features should include test coverage
- If tests are not feasible, explain why in the PR

## Pull Requests

A PR is ready for review when it:

- Is focused on one objective
- Explains context and impact
- References an issue (`Closes #...`) when applicable
- Includes manual validation steps
- Includes screenshots for UI changes
- Lists linked PRs if the change spans repositories

## Review and Feedback

- Reviewers may request technical or readability improvements
- Discussions should stay factual, respectful, and constructive
- Maintainers may ask to split overly large PRs

## Communication and Behaviour

By participating in this project, you agree to follow the repository Code of Conduct. Disrespectful, abusive, or discriminatory behaviour is not accepted.

Thank you for your contribution.
