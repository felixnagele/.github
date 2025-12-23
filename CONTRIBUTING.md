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

## Development Environment: Visual Studio Code

It is recommended to use **Visual Studio Code (VS Code)** as the default IDE for all contributions. This ensures a consistent development experience and makes it easier to follow formatting and workflow guidelines. Each repository should include a `.vscode` folder with recommended settings and extensions to help contributors get started quickly and maintain consistency.

The repository also includes editor-agnostic configuration files (e.g., `.editorconfig` and formatter config files) to ensure consistent behavior across different editors.

**Recommended setup:**

- Use VS Code for all code contributions by default.
- Ensure the `.vscode` folder exists in the repo with workspace settings and extension recommendations.
- Install the recommended extensions when prompted by VS Code.
- Use the provided workspace settings and repository configuration files for formatting, linting, and other editor behaviors.

If you use a different editor, make sure it respects the repository configuration files to maintain consistency.

## Formatting

It is required to use **Prettier** as the default formatter for all supported file types, including Markdown. The configurations are provided in the repository to ensure consistent formatting across contributions.

Code must be formatted before opening a pull request. The repository includes all required configuration files to ensure consistent formatting across editors (for example, formatter and editor configuration files). With the recommended VS Code settings and extensions, formatting is handled automatically.

## Pull requests

- Fill out the PR template (applied automatically from `.github/`).
- Use `Closes #ISSUE_NUMBER` if the PR fully resolves an issue.
- Use `Related: #ISSUE_NUMBER` if the PR is linked but should not close the issue.
