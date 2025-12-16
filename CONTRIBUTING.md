# Contributing

Thanks, any help is welcome! Please keep changes small and focused.

## Workflow

- Fork the repo and create a branch for each task.
- Use a clear branch name with a prefix (see below).
- Make changes and run tests/linters if present.
- Format code locally before committing (Auto Formatting) -> CI will block unformatted PRs.
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

## Formatting

To keep the codebase consistent we use **Prettier** by default and **Black** for Python.

- Please format code before opening a PR. Editors can do this automatically (recommended).
- PRs that fail formatting checks will be requested for fixes.

Editor (VS Code) recommended settings:

- Install extensions: **Prettier - Code formatter** and **Black Formatter**.
- Don't override Prettier and Black defaults!
- Recommended workspace settings (add to your global vscode settings or `.vscode/settings.json`):

```json
{
  "editor.formatOnSave": true,
  "editor.formatOnPaste": false,
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "[python]": {
    "editor.defaultFormatter": "ms-python.black-formatter",
    "editor.formatOnSave": true,
    "editor.formatOnPaste": false
  },
  "files.trimTrailingWhitespace": true,
  "files.insertFinalNewline": true
}
```

## Pull requests

- Fill out the PR template (applied automatically from `.github/`).
- Use `Closes #ISSUE_NUMBER` if the PR fully resolves an issue.
- Use `Related: #ISSUE_NUMBER` if the PR is linked but should not close the issue.
