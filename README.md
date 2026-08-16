# Experts in CMT: CMT Gene Browser Dataset

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.21970233.svg)](https://doi.org/10.5281/zenodo.21970233)

A curated, gene-resolved dataset of the genes and subtypes associated with Charcot-Marie-Tooth disease (CMT) and related inherited neuropathies. It is the data behind the [CMT Gene Browser](https://expertsincmt.org/genetics/cmt-gene-browser/) at [expertsincmt.org](https://expertsincmt.org).

**Version 1.0.3** &middot; Build date 2026-08-16 &middot; Licensed [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)

## What this is

Each record resolves a gene to its associated CMT subtype(s), with curated nomenclature, classifications, and links to authoritative external resources. The dataset is intended as an educational and reference resource. It is not medical advice, variant interpretation, or diagnostic guidance.

- **159 genes**
- **188 subtype rows** (one row per gene-subtype association)
- **19 candidate gene associations** (genes under evaluation, not yet confirmed subtypes)

## Contents

| File | Description |
|---|---|
| `eic-cmt-genes-v1.0.3.json` | Gene-resolved dataset (genes with nested subtypes) plus a provenance and license manifest. |
| `eic-cmt-genes-v1.0.3.csv` | Subtype-level table (one row per subtype; gene fields repeat). |
| `LICENSE.txt` | Full license terms, attribution, source citations, and disclaimer. |
| `README.txt` | Packaged dataset readme (ships inside the distributable). |
| `CHANGELOG.md` | Version history. |

## Fields

Gene nomenclature and aliases, locus, inheritance mode(s), classifications, ClinGen gene-disease validity (CMT GCEP) and dosage sensitivity, Genomics England PanelApp 846 ratings, curated gene function summaries, external record links, discovery attribution, and nested subtype detail.

## License

The Experts in CMT curation, compilation, selection, arrangement, classifications, and original descriptive text are licensed under a **Creative Commons Attribution 4.0 International License (CC BY 4.0)**. You are free to share and adapt the material for any purpose, including commercially, so long as you give appropriate credit, link to the license, and indicate changes.

This dataset references and links to content owned by third parties (gene nomenclature, variant records, curated classifications, population frequency data, reference sequences, protein annotations, panel identifiers, discovery attributions, and cited literature). All such content remains the property of its respective owner under that owner's terms. No rights in third-party content are granted by Experts in CMT. Anyone reusing this dataset is responsible for complying with the terms governing any third-party content it contains. See `LICENSE.txt` for the complete terms and the full source citations.

## How to cite

> Experts in CMT. (2026). *Experts in CMT: CMT Gene Browser* (Version 1.0.3) [Data set]. Zenodo. https://doi.org/10.5281/zenodo.21970234

- **Concept DOI** (always resolves to the latest version): [10.5281/zenodo.21970233](https://doi.org/10.5281/zenodo.21970233)
- **Version DOI** (this release, 1.0.3): [10.5281/zenodo.21970234](https://doi.org/10.5281/zenodo.21970234)

## Sources

Records reference HGNC, Ensembl, MANE, UniProt, ClinVar, ClinGen, MONDO, gnomAD, OMIM, Genomics England PanelApp, and the Genesis Project Foundation. All source data in this release was obtained on 2026-08-02. Each source remains subject to its own terms of use and is cited in full in `LICENSE.txt`.

## Disclaimer

The dataset is offered as-is and as-available, without warranties of any kind. It is provided for informational and educational purposes and is not medical advice, and it is not a substitute for evaluation by a qualified healthcare provider. Genetic testing, diagnosis, and healthcare decisions should always be made in consultation with a qualified healthcare professional.

---

&copy; 2026 Experts in CMT. expertsincmt.org is a website of Experts in CMT.
