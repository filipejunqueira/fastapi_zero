# FastAPI Zero

A FastAPI project configured with Python 3.13 and Poetry.

## Development Setup

### Using Poetry Environment

This project uses **Python 3.13.5** managed by Poetry. You have two options for running commands:

#### Option 1: Activate Poetry Shell
```bash
poetry shell
task lint
task format  
task test
task run
```

#### Option 2: Use Poetry Run (No Activation Required)
```bash
poetry run task lint
poetry run task format
poetry run task test
poetry run task run
```

### Available Tasks

- `task lint` - Run ruff linting checks
- `task format` - Format code with ruff
- `task test` - Run pytest with coverage
- `task run` - Start FastAPI development server

### Verification

To verify your Python version:
```bash
poetry run python --version  # Should show Python 3.13.5
```

---

Claude switched this repository to SSH on 2026-09-13.
Why: an HTTPS remote cannot push from the claude-sandbox container, which has no git credential helper and does not read the host's git config. SSH works there with no setup. Original remote URLs are recorded in the claude-config repo at notes/remote-urls-before-2026-09-13.txt.
