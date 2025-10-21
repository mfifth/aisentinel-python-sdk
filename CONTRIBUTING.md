# Contributing to AISentinel Python SDK

Thank you for your interest in contributing to the AISentinel Python SDK! We welcome contributions from the community.

## Development Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/aisentinel/aisentinel-python-sdk.git
   cd aisentinel-python-sdk
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install -e ".[dev]"
   ```

4. **Run tests**
   ```bash
   pytest
   ```

## Code Style

This project uses several tools to maintain code quality:

- **Black** for code formatting
- **isort** for import sorting
- **mypy** for type checking
- **ruff** for linting

Run all checks:
```bash
black aisentinel/
isort aisentinel/
mypy aisentinel/
ruff check aisentinel/
```

## Testing

- Write tests for new features in the `tests/` directory
- Aim for high test coverage
- Run tests with `pytest`

## Pull Request Process

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Make your changes
4. Run tests and linting
5. Commit your changes (`git commit -m 'Add amazing feature'`)
6. Push to the branch (`git push origin feature/amazing-feature`)
7. Open a Pull Request

## Commit Messages

Use clear, descriptive commit messages. We follow conventional commits:

- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation
- `test:` for tests
- `refactor:` for code refactoring

## Issues

- Check existing issues before creating new ones
- Use issue templates when available
- Provide clear reproduction steps for bugs

## Code of Conduct

Please be respectful and inclusive in all interactions. We follow the [Contributor Covenant](https://www.contributor-covenant.org/).

## License

By contributing, you agree that your contributions will be licensed under the MIT License.
