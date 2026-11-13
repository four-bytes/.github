# Contributing

Thank you for your interest in contributing to a Four Bytes project.

## Workflow

1. **Open an issue first** describing the bug or feature, unless it is a trivial fix.
2. Fork the repository and create a branch from `main` (e.g. `fix/123-short-description`).
3. Make your changes with tests.
4. Open a pull request that references the issue (`Closes #123`).
5. A maintainer reviews it; please keep the conversation on the pull request.

Security issues: see [SECURITY.md](SECURITY.md) — never in public issues.

## Coding Guidelines (PHP)

- PHP version as required by the package's `composer.json`
- `declare(strict_types=1);` in every file
- Coding style: [PER Coding Style](https://www.php-fig.org/per/coding-style/)
- Static analysis must pass at the level configured in the repository (`phpstan.neon`)
- Tests with PHPUnit for every change in behavior; the test suite must pass
- No new runtime dependencies without discussion in the issue

## Commits and Pull Requests

- English for code, comments, commit messages, issues and pull requests
- [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `chore:` …)
- One topic per pull request, keep it small
- Update `HISTORY.md` for user-visible changes
- Never commit credentials, tokens or personal data

## Releases

Versions follow [Semantic Versioning](https://semver.org/); releases are tagged `vX.Y.Z`.

## License

By contributing, you agree that your contributions are licensed under the repository's license.
