## Branching Strategy

- **main**: Always deployable, protected.
- **develop**: Daily integration; merges only from `feature/*` via PR.
- **feature/<name>**: New features or tasks; branched off `develop`; merged back via PR.
