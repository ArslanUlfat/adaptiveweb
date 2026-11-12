# Contributing to AdaptiveWeb

Thank you for contributing to AdaptiveWeb!

## Development Workflow

1. Fork the repository.
2. Create a branch from `develop`.
3. Implement your changes.
4. Add or update tests.
5. Run the tests and lint checks.
6. Commit using Conventional Commits.
7. Open a Pull Request against `develop`.

## Branch Naming

Use these prefixes:

- `feature/` - New features
- `fix/` - Bug fixes
- `docs/` - Documentation
- `refactor/` - Code refactoring
- `perf/` - Performance improvements
- `test/` - Tests
- `chore/` - Maintenance

Examples:
- `feature/network-detection`
- `fix/profile-switching`
- `docs/installation-guide`

## Commit Message Convention

Follow Conventional Commits:

- `feat:` New feature
- `fix:` Bug fix
- `docs:` Documentation
- `perf:` Performance improvement
- `refactor:` Code refactoring
- `test:` Tests
- `build:` Build system changes
- `ci:` CI changes
- `chore:` Maintenance

Examples:

feat: add network detection
fix: prevent unnecessary profile switching
docs: update installation guide

## Pull Requests

- Keep PRs focused and reasonably small.
- Explain what changed and why.
- Link related issues.
- Include tests for new functionality.
- Update documentation when needed.
- Ensure all CI checks pass.

## Code Guidelines

- Use TypeScript where applicable.
- Keep the core framework-independent.
- Avoid unnecessary dependencies.
- Consider browser compatibility.
- Prioritize performance and accessibility.
- Never compromise essential website functionality.
