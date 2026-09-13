# TARGENET

Computational drug repurposing pipeline: screening ~2,000–2,500 FDA-approved
drugs against a 21-target panel (5 age-related disease families) using a
GraphDTA-style GNN trained on ChEMBL binding data.

## Resume in a fresh Colab session
1. Mount Drive: `from google.colab import drive; drive.mount('/content/drive')`
2. `cd /content/drive/MyDrive/targenet`
3. Check `HANDOVER.md` → "Current Status" for where the project left off
4. Check `MANIFEST.md` for large-artifact paths/checksums on Drive
5. Re-auth git via Colab secret `GITHUB_TOKEN` (see Phase 0.2 in roadmap)
6. Continue at the next unchecked substep in `roadmap_v3.md`

## Structure
- `notebooks/` — Colab notebooks, one per phase or substep cluster
- `scripts/` — reusable Python modules
- `results/` — small results (CSVs, tables)
- `figures/` — plots
- `configs/` — pinned versions, hyperparameters
- `HANDOVER.md` — progress log + current status
- `LITERATURE.md` — reference list (Ref-1 through Ref-13)
- `MANIFEST.md` — large-artifact tracking (path, size, SHA256, description)
