# HANDOVER.md — TARGENET

## Current Status
- **Phase:** 0 (Repository & Handover Setup) — COMPLETE
- **Last completed substep:** 0.7 (first commit + push)
- **Next substep:** 1.1 (install libraries)
- **Blockers:** none

## Progress Log
<!-- Format: YYYY-MM-DD | Substep ID | one-line result | commit hash -->
2026-09-13 | P0.1-0.7 | Repo skeleton created, pushed to GitHub main | a841f59
2026-09-13 | P1.1 | Installed rdkit, torch, torch_geometric, chembl_webresource_client, biopython, sklearn, xgboost, mlxtend, umap-learn | fccdf50
2026-09-13 | P1.1 | Installed and pinned rdkit, torch, torch_geometric, chembl_webresource_client, biopython, sklearn, xgboost, mlxtend, umap-learn to configs/requirements.txt | 9f5ba93
2026-09-13 | P1.2-1.3 | Created data/raw, data/clean, eda, models folders; confirmed GPU visibility | d25e17b
2026-09-13 | P1.1 | Fixed torch install to CUDA-enabled build after Runtime>GPU switch; confirmed Tesla T4 visible; re-pinned requirements.txt | cc00883
2026-09-13 | P1.1 | Reinstalled cheminformatics/ML packages lost after GPU runtime restart; requirements.txt now complete | dddb526
2026-09-13 | P1.4 | Recorded ChEMBL release version (ChEMBL_37, 2026-05-01) to configs/chembl_version.json | a691158
2026-09-13 | P1.5-metabolic | Literature validation gate passed for 6 Metabolic-family targets (DPP-4, SGLT-2, PTP1B, GLP-1R, HMG-CoA Reductase, PCSK9), >=3 independent sources each | 6ec83f2
2026-09-13 | P1.5-cardiovascular | Literature validation gate passed for 5 Cardiovascular-family targets (ACE, AT1R, PDE5, COX-2, Renin), >=3 independent sources each; noted COX-2 dual-family status and aliskiren withdrawal caveat | c926ee8
2026-09-13 | P1.5-neurodegenerative | Literature validation gate passed for 5 Neurodegenerative-family targets (AChE, BACE1, GSK-3b, MAO-B, LRRK2), >=3 independent sources each; noted BACE1 trial discontinuation and LRRK2 clinical-validation-pending caveats | 0024da6
2026-09-13 | P1.5-eye | Literature validation gate passed for 3 Eye-family targets (Carbonic Anhydrase II, VEGFR-2, Aldose Reductase), >=3 independent sources each; noted aldose reductase clinical-translation caveat | 0755374
