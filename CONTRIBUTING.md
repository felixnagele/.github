# Contributing

Thanks, any help is welcome! Please keep changes small and focused.

## Workflow

- Fork the repo and create a branch for each task.
- Use a clear branch name with a prefix (see below).
- Make changes and run tests/linters if present.
- Commit with a short imperative message (e.g. `Add X`, `Fix Y`, `Refactor Z`).
- Open a pull request to `main` using the PR template.
- For larger changes, open an issue first to discuss (please use the issue templates).

## Branch naming

Use one of these prefixes to indicate the type of change:

- `feature/short-description` → new functionality
- `fix/short-description` → bug fixes
- `task/short-description` → maintenance, cleanup, restructuring
- `docs/short-description` → documentation changes
- `test/short-description` → adding or adjusting tests
- `refactor/short-description` → code restructuring without new features

If your change doesn’t fit these categories, use a new prefix only when it makes clear sense.

## Pull requests

- Fill out the PR template (applied automatically from `.github/`).
- Use `Closes #ISSUE_NUMBER` if the PR fully resolves an issue.
- Use `Related: #ISSUE_NUMBER` if the PR is linked but should not close the issue.
