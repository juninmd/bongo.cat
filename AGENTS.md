```markdown
# AGENTS.md File Guidelines

These guidelines are designed to ensure the quality, maintainability, and efficiency of all AGENTS.md files within this repository. Adherence to these principles is crucial for fostering a robust and scalable codebase.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a clearly defined, single responsibility. Avoid creating multiple agents with similar functionality.
*   **Abstraction:**  Implement common patterns and abstractions. Document these clearly.
*   **Code Reuse:**  Design agents to be reusable across different projects and scenarios, leveraging existing components where appropriate.
*   **Standard Library Usage:**  Utilize the standard library whenever feasible and appropriate for the agent's functionality.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:**  Strive for the shortest code paths possible while maintaining functionality.
*   **Readability:**  Code should be easily understood by others (and your future self). Use descriptive variable and function names.
*   **Avoid Complexity:**  Don't over-engineer solutions.  Prioritize clarity over unnecessary complexity.
*   **Consistent Formatting:**  Follow a consistent code style (e.g., PEP 8 – for Python) throughout the project.

## 3. SOLID Principles

*   **Single Responsibility:** (As mentioned above - apply this to all agents)
*   **Open/Closed Principle:** Design agents to be extensible through well-defined interfaces and public APIs.  Avoid modifying the core logic directly.
*   **Liskov Substitution Principle:**  Ensure that derived classes can be substituted for their base classes without altering the program's behavior.
*   **Interface Segregation Principle:** Each interface should define only the functionalities that are necessary for interaction.
*   **Dependency Inversion Principle:**  High-level modules (agents) should not depend on low-level modules.  They should depend on abstractions.

## 4. YAGNI (You Aren't Gonna Need It)

*   **Avoid Unnecessary Code:**  Don't write code that you anticipate will never be used.
*   **Focus on Functionality:**  Prioritize implementing the *essential* functionality. Don't add features simply because they *might* be useful in the future.
*   **Refactoring:** Refactor existing code to improve its structure and remove dead code.

## 5. Code Generation & Structure

*   **File Size Limit:**  Each file must not exceed 180 lines of code.
*   **Commenting:**  Each function/class should have a concise docstring explaining its purpose, parameters, and return value. Comments should clarify *why* not *what*.
*   **Naming Conventions:**  Use consistent naming conventions (e.g., snake_case for variables and functions).
*   **Code Organization:**  Organize code logically and consistently. Use appropriate grouping and separation of concerns.
*   **Error Handling:** Implement basic error handling where necessary.
*   **Data Structures:** Choose appropriate data structures for the agent's tasks.

## 6. Testing & Coverage

*   **Unit Tests:**  All agent functions/classes should have a comprehensive suite of unit tests.
*   **Test Coverage:** Aim for at least 80% test coverage.  Use a coverage tool (e.g., Coverage.py, Jest) to verify.
*   **Test-Driven Development:**  Write tests *before* writing code.

## 7. Development Workflow

*   **Pull Requests:**  All changes should be submitted as pull requests.
*   **Code Reviews:**  All code should be reviewed by at least one other team member before merging.
*   **Version Control:**  Use Git for version control.
*   **Documentation:** Document the reasoning behind design decisions.

## 8.  Specific Considerations - AGENTS.md

*   **Configuration:**  Configuration should be managed through separate configuration files (e.g., JSON, YAML).
*   **Versioning:**  Use versioning to track changes to the codebase.
*   **Dependencies:** Clearly define and manage dependencies.
*   **Logging:** Implement basic logging.


This document is intended to be a living guide and will be reviewed and updated periodically.  Any significant changes to these guidelines should be discussed and approved by the team lead.
```