# AEGIS Implementation Repository

**Status:** Repository scaffold only — implementation has not begun.

This repository is separate from the AEGIS architecture/documentation repository at `KingsDux/AEGIS-Adaptive-Environmental-Guard-Intelligence-System-`. The architecture documents remain the source of truth and are not duplicated or modified here.

## Approved constraints represented here

- AEGIS is decision support, not an autonomous clinical or biosecurity authority.
- Consequential actions require human authorization.
- Document 02 owns canonical domain vocabulary and global state semantics.
- Documents 03 and 04 own the authoritative 13-screen registry.
- Document 19 owns implementation sequencing.
- The backend architecture is locked to Python, FastAPI, PostgreSQL, and Redis Streams.

## Repository status

- `backend/` reserves the approved backend boundary; no application code, dependencies, schema, or API contract has been created.
- `frontend/` is intentionally uninitialized because the approved frontend technology stack could not be verified from the documents available in this workspace.
- `infrastructure/` reserves deployment and local-service concerns; no deployment topology or environment configuration has been created.
- `contracts/` is reserved for approved data and API contracts; no contract has been inferred or generated.
- `docs/` contains implementation-repository records only, not copies of the architecture baseline.

The source repository and access status are recorded in `docs/repository-source.md`.

## Implementation gate

Do not begin Phase 1 or add product code until this scaffold is checked against the complete Documents 01–22, especially Documents 08, 15, 16, 18, 19, 21, and 22. The current repository is a scaffold and has no completed Phase 0 audit.
