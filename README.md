# ACE Guides & Artifacts

A curated collection of battle-tested, customer-facing guides created by Snowflake Account Engineers. These guides distill real-world implementation experience into reusable resources that any AE can share with customers.

## Repository Structure

```
general_guides/
├── DAMA/                        # Data management (DAMA framework) on Snowflake
├── Networking_and_Security/     # Private connectivity (AWS PrivateLink, Azure Private Link)
└── RBAC/                        # Role-Based Access Control (EN, PT-BR, ES)
```

Guides are organized by high-level subject area. Each subfolder contains one or more guides in Markdown (`.md`) or Jupyter Notebook (`.ipynb`) format.

## Available Guides

| Subject | Guide | Format |
|---------|-------|--------|
| DAMA | Data Management on Snowflake | Markdown |
| Networking & Security | AWS PrivateLink Setup | Notebook |
| Networking & Security | Azure Private Link Setup | Notebook |
| RBAC | Role-Based Access Control | Markdown (EN, PT-BR, ES) |

## Contributing

All contributions are welcome. To add a new guide, place it in the appropriate subfolder under `general_guides/` (or create a new subfolder for a new topic area).

### Guide Standards

A guide in this repo must meet the following criteria:

1. **Battle-tested** — Validated with at least one customer engagement.
2. **Generalized** — Free of customer-specific details; usable by any account team.
3. **Narrative & sequential** — Walks the reader through the process step by step.
4. **Grounded in best practices** — Aligned with the Snowflake Well-Architected Framework.
5. **Self-contained** — If external setup is required (cloud provider config, third-party tools), the guide covers those steps as well.
6. **Well-commented** — Objects, parameters, and decisions are explained in enough detail that a customer can complete the task without additional support.
