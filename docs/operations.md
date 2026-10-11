# Operations and runbooks

Use this document when a repository has a demo environment, deployment path,
scheduled process, support responsibility, or retained operational artifacts.
For a learning archive with no operating surface, state that explicitly and keep
this file short.

## Current operational posture

- Approved environments: <!-- local, demo, staging, production, or none -->
- Business owner:
- Technical / operations owner:
- Support or escalation route:

## Supported operations

| Operation | Approved method | Owner | Evidence / runbook |
| --- | --- | --- | --- |
| Local development | | | |
| Demo or staging deployment | | | |
| Production deployment | | | |
| Backup / restore | | | |
| Incident response | | | |

## Operational controls

- Secrets are stored in an approved secret manager; never document their values.
- Monitoring, logs, health checks, and alerts are known for every approved environment.
- Backup and restoration ownership are confirmed before data-bearing deployment.
- Each release has an authorized owner, validation evidence, and rollback path.

## Historical or unapproved material

<!-- Identify legacy scripts, deployment notes, or examples and state clearly
whether they may be used. Do not let historical material become implicit
production guidance. -->

## Before a new deployment

- [ ] Confirm environment and budget ownership.
- [ ] Review security, data classification, secrets, and access controls.
- [ ] Validate health checks, monitoring, backups, restore, and rollback.
- [ ] Record release approval and post-deployment validation in the delivery issue.
