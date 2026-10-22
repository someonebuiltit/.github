# Contributing

Thanks for wanting to help! These rules apply to every repository in the org unless that repo has its own CONTRIBUTING file.

## Workflow

1. Open an issue first for anything bigger than a small fix, so we can agree on the approach.
2. Fork the repo (or create a branch if you have write access) and keep changes focused on one thing.
3. Open a pull request against `main` and fill in the PR template.

## Rules

- `main` is protected: no force-pushes and no deleting it.
- Commit messages follow [Conventional Commits](https://www.conventionalcommits.org/) (`feat:`, `fix:`, `docs:`, `chore:` ...).
- Don't commit secrets, keys or `.env` files. Secret scanning with push protection is on and will block them.
- Keep CI green. Add or update tests when you change behavior.
- Be kind. See the [Code of Conduct](CODE_OF_CONDUCT.md).
