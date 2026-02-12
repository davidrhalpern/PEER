# ADR-0001: Repository governance

## Decision
The PEER repository will enforce a protected `main` branch and require pull requests for all changes, including for administrators.

## Rationale
PEER is fundamentally about traceability, accountability, and disciplined change control. The repository should embody those values from the beginning.

## Consequences
- All changes have a reviewable proposal (PR) and an audit trail.
- Automation and checks can be added over time without changing the core workflow.
