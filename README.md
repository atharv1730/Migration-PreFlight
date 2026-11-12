# Migration PreFlight

A PostgreSQL migration safety checker that identifies risky database changes before they are merged or deployed.


## Status
Early Development


## Goals

- Analyze PostgreSQL migration SQL for common safety risks.
- Explain why a change may be risky.
- Recommend safer rollout patterns.
- Eventually report findings on GitHub pull requests.