# Contributing

Thanks for contributing to Honest Online Learning.

## Before You Start

1. Fork or clone the repository.
2. Create a branch for your change.
3. Keep changes focused and avoid unrelated refactors.
4. Do not commit secrets, credentials, or local environment files.

## Development

```bash
npm install
npm run dev
```

Before submitting a change, run:

```bash
npm run build
```

Run linting where supported by the current project setup.

## Pull Requests

A pull request should:

- explain what changed and why
- include screenshots for meaningful UI changes when useful
- avoid unrelated formatting or dependency changes
- keep existing behavior intact unless the change intentionally modifies it
- avoid including private keys, tokens, passwords, or production credentials

## Commit Messages

Use short, descriptive commit messages, for example:

```text
fix: correct login redirect
feat: add course filtering
docs: update project readme
style: polish dashboard layout
```

## Issues

For bugs, include the affected page or feature, expected behavior, actual behavior, and steps to reproduce where possible.
