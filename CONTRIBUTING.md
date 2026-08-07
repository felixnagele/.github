# Contributing

Thanks, any help is welcome! Please keep changes small and focused.

## Workflow

- Fork the repo and create a branch for each task.
- Use a clear branch name with a prefix:
  - `feature/short-description` for new functionality
  - `fix/short-description` for bug fixes
  - `chore/short-description` for maintenance, cleanup, restructuring
- Commit using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/#summary):
  - Format: `<type>(<optional scope>): <description>`
  - Types: `feat` `fix` `chore` `docs` `refactor`
  - Breaking changes: append `!` (e.g. `feat!:`) and describe the change in the body.
- Open a pull request to `main` using the PR template.
- For larger changes, open an issue first to discuss.
- Use `Closes #ISSUE_NUMBER` if the PR fully resolves an issue, otherwise `Related: #ISSUE_NUMBER`.
