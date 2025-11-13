<!--
Sync Impact Report:
Version change: N/A → 1.0.0
List of modified principles:
- Principle 1: N/A → Write tests first (TDD approach)
- Principle 2: N/A → Use Python 3.12+ with type hints everywhere
- Principle 3: N/A → Keep code clean and easy to read
- Principle 4: N/A → Document important decisions with ADRs
- Principle 5: N/A → Follow essential OOP principles: SOLID, DRY, KISS
Added sections:
- Technical Stack
- Quality Requirements
Removed sections: N/A
Templates requiring updates:
- .specify/templates/plan-template.md: ⚠ pending
- .specify/templates/spec-template.md: ⚠ pending
- .specify/templates/tasks-template.md: ⚠ pending
- .specify/templates/commands/*.md: ⚠ pending
- README.md: ⚠ pending
Follow-up TODOs:
- TODO(RATIFICATION_DATE): Please provide the original adoption date for this constitution.
-->
# calculator Constitution

## Core Principles

### I. Write tests first (TDD approach)
All new features and bug fixes must be developed using a Test-Driven Development (TDD) approach. Tests are written and approved before implementation begins, following a Red-Green-Refactor cycle.

### II. Use Python 3.12+ with type hints everywhere
All Python code must adhere to Python 3.12 or newer. Type hints are mandatory for all function signatures, variable declarations, and class attributes to ensure code clarity and maintainability.

### III. Keep code clean and easy to read
Code must be self-documenting, follow established style guides (e.g., PEP 8), and prioritize readability. Complex logic should be broken down into smaller, manageable units.

### IV. Document important decisions with ADRs
Architectural and significant design decisions must be documented using Architectural Decision Records (ADRs) to capture context, options considered, and rationale.

### V. Follow essential OOP principles: SOLID, DRY, KISS
Object-Oriented Programming (OOP) principles such as SOLID (Single Responsibility, Open/Closed, Liskov Substitution, Interface Segregation, Dependency Inversion), DRY (Don't Repeat Yourself), and KISS (Keep It Simple, Stupid) must be applied to ensure robust, maintainable, and scalable code.

## Technical Stack

- Python 3.12+ with UV package manager
- pytest for testing
- Keep all project files in git

## Quality Requirements

- All tests must pass
- At least 80% code coverage
- Use dataclasses for data structures

## Governance

This constitution supersedes all other project practices. Amendments require a formal proposal, review by core contributors, and a majority approval. Versioning follows semantic versioning rules. Compliance reviews will be conducted quarterly.

**Version**: 1.0.0 | **Ratified**: TODO(RATIFICATION_DATE): Please provide the original adoption date for this constitution. | **Last Amended**: 2025-11-13