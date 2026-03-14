# NMA Dose-Response Studio v2.0.1

**Browser-based network meta-analysis and dose-response modeling platform.**

## Quick Start
1. Open `index.html` in Chrome, Firefox, Safari, or Edge
2. Load a demo dataset or enter your own data
3. Select analysis method and click Run

No installation required.

## Features
- **Network meta-analysis** (SUCRA, P-scores, node-splitting, consistency)
- **Dose-response modeling** (linear, Emax, sigmoid, splines, fractional polynomials)
- **5 tau-squared estimators** (DL, REML, PM, SJ, EB)
- **HKSJ adjustment** for small-sample CIs
- **8+ publication bias methods** (Egger, trim-and-fill, PET-PEESE, Copas, selection models)
- **Diagnostic test accuracy** (bivariate GLMM, HSROC)
- **Seeded PRNG** (xoshiro128**) for reproducibility
- **Export**: CSV, PNG, LaTeX, DOCX, PDF, BibTeX

## Validation
79/79 tests PASS against R metafor, netmeta, and dosresmeta.

## Citation
> Ahmad M, et al. NMA Dose-Response Studio v2.0.1. *F1000Research*. 2026. [DOI pending]

## License
MIT
