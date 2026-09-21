# HCAToolkit

HCAToolkit is an umbrella for related creative and technical work centered on making complex information more explicit, organized, and usable. Its projects include structured tools and reusable systems for creative and technical concerns, including deterministic validation. Calculogic is a major system within this broader body of work, not another name for HCAToolkit as a whole.

## From Creative Systems to Software

The work developed through overlapping threads rather than a sequence of projects replacing one another. Long-running character, story, worldbuilding, relationship, ability, and rules documentation established an early practice of externalizing complex creative systems. Psychology and personality research became increasingly structured alongside this work, extending into assessments, questions, scoring, reusable logic, and executable prototypes.

H-CAT grew from efforts to make character psychology, narrative history, creative decisions, forms, quizzes, research, and related creator tools more explicit and usable. Its website and community experimentation moved from Wix to WordPress and plugins as the requirements became more complex. When the needed forms, calculations, linked information, and reusable logic no longer fit cleanly within those combinations, Calculogic emerged as generalized reusable tooling. Repository-based work led to the current React implementation, while clearer terminology, architecture, ownership boundaries, and conventions made deterministic validation a distinct concern. The Validator subsequently grew into a modular suite and was extracted for independent ownership and reuse.

## Current Software Projects

### [Calculogic React App](https://github.com/HCAToolkit/Calculogic_React_App)

The current React, TypeScript, and Vite implementation of Calculogic. It is the application host in which the Validator originally developed and provides a real consumer and integration context for standalone Validator development.

### [Calculogic Validator](https://github.com/HCAToolkit/calculogic-validator)

The standalone repository is the current authoritative source for the Calculogic Validator: a modular validation suite that grew from the need to make Calculogic's written conventions deterministic and inspectable. Its extraction gives the Validator independent ownership and enables reuse by consumers such as the React app.

Each project repository owns its implementation details, installation guidance, architecture, workflows, contracts, specifications, and detailed history. This profile provides organization-level context and routes readers to the current project documentation.

## AI-Assisted Development

AI tools are used throughout HCAToolkit's research, design, writing, development, and review, but direction and decisions remain mine. I establish the vision for each project, explore and evaluate design options, determine priorities, and decide which changes are ultimately accepted.

AI assists with the reasoning behind that work: discussing ideas, examining alternatives, challenging assumptions, developing explanations, and refining technical approaches before anything is built. It also helps write, organize, and revise the living documents that support ongoing work across these projects.

These documents bring together evolving ideas, conceptual models, and research, alongside more developed design notes and specifications. They are not exhaustive change logs. They retain ideas that remain relevant, might become useful later, or are still uncertain; ideas that have been definitively abandoned are removed rather than kept as a historical record.

An idea appearing in a living document is not necessarily an active direction, an approved decision, or an implemented feature.

To help AI agents work in line with that intent, I write instructions that describe my preferred approaches to reasoning, prioritization, and problem-solving before an agent begins work in a given document or repository. These address things like how I weigh return on investment, how I want ideas developed and assessed, and how to avoid unnecessary complexity. The aim is fidelity to my intent and approach, not a fixed sequence of commands to execute.

This guidance exists in layers. Some instructions are shared across all agents, while others are agent-specific, accounting for differences in tools and environments.

Repository-level files address a given project's conventions, architecture, structure, ownership boundaries, and development practices. Following this guidance does not guarantee that an agent's work is correct; it is still reviewed like everything else described here.

Concepts developed this way can inform scoped GitHub issues and implementation tasks. From there, AI agents assist with coding, testing, documentation, and review, and the results are evaluated through pull requests and recorded verification rather than taken on faith.

Different projects don't necessarily follow an identical process. In some cases, multiple AI agents independently review one another's work, identifying problems or proposing corrections. This adds a review opportunity; it does not replace human oversight.

Across all of this, responsibility for what gets accepted, deferred, rejected, or merged remains mine. AI participates in the process; it does not own the outcome.
