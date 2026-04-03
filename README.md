# docs-collab-pilot

Cross-org collaboration repository for the **pilot** project.

## Contents

| Path | Purpose |
|------|---------|
| `bmm.yaml` | Project configuration for BMAD agents |
| `project-context.md` | Project context and scope |
| `research/` | Shared research artifacts |
| `brief/` | Shared brief artifacts |
| `prd/` | Shared PRD artifacts |
| `decisions/` | Shared decision records |

## Setup

1. Use the `eco` CLI to set up the multi-root workspace: `eco workspace setup`
2. Run the BMAD installer to generate IDE integration files (`.windsurf/workflows/`, `.github/agents/`, etc.)
3. Open the generated workspace file in your IDE

Your workspace will look like:

```text
~/workspace/
├── bmad/                  # pca-bmad-runtime
└── docs-collab/
    └── pilot/             # this repo
```

PCA contributors will also have `docs/` in the workspace.

## Source of Truth

This repository is the **canonical source** for shared project artifacts. All shared research, brief, PRD, and decision content is authored here — not in the `docs` nexus.

## Working Rules

- Shared project changes are authored in this repository
- BMAD runtime is accessed via the `pca-bmad-runtime` root in the multi-root workspace
- PCA-only content lives in `docs/projects/pilot/`
