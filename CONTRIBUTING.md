# Contributing Guide

Thanks for your interest in improving this project.

## Workflow

1. Fork the repository.
2. Create a feature branch: `git checkout -b feat/your-change`.
3. Make focused changes with clear commit messages.
4. Run checks locally (notebook execution and linting if applicable).
5. Open a Pull Request with context, rationale, and testing notes.

## Pull Request Checklist

- [ ] Scope is focused and clearly described.
- [ ] Documentation is updated if behavior changed.
- [ ] Notebook changes are reproducible.
- [ ] Large generated outputs are removed unless required.

## Coding Notes

- Keep forecasting logic transparent and well-commented.
- Prefer deterministic behavior where possible (set random seeds).
- Separate data loading, feature engineering, and modeling logic by section.
