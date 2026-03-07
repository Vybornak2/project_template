# __package_name__

__package_description__

## Development

### Environment Setup - uv

```bash
uv venv
uv sync
.venv\Scripts\activate

# Sync development group dependencies  
uv sync --dev
```

### Pre-commit

```bash
# Update pre-commit hooks
pre-commit autoupdate 
# Install pre-commit hooks 
pre-commit install
# Run pre-commit hooks on all files without committing
pre-commit run --all-files
```

### Testing - Pytest

```bash
# Run all tests
pytest  
# Run tests matching a specific pattern
pytest -k "test_pattern"
```

### Linting and Formatting - Ruff

```bash
# Check for linting errors and formatting issues
ruff check .
# Fix linting errors automatically (use with caution)
ruff check . --fix

# Format code
ruff format .
```

### Type Checking - TY

```bash
# Run type checking
ty check .
```

### Resources

- [uv](https://docs.astral.sh/uv/)
- [pre-commit](https://pre-commit.com/)
- [pytest](https://docs.pytest.org/en/stable/)
- [ruff](https://docs.astral.sh/ruff/)
- [ty](https://docs.astral.sh/ty/)
