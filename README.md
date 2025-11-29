# Project Template

This repository is a general-purpose project template.

## 1. Folder Structure (Non-Meta Repository)

```
/guidelines/          # Policies, guidelines, and governance rules
/modules/            # References to a repo (or their meta) repositories
/content/             # Centralised content (CAS), assets and resources
/docs/architecture/design/ # ADRs (Architecture Decision Records)
/docs/technical/specs/     # TSDs (Technical Specification Documents)
/ci/                  # CI/CD pipelines, policies, templates
```
**Note:** The `/docs` directory is reserved for non-meta (i.e., project) repositories only.

## 2. Naming and Storage Conventions

| Type | Storage Location (Meta Repo) | File Name          | Title In-File      |
| ---- | ---------------------------- | ------------------ | ------------------ |
| ADR  | `/architecture/design/`      | `adr-000-title.md` | `ADR-000: Title`   |
| GDR  | `/guidelines/decisions/`               | `gdr-000-title.md` | `GDR-000: Title`   |
| TSD  | `/technical/specs/`          | `tsd-000-title.md` | `TSD-000: Title`   |

## Separation of Concerns

- **GDRs**: Governance, policies, and organizational rules.
- **ADRs**: High-level, deterministic architectural decisions (e.g., DAG/CD rules).
- **TSDs**: Mutable, implementation-level technical specifications.
