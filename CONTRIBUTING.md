# Contributing to Agent Governance Demo

First off, thank you for considering contributing to this project! It's people like you that make it a great tool for the community.

## Before Larger Changes

Open an issue before changing public APIs, governance semantics, or release packaging. Keep proposals focused on small, testable changes.

## Development Setup

1. Clone the repository
2. Install dependencies: `pip install -e ".[test]"`
3. Run tests: `python -m pytest`

## PR Process

1. Fork the repo and create your branch from `main`.
2. Ensure the test suite passes.
3. If you've added code that should be tested, add tests.
4. Ensure your code follows the existing style (we use `ruff` for linting).
5. Open a Pull Request!

## Code Style
We aim for zero-dependency, standard-library-only implementations. Please avoid adding third-party requirements to the `src/` directory.
