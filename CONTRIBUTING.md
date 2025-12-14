# Contributing to @zennal/dsa

Thank you for your interest in contributing to @zennal/dsa! This document provides guidelines and information for contributors.

## Table of Contents

- [Development Setup](#development-setup)
- [Running Tests](#running-tests)
- [Building the Project](#building-the-project)
- [Code Style](#code-style)
- [Submitting Changes](#submitting-changes)
- [Reporting Issues](#reporting-issues)
- [License](#license)

## Development Setup

1. **Fork and Clone the Repository**

   ```bash
   git clone https://github.com/girish-kor/zennal-dsa.git
   cd zennal-dsa
   ```

2. **Install Dependencies**

   ```bash
   npm install
   ```

3. **Verify Setup**

   Run the type checker to ensure everything is set up correctly:

   ```bash
   npm run type-check
   ```

## Running Tests

This project uses Vitest for testing. To run the tests:

```bash
npm test
```

For watch mode during development:

```bash
npm test -- --watch
```

## Building the Project

To build the project for distribution:

```bash
npm run build
```

This will generate the bundled files in the `dist/` directory.

## Code Style

This project uses ESLint and Prettier for code formatting and linting.

- **Linting**: `npm run lint`
- **Formatting**: `npm run format`

Please ensure your code passes linting and is properly formatted before submitting.

### TypeScript Guidelines

- Use TypeScript for all new code
- Provide proper type annotations
- Follow the existing code patterns in the project

## Submitting Changes

1. **Create a Feature Branch**

   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make Your Changes**

   - Write tests for new functionality
   - Ensure all tests pass
   - Run linting and formatting
   - Update documentation if necessary

3. **Commit Your Changes**

   Use clear, descriptive commit messages:

   ```bash
   git commit -m "Add feature: brief description of changes"
   ```

4. **Push and Create Pull Request**

   ```bash
   git push origin feature/your-feature-name
   ```

   Then create a pull request on GitHub.

### Pull Request Guidelines

- Provide a clear description of the changes
- Reference any related issues
- Ensure CI checks pass
- Request review from maintainers

## Reporting Issues

If you find a bug or have a feature request:

1. Check existing issues to avoid duplicates
2. Use the issue templates when available
3. Provide detailed information including:
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details (Node.js version, OS, etc.)

## Documentation

To generate TypeDoc documentation:

```bash
npm run docs
```

Documentation will be generated in the `docs/` directory.

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project (MIT License).