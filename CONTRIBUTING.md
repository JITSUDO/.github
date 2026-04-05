# Contributing to JITSudo

Thanks for your interest in contributing! This guide covers how to get started.

## Getting Started

1. Fork the repository
2. Clone your fork
3. Create a branch from `main`
4. Make your changes
5. Open a pull request

## Development Setup

Each repository has its own setup instructions:

- **jitsudo** — See [CLAUDE.md](https://github.com/JITSUDO/jitsudo/blob/main/CLAUDE.md) for build commands
- **jitsudo-docs** — `yarn install && yarn dev`
- **terraform-provider-jitsudo** — `go build ./...`

## Pull Requests

- Keep PRs focused — one feature or fix per PR
- Include a clear description of what changed and why
- Add tests for new functionality
- Ensure CI passes before requesting review

## Commit Messages

Use conventional commits:

```text
feat: add new feature
fix: resolve bug
docs: update documentation
chore: maintenance tasks
refactor: code restructuring
test: add or update tests
```

## Code Style

- **Go** — `gofmt`, `go vet`, `golangci-lint`
- **TypeScript** — Prettier + ESLint
- **Markdown** — markdownlint

## Reporting Issues

Use GitHub Issues. Include:

- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details (OS, browser, versions)

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.
