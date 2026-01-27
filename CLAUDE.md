# CLAUDE.md - AI Assistant Guidelines

This file provides guidance for AI assistants working with this repository.

## Repository Overview

**Project Name:** Test-Project
**Status:** New repository (initial setup)
**Primary Branch:** `main` (to be created)

### Current State

This repository is freshly initialized and ready for development. No source files, configurations, or dependencies have been added yet.

## Project Structure

```
Test-Project/
├── CLAUDE.md          # AI assistant guidelines (this file)
└── .git/              # Git repository data
```

As the project grows, update this section to reflect the actual structure:

```
# Example structure (update as project develops):
Test-Project/
├── src/               # Source code
│   ├── components/    # UI components (if applicable)
│   ├── utils/         # Utility functions
│   └── index.ts       # Entry point
├── tests/             # Test files
├── docs/              # Documentation
├── package.json       # Dependencies and scripts
├── tsconfig.json      # TypeScript configuration (if applicable)
└── CLAUDE.md          # AI assistant guidelines
```

## Development Workflow

### Getting Started

1. Clone the repository
2. Install dependencies (when added): `npm install` or `yarn`
3. Follow the conventions outlined below

### Git Conventions

**Branch Naming:**
- Feature branches: `feature/<description>`
- Bug fixes: `fix/<description>`
- Documentation: `docs/<description>`
- AI-assisted work: `claude/<description>-<session-id>`

**Commit Messages:**
- Use clear, descriptive messages
- Start with a verb (Add, Fix, Update, Remove, Refactor)
- Keep the first line under 72 characters
- Reference issues when applicable: `Fix #123: description`

**Example:**
```
Add user authentication module

- Implement JWT token generation
- Add login/logout endpoints
- Include password hashing utilities
```

### Code Review Process

1. Create a feature branch from `main`
2. Make changes and commit
3. Push to remote and create a pull request
4. Ensure all checks pass
5. Request review if required
6. Merge after approval

## Coding Conventions

### General Principles

- Write clean, readable, and maintainable code
- Follow the DRY (Don't Repeat Yourself) principle
- Keep functions small and focused
- Use meaningful variable and function names
- Add comments only when the code isn't self-explanatory

### File Organization

- Group related files together
- Use consistent naming conventions
- Keep files focused on a single responsibility

### Testing

- Write tests for new functionality
- Maintain existing test coverage
- Run tests before committing: `npm test` (when configured)

## AI Assistant Guidelines

### When Working on This Repository

1. **Read Before Modifying:** Always read existing files before making changes
2. **Minimal Changes:** Make only the changes necessary to complete the task
3. **Preserve Style:** Match the existing code style and conventions
4. **Test Changes:** Run tests and verify changes work correctly
5. **Clear Commits:** Use descriptive commit messages

### Common Tasks

**Adding New Features:**
1. Understand the existing codebase structure
2. Plan the implementation
3. Write the code following project conventions
4. Add appropriate tests
5. Update documentation if needed

**Fixing Bugs:**
1. Reproduce and understand the issue
2. Identify the root cause
3. Implement the fix
4. Add regression tests
5. Verify the fix doesn't break other functionality

**Refactoring:**
1. Ensure tests exist for affected code
2. Make incremental changes
3. Run tests after each change
4. Preserve external behavior

### What to Avoid

- Don't over-engineer solutions
- Don't add unnecessary dependencies
- Don't create files unless absolutely necessary
- Don't modify unrelated code
- Don't skip reading existing files before editing

## Build and Deploy

*(Update this section when build/deploy processes are configured)*

### Scripts

```bash
# Development (example)
npm run dev

# Build (example)
npm run build

# Test (example)
npm test

# Lint (example)
npm run lint
```

### Environment Variables

*(Document required environment variables here when applicable)*

```bash
# Example:
# DATABASE_URL=postgresql://localhost:5432/mydb
# API_KEY=your-api-key
```

## Dependencies

*(Update this section when dependencies are added)*

### Production Dependencies

- None yet

### Development Dependencies

- None yet

## Troubleshooting

### Common Issues

*(Document common issues and solutions as they arise)*

**Issue:** [Description]
**Solution:** [Steps to resolve]

## Resources

- Project Documentation: [Link when available]
- Issue Tracker: [Link when available]
- Team Wiki: [Link when available]

---

## Maintenance Notes

**Last Updated:** 2026-01-27
**Updated By:** Claude AI Assistant

This file should be updated whenever:
- Project structure changes significantly
- New development workflows are established
- Important conventions are added or modified
- Build/deploy processes change
