# GrumpiFied Designs - Copilot Instructions

## Project Overview

This repository hosts the GrumpiFied Designs Merch Site, a mirrored site for merchandise and design content.

## Repository Structure

- **Root Directory**: Contains core configuration files including `.gitignore`, `LICENSE`, and `README.md`
- The project uses Node.js/JavaScript-based tooling (based on `.gitignore` patterns)
- Build artifacts are output to `dist/`, `.next/`, or similar directories depending on the framework used

## Development Workflow

### Setup

1. Install dependencies:
   ```bash
   npm install
   ```
   or
   ```bash
   yarn install
   ```

2. Check for any environment variables needed by reviewing `.env.example` if present

### Building

- Follow standard Node.js/JavaScript project conventions
- Build outputs should be generated in directories specified in `.gitignore` (e.g., `dist/`, `.next/`, `.nuxt/`)

### Testing

- Run tests using standard npm/yarn commands:
  ```bash
  npm test
  ```
  or
  ```bash
  yarn test
  ```

### Linting

- Use ESLint for code quality checks if configured
- Run linting before submitting changes:
  ```bash
  npm run lint
  ```
  or
  ```bash
  yarn lint
  ```

## Coding Standards

- Follow JavaScript/TypeScript best practices
- Maintain consistency with existing code style
- Keep code changes minimal and focused
- Write clear, descriptive commit messages
- Add comments for complex logic or non-obvious implementations

## Pull Request Guidelines

- Keep PRs focused on a single concern or feature
- Include tests for new functionality when applicable
- Update documentation if behavior or usage changes
- Ensure all tests pass before requesting review
- Address review feedback promptly

## Files to Exclude

The `.gitignore` file defines patterns for files that should not be committed:
- Build artifacts (`dist/`, `.next/`, `.nuxt/`, etc.)
- Dependency directories (`node_modules/`, `jspm_packages/`)
- Log files (`*.log`, `logs/`)
- Environment files (`.env`, `.env.*` except `.env.example`)
- Cache directories (`.cache/`, `.parcel-cache/`, etc.)
- IDE-specific files (`.vscode-test`)

## Special Notes

- This is a merchandise/design site, so pay attention to visual consistency and user experience
- When making changes, consider both desktop and mobile views
- Preserve any existing branding and design elements
