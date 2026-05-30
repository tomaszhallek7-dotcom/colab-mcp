# Contributing to Colab MCP

Thank you for your interest in contributing! This document provides guidelines and instructions for contributing to this project.

## Code of Conduct

We are committed to providing a welcoming and inclusive environment. Please read and follow our [Code of Conduct](CODE_OF_CONDUCT.md).

## How to Contribute

### Reporting Bugs

1. **Check existing issues** - Search to ensure the bug hasn't already been reported
2. **Provide details** - Include:
   - Clear description of the bug
   - Steps to reproduce
   - Expected vs actual behavior
   - Environment details (OS, versions, etc.)
   - Error messages or logs
3. **Use the bug report template** - Click "New Issue" and select the bug report template

### Suggesting Features

1. **Check existing issues** - Look for related feature requests
2. **Describe the use case** - Explain why this feature would be valuable
3. **Provide examples** - Show how the feature would work
4. **Use the feature request template** - Click "New Issue" and select the feature request template

### Submitting Changes

#### Before You Start
- Fork the repository
- Clone your fork locally
- Create a new branch: `git checkout -b feature/your-feature-name`

#### Making Changes
1. **Follow style guidelines** - Maintain consistency with existing code
2. **Write clear commit messages** - Use descriptive, imperative-mood messages
3. **Add documentation** - Update README and relevant docs
4. **Test thoroughly** - Ensure your changes don't break existing functionality

#### Commit Message Format

Follow the Conventional Commits specification:

```
<type>(<scope>): <subject>

<body>

<footer>
```

**Types:**
- `feat` - A new feature
- `fix` - A bug fix
- `docs` - Documentation changes
- `style` - Code style changes (formatting, missing semicolons, etc.)
- `refactor` - Code refactoring without feature changes or bug fixes
- `perf` - Performance improvements
- `test` - Test additions or modifications
- `chore` - Build process, dependencies, tooling

**Example:**
```
feat(mcp): add support for new Google Colab API endpoints

Implemented support for the new Colab execution API to enable
more efficient notebook operations.

Closes #42
```

### Pull Request Process

1. **Update your branch** - Rebase on main before submitting
2. **Run tests** - Ensure all tests pass locally
3. **Fill the PR template** - Provide all requested information
4. **Link related issues** - Use "Closes #issue-number" format
5. **Request reviews** - Tag relevant maintainers
6. **Respond to feedback** - Address review comments promptly

## Development Setup

### Prerequisites
- Git
- Python 3.8+ or Node.js 14+
- Required dependencies (see project README)

### Local Development

```bash
# Clone and setup
git clone https://github.com/tomaszhallek7-dotcom/colab-mcp.git
cd colab-mcp

# Create virtual environment (Python)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run tests
pytest  # or your test command
```

## Code Style Guidelines

### General
- Use meaningful variable and function names
- Keep functions small and focused
- Add comments for complex logic
- Follow DRY principle (Don't Repeat Yourself)

### Documentation
- Add docstrings to all functions and classes
- Update README for user-facing changes
- Include usage examples for new features

## Testing

- Write tests for all new features
- Maintain or improve code coverage
- Ensure tests pass before submitting PR

## Review Process

- At least one maintainer review is required
- Address all requested changes
- Maintain professional and respectful communication
- Patience - reviews may take time

## License

By contributing, you agree that your contributions will be licensed under the Apache License 2.0.

## Questions?

Feel free to:
- Open a GitHub Discussion for questions
- Create an issue for clarification
- Reach out to maintainers

Thank you for contributing! 🚀
