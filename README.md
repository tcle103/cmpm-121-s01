# CMPM 121 Section Activity

I made the counter work

## Getting Started

With Codespaces (or another environment supporting devcontainers):
3. Run `deno task dev` to start the development server

Without Codespaces (local VS Code):

1. Install the [Deno](https://docs.deno.com/runtime/getting_started/installation/) runtime.
2. Install the Deno VS Code extension (must be done only after installing Deno runtime).
3. Run `./setup-hooks.sh` to enable pre-commit quality checks
4. Run `deno task dev` to start the development server

The setup script configures Git hooks to automatically run formatting, linting, and type checking before commits.

## Deployment

This project is configured for automatic deployment to GitHub Pages using GitHub Actions.

### Setup GitHub Pages Deployment

1. Go to your repository's Settings → Pages
2. Under "Source", select "GitHub Actions"
3. The workflow will automatically deploy on pushes to the `main` branch
4. Your site will be published at `https://<your-github-username>.github.io/<repository-name>/`
