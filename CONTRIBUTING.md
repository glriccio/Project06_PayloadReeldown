# Contributing to Stratospheric Balloon Payload Reeldown System

Thank you for your interest in contributing to this project! This document provides guidelines for contributing to the repository.

## Table of Contents
- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Workflow](#development-workflow)
- [Coding Standards](#coding-standards)
- [Submitting Changes](#submitting-changes)
- [Reporting Issues](#reporting-issues)

## Code of Conduct

### Our Standards
- Be respectful and inclusive
- Focus on constructive feedback
- Prioritize project goals and team collaboration
- Maintain professional communication

## Getting Started

1. **Fork the repository** (if external contributor)
2. **Clone your fork** or the main repository
   ```bash
   git clone https://github.com/glriccio/Project06_PayloadReeldown.git
   ```
3. **Create a feature branch**
   ```bash
   git checkout -b feature/your-feature-name
   ```

## Development Workflow

### Branch Naming Convention
- `feature/` - New features
- `bugfix/` - Bug fixes
- `hotfix/` - Critical fixes
- `docs/` - Documentation updates
- `test/` - Test additions or modifications

### Commit Message Guidelines
Write clear, descriptive commit messages:
```
[Component] Brief description

Detailed explanation of what changed and why.

- Bullet points for multiple changes
- Reference issues with #issue-number
```

Example:
```
[Firmware] Add motor control initialization

Implemented PWM-based motor control initialization for the reel system.

- Added motor driver configuration
- Implemented safety checks
- Fixes #12
```

## Coding Standards

### General Guidelines
- Write clear, self-documenting code
- Add comments for complex logic
- Follow existing code style in the repository
- Keep functions focused and modular
- Write tests for new functionality when applicable

### Documentation
- Update README.md if you change functionality
- Document all public APIs and interfaces
- Include inline comments for complex algorithms
- Update relevant documentation in the `docs/` folder

## Submitting Changes

### Pull Request Process

1. **Update your branch** with the latest changes from main
   ```bash
   git fetch origin
   git rebase origin/main
   ```

2. **Run tests** (when test infrastructure is available)
   ```bash
   # Run appropriate tests for your changes
   ```

3. **Create a Pull Request**
   - Use a clear, descriptive title
   - Fill out the PR template
   - Link related issues
   - Describe what changed and why
   - Include testing details

4. **Code Review**
   - Address reviewer feedback
   - Keep discussions focused and professional
   - Update PR as needed

5. **Merge**
   - PRs require approval before merging
   - Use "Squash and Merge" for feature branches
   - Delete branch after merging

## Reporting Issues

### Bug Reports
When reporting bugs, include:
- Clear, descriptive title
- Steps to reproduce
- Expected behavior
- Actual behavior
- Environment details (OS, hardware, versions)
- Screenshots or logs if applicable

### Feature Requests
When requesting features, include:
- Clear description of the feature
- Use case and motivation
- Proposed implementation (if applicable)
- Alternative solutions considered

### Issue Labels
- `bug` - Something isn't working
- `enhancement` - New feature or request
- `documentation` - Documentation improvements
- `question` - Questions about the project
- `help wanted` - Extra attention needed
- `good first issue` - Good for newcomers

## Project-Specific Guidelines

### Hardware Changes
- Document all hardware modifications in `hardware/` directory
- Include schematics and bill of materials
- Test thoroughly before committing

### Firmware Changes
- Follow embedded systems best practices
- Consider memory and processing constraints
- Document pin assignments and hardware dependencies

### Safety-Critical Code
- Extra review required for safety-critical components
- Comprehensive testing mandatory
- Document failure modes and safety mechanisms

## Questions?

If you have questions about contributing, please:
1. Check existing documentation
2. Search existing issues
3. Open a new issue with the `question` label

Thank you for contributing to the Stratospheric Balloon Payload Reeldown System!
