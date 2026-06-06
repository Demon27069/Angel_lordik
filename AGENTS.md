# AI Agent Instructions for Angel_lordik

## Project Overview

Angel_lordik is a newly initialized project. This document establishes conventions and guidance for AI agents working in this repository.

## Getting Started

### Development Environment

- **Container**: Dev container based on universal Microsoft image (`mcr.microsoft.com/devcontainers/universal:2`)
- **Location**: Work from `/workspaces/Angel_lordik` root directory
- **Status**: Fresh project - initial setup and architecture phase

### Before Starting Work

1. **Understand the project goal**: Ask for clarification on the project's purpose, target technology stack, and primary use cases
2. **Check existing patterns**: Look for configuration files, package managers (package.json, pyproject.toml, etc.), and build scripts before proposing tech stack changes
3. **Preserve history**: When modifying existing files, maintain meaningful git history with clear commit messages

## Development Conventions

### File Organization

- Keep project structure minimal and logical during initial setup
- Use clear, descriptive names for directories and files
- Document the purpose of new directories in this file as the project grows

### Git Workflow

- Create feature branches for significant changes
- Write descriptive commit messages that explain the "why" not just the "what"
- Use pull requests for code review before merging to main

### Documentation

- Keep `AGENTS.md` updated as the project structure and conventions evolve
- Create `README.md` with project overview, setup instructions, and running instructions
- Link to detailed documentation rather than duplicating content in this file

## Common Tasks

### Setting Up a New Feature

1. Create a descriptive branch name: `feature/short-description`
2. Implement the feature following established patterns
3. Add tests if the project has a test suite
4. Update relevant documentation
5. Create a pull request with context about the changes

### Debugging Issues

- Check this file for project-specific gotchas or known issues
- Review recent commits to understand recent changes
- Use provided error messages to search for solutions in documentation
- Ask for clarification on project-specific setup if something seems broken

## Technology Stack

> To be determined based on project requirements

When proposing technologies, prefer:
- Well-documented tools with active communities
- Solutions that match the project's scope and team expertise
- Minimal external dependencies during initial setup

## Next Steps

1. **Define project purpose**: Clarify the main goals and scope of Angel_lordik
2. **Choose technology stack**: Decide on primary language(s), frameworks, and tools
3. **Create README.md**: Add comprehensive setup and usage instructions
4. **Initialize project structure**: Set up directories, configuration files, and initial code
5. **Establish testing strategy**: Plan for test coverage and CI/CD as needed

## Notes for AI Agents

- This is an active project in development - conventions may change
- Always ask for confirmation before making significant architectural decisions
- Link to existing documentation rather than creating redundant content
- Keep this file as the source of truth for project conventions
- If you encounter unclear or contradictory information, flag it for clarification
