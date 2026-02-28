```markdown
# AGENTS.md - Guidelines for AI Coding Agents

These guidelines outline the principles and rules for development of AI coding agents within this repository. Adherence to these principles is critical for creating robust, maintainable, and scalable code.

## 1. DRY (Don't Repeat Yourself)

*   Every function, class, and module should have a single, well-defined purpose.
*   Avoid duplicating code across multiple files.
*   Refactor code to eliminate redundancies.

## 2. KISS (Keep It Simple, Stupid)

*   Strive for maximum clarity and readability in code.
*   Favor simpler solutions over complex ones whenever possible.
*   Minimize code length without sacrificing functionality.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class or module should have one, and only one, reason to change.
*   **Open/Closed Principle:**  The system should be extensible without modification.  New functionality should be added through new classes/modules, not by modifying existing code.
*   **Liskov Substitution Principle:**  Subclasses should be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:** Client code should not depend on implementation details of classes.

## 4. YAGNI (You Aren't Gonna Need It)

*   Implement only the functionality absolutely necessary for the current task.
*   Avoid introducing unnecessary complexity or features.
*   Prioritize functionality over optimization.

## 5. Code Structure & Organization

*   **File Size:** Each file should ideally be no more than 180 lines of code.  Short files are easier to understand and maintain.
*   **Naming Conventions:**  Use consistent and descriptive naming conventions. Modules should be prefixed with 'module_'. Classes/functions should be prefixed with 'agent_'.
*   **Comments:**  Add comments where appropriate to explain complex logic, assumptions, or design decisions, but avoid excessive commenting.  Comments should focus on *why* not *what*.
*   **Modular Design:** Break down the agent into smaller, reusable components.
*   **Data Structures:** Utilize appropriate data structures for efficient data management.  Consider using dictionaries, lists, or sets as appropriate.
*   **Error Handling:** Implement robust error handling to prevent crashes and provide informative error messages.

## 6. Testability & Mocking

*   All development MUST be productive.  Testing is a critical part of the development workflow.
*   **Mocking:**  Utilize mocks and stubs extensively for unit testing.  Do not use real data or external systems.
*   **Automated Tests:**  Create comprehensive automated tests to cover all critical functionalities.
*   **Test Coverage:** Aim for at least 80% test coverage.  Utilize coverage tools to track progress.

## 7. Production-Ready Code

*   **Code Style:** Follow a consistent coding style and linting rules.  Use a linter to enforce style.
*   **Readability:** Prioritize code that is easy to read and understand.
*   **Documentation:**  Document the code thoroughly, including API documentation and explanations of key design decisions.
*   **Versioning:**  Utilize version control (e.g., Git) to track changes and facilitate collaboration.
*   **Deployment:**  Consider the potential for future deployment and scalability when designing the agent.

## 8. Specific Considerations for AI Agents

*   **State Management:** Implement a well-defined state management strategy to maintain agent context.
*   **Reasoning Engine:** Design a modular and extensible reasoning engine that supports different types of reasoning.
*   **Input/Output Handling:**  Create a clear interface for handling input and output data.
*   **Error Handling & Recovery:**  Implement robust error handling and recovery mechanisms.

## 9.  Documentation & API Definition

*   **API Documentation:**  Provide clear and concise API documentation for all agents and functions.
*   **Example Usage:** Include example usage code to illustrate how to use the agents.

## 10.  Continuous Improvement

*   Regularly review and update the code and documentation.
*   Refactor code to improve its quality and maintainability.

These guidelines are intended as a starting point.  Specific details will vary depending on the individual agent's purpose.
```