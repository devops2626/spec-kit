# Specify CLI (Spec Kit)

A Python CLI tool for Spec-Driven Development (SDD). It provides a structured workflow where specifications become executable artifacts, guiding AI coding agents through a multi-step process: principles, requirements, technical planning, task breakdown, and implementation.

## Setup

The package is installed in editable mode via pip:

```bash
pip install -e ".[test]"
```

This installs the `specify` command globally.

## Usage

```bash
specify --help          # Show available commands
specify init            # Initialize a new Specify project
specify check           # Check required tools are installed
specify version         # Show version and system info
specify integration     # Manage coding agent integrations
specify extension       # Manage spec-kit extensions
specify preset          # Manage spec-kit presets
specify workflow        # Manage and run automation workflows
```

## Development

Run tests:
```bash
python -m pytest tests/ --tb=short
```

## Project Structure

- `src/specify_cli/` — Python source for the CLI
- `templates/` — Prompt templates for the SDD workflow
- `scripts/` — Supporting bash/powershell scripts
- `extensions/` — Optional capability extensions
- `presets/` — Configuration presets (e.g., `lean`)
- `workflows/` — YAML workflow definitions
- `tests/` — Test suite (pytest)

## User preferences

- No special preferences recorded yet.
