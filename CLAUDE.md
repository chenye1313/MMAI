# CLAUDE.md

This file provides guidance for AI assistants working with the MMAI repository.

## Repository Overview

**MMAI** is a project owned by `chenye1313`. It is currently in early-stage development with an initial commit structure in place.

- **Primary branch:** `master`
- **Remote:** `origin` (GitHub — `chenye1313/MMAI`)

## Project Structure

```
MMAI/
├── .git/
├── CLAUDE.md       # AI assistant guidance (this file)
└── README.md       # Project readme
```

The repository is newly initialized. As the project grows, update this section to reflect the directory layout, key modules, and entry points.

## Development Workflow

### Branching

- The default branch is `master`.
- Feature branches should be created off `master` for new work.
- Use descriptive branch names (e.g., `feature/add-model`, `fix/data-loading`).

### Commits

- Write clear, concise commit messages describing *why* the change was made.
- Keep commits focused — one logical change per commit.

### Building & Testing

No build system or test framework is configured yet. Update this section when they are added.

## Conventions

### Code Style

No linter or formatter is configured yet. When one is added, document the commands here:

```bash
# Example (update when configured):
# npm run lint
# npm run format
```

### File Organization

- Keep the root directory clean; place source code in dedicated subdirectories (e.g., `src/`, `lib/`).
- Configuration files belong in the project root.

## Key Commands

No project-specific commands are defined yet. Add them here as the project evolves:

```bash
# Build:       (not yet configured)
# Test:        (not yet configured)
# Lint:        (not yet configured)
# Run:         (not yet configured)
```

## Notes for AI Assistants

- Read existing code before proposing changes.
- Do not over-engineer; keep changes minimal and focused on the task at hand.
- When adding new dependencies, justify the choice and check for existing alternatives in the project.
- Update this file when significant structural changes are made (new frameworks, build tools, test infrastructure, etc.).
