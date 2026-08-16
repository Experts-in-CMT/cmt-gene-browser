# Changelog

All notable changes to the Experts in CMT CMT Gene Browser dataset are documented in this file. Each release corresponds to a tagged Git release and, where minted, a versioned DOI.

The format is loosely based on [Keep a Changelog](https://keepachangelog.com/), and the dataset uses a `MAJOR.MINOR.PATCH` version scheme.

## [1.0.3] - 2026-08-16

Initial public release. Baseline production cut of the gene-resolved CMT dataset.

- 159 genes, 188 subtype rows, including 19 candidate gene associations.
- Gene-resolved JSON (genes with nested subtypes) and a subtype-level CSV.
- Curated fields: nomenclature and aliases, locus, inheritance, classifications, ClinGen gene-disease validity (CMT GCEP) and dosage sensitivity, PanelApp 846 ratings, gene function summaries, discovery attribution, and external record links.
- External record links limited to licensed, redistributable sources (for example gnomAD as a derived link). Display-only links that are not licensed for redistribution are intentionally excluded from the dataset.
- Licensed CC BY 4.0 for Experts in CMT curation; third-party content remains under its respective terms (see `LICENSE.txt`).
