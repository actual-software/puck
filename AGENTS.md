# Development Guidelines

This document contains development guidelines and policies for the puck repository.

## Project Structure & Module Organization

The repository follows a monorepo structure:
- `/apps` - Application packages
- `/packages` - Shared library packages
- Follow the existing directory conventions when adding new modules

## Build, Test, and Development Commands

- `pnpm install` - Install dependencies
- `pnpm build` - Build all packages
- `pnpm test` - Run test suite
- `pnpm dev` - Start development server

## Coding Style & Naming Conventions

1. Use TypeScript for all new code
2. Follow existing naming conventions in each package
3. Use descriptive variable names
4. Add JSDoc comments for public APIs

### State Management

1. Use Jotai for global state management

## Testing Guidelines

1. Write unit tests for business logic
2. Include integration tests for critical user flows
3. Aim for meaningful test coverage
4. Ensure tests are maintainable and focused

## Commit & Pull Request Guidelines

1. Write clear, descriptive commit messages
2. Reference issue numbers in commits when applicable
3. Keep PRs focused and reviewable
4. Ensure CI passes before requesting review
5. Review your own diff before submitting

## Security & Configuration Tips

1. Never commit sensitive data or credentials
2. Use environment variables for configuration
3. Follow security best practices for dependencies
4. Keep dependencies up to date