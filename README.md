# Razor Sharp Changes

> A software modification policy


The art of writing software is the art of making coherent incremental changes. This policy outlines guidelines to optimize the development process and ensure the correctness, clarity, and maintainability of the software.

## 1. Each commit represents a single, focused change showing progress

Make commits for well-defined modifications. A well-defined commit captures a single logical change or feature enhancement that demonstrates obvious progress. Each commit should encapsulate a cohesive unit of work, making it easier to understand and manage changes.

To determine if a change meets the criteria, ensure the purpose of the change is clear and specific. Ask yourself, "Does this change have a clear objective and contribute to the overall progress of the project?"

By strictly following this rule, developers ensure that each commit represents a well-defined change that demonstrates clear progress in the development process. This promotes clarity and enables easier tracking of changes within the codebase.

## 2. Avoid combining unrelated changes in a single commit

Refrain from including unrelated modifications in a single commit. Each commit should focus on a specific change or feature.

By keeping each commit focused on a single change, developers can maintain clarity and organization in their development process. It allows for better understanding of the purpose and impact of each modification, making it easier to manage and reason about the changes made.

Separating unrelated changes into distinct commits enhances the developer's workflow by simplifying the tracking of changes and enabling efficient reverting or rolling back of modifications when needed. It promotes a more effective and streamlined development process.

## 3. Refactor must be prioritized if it would simplify a desired change

While working on a change, if you identify a possible refactoring that would simplify the desired change, prioritize the refactoring. Put aside your current work, make the refactor, and then return to the previous work, which would now be simpler due to the completed refactor. This approach streamlines the development process and makes the desired change easier to reason about.

By prioritizing refactoring when it simplifies a desired change, developers ensure that the codebase remains clean, maintainable, and optimized for the desired modifications. This reduces technical debt and enhances the overall quality of the software.

## Conclusion 

By adhering to these rules, developers can achieve razor sharp changes, where each commit represents a focused and meaningful modification. This policy promotes clarity and correctness in your codebase.

May your changes be razor sharp.
