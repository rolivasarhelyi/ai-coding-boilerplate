# AI Project Context Boilerplate

A reusable project context system for AI-assisted software development.

This boilerplate provides a consistent structure for documenting project goals, requirements, coding standards, and feature specifications. It is designed to help AI coding assistants maintain context across development sessions and generate higher-quality, more consistent code.

## Purpose

The goal of this boilerplate is to:

* Provide a standardized project context structure
* Reduce repetitive prompting and explanations
* Keep project requirements organized
* Improve AI understanding of the project
* Create a repeatable workflow for new projects

## Structure

```txt
.claude/
└── skills/

context/
├── project-overview.md
├── coding-standards.md
├── ai-interaction.md
├── current-feature.md
└── features/
    └── feature-template.md

CLAUDE.md
```

## How to Use

### 1. Create a New Project

Start a new repository using this boilerplate.

### 2. Define the Project

Update `context/project-overview.md` with information about the project, goals, users, and technical approach.

### 3. Create Feature Specifications

Use `context/features/feature-template.md` as the starting point for documenting new features.

Create one file per feature inside the `features` directory.

### 4. Track Active Work

Update `context/current-feature.md` to reflect the feature currently being implemented.

### 5. Develop with AI Assistance

When working with an AI coding assistant, instruct it to review the project context files before making changes or implementing features.

### 6. Maintain Documentation

Keep project documentation and feature specifications updated as requirements evolve.

## Recommended Workflow

1. Define the project.
2. Create a feature specification.
3. Set the active feature.
4. Implement the feature.
5. Review and update documentation.
6. Repeat for the next feature.

## License

Use, modify, and adapt this boilerplate as needed for your own projects.
