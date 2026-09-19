# HCAToolkit

HCAToolkit is an umbrella for related creative and technical work centered on making complex information more explicit, organized, and usable. Its projects include structured tools and reusable systems for creative and technical concerns, including deterministic validation. Calculogic is a major system within this broader body of work, not another name for HCAToolkit as a whole.

## From Creative Systems to Software

The work developed through overlapping threads rather than a sequence of projects replacing one another. Long-running character, story, worldbuilding, relationship, ability, and rules documentation established an early practice of externalizing complex creative systems. Psychology and personality research then became increasingly structured, extending into assessments, questions, scoring, reusable logic, and executable prototypes.

H-CAT grew from efforts to make character psychology, narrative history, creative decisions, forms, quizzes, research, and related creator tools more explicit and usable. Its website and community experimentation moved from Wix to WordPress and plugins as the requirements became more complex. When the needed forms, calculations, linked information, and reusable logic no longer fit cleanly within those combinations, Calculogic emerged as generalized reusable tooling. Repository-based work led to the current React implementation, while clearer terminology, architecture, ownership boundaries, and conventions made deterministic validation a distinct concern. The Validator subsequently grew into a modular suite and was extracted for independent ownership and reuse.

## Current Projects

### [Calculogic React App](https://github.com/HCAToolkit/Calculogic_React_App)

The current React, TypeScript, and Vite implementation of Calculogic. It is the application host in which the Validator originally developed and now serves as a consumer and integration environment for the standalone Validator.

### [Calculogic Validator](https://github.com/HCAToolkit/calculogic-validator)

The standalone repository is the current authoritative source for the Calculogic Validator: a modular validation suite that grew from the need to make Calculogic's written conventions deterministic and inspectable. Its extraction gives the Validator independent ownership and enables reuse by consumers such as the React app.

Each project repository owns its implementation details, installation guidance, architecture, workflows, contracts, specifications, and detailed history. This profile provides organization-level context and routes readers to the current project documentation.
