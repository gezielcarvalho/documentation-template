# Project documentation

This folder records the durable context that should survive a sprint, issue, or
person changing teams. GitHub Issues and Projects track live work; these files
explain why the work exists and how it is delivered.

## Use the smallest appropriate set

- **Maintained showcase, demo, cohort, or platform:** use every core document.
- **Learning archive:** keep only this file, explaining purpose, status, and a
  successor link when one exists.
- **Migration hold:** add `MIGRATION.md`, architecture/dependency notes, and a
  risk log instead of expanding product scope.

Keep each document concise. Link to issues, pull requests, diagrams, and
external records rather than duplicating them.

## Core documents

| File | Purpose |
| --- | --- |
| `charter.md` | Purpose, stakeholders, success criteria, and constraints |
| `scope-and-roadmap.md` | Scope boundary, milestones, dependencies, and active direction |
| `architecture.md` | Context, components, data, integrations, and technical constraints |
| `delivery-and-quality.md` | Agile working agreement, quality checks, release approach, and Definition of Done |
| `operations.md` | Optional operating posture, ownership, runbook, and release boundary |
| `risks-and-decisions.md` | Assumptions, risks, mitigations, and decision log |
| `adr/` | Short records for decisions that require lasting technical rationale |
