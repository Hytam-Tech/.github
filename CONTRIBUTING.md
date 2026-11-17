# Contributing

## Workflow

1. Fork the repository and branch from `main`.
2. Make a focused change. One concern per pull request.
3. Run before pushing:
   ```sh
   cargo fmt --all
   cargo clippy --all-targets -- -D warnings
   cargo test
   ```
4. Open a pull request using the template.

## Commits

[Conventional Commits](https://www.conventionalcommits.org/): `feat:`, `fix:`, `docs:`, `refactor:`, `test:`, `chore:`.

## Issues

Search existing issues first. Use the bug or feature template.
