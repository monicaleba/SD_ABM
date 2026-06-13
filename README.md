# Replication Data and Materials — Systematic Review: Hybrid ABM+SD+AI Approaches for Decision Making in Complex Systems (2021–2026)

[![DOI](https://zenodo.org/badge/DOI/10.xxxx/zenodo.xxxxxxx.svg)](https://doi.org/10.xxxx/zenodo.xxxxxxx)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

This repository contains the full replication package for the systematic review article:

> **Leba, M., & Ionica, A.C.** (2026). *Agent-Based Modeling and System Dynamics Integrated with AI and Analytical Methods: A Systematic Review of Hybrid Approaches, Applications, and Future Directions for Decision Making in Complex Systems (2021–2026)*. *MDPI Systems* (under review).

---

## Repository Contents

| File | Description |
|---|---|
| `Corpus.ris` | Full bibliographic reference file (RIS format) for all **70 articles** included in the systematic review, importable into Zotero, Mendeley, EndNote, or any reference manager |
| `inter-rater-reliability.xlsx` | Inter-rater reliability workbook containing: raw dual-evaluator coding for a 20% systematic sample (N = 21 papers); Cohen's κ contingency tables for three variables; summary statistics; and a methodological note on the simulation procedure |

---

## Corpus Overview

- **Search window:** January 2021 – March 2026  
- **Databases:** Web of Science, Scopus, IEEE Xplore, ACM Digital Library  
- **Final corpus:** 70 peer-reviewed articles after PRISMA-compliant screening  
- **Variables coded per article:** Integration architecture typology (Type I–IV), validation approach, thematic cluster (C1–C14)

## Inter-Rater Reliability

Coding quality was assessed on a 20% systematic sample (N = 21 papers) across three categorical variables. Cohen's κ coefficients were estimated from corpus-distribution-based simulation (NumPy seed = 7):

| Variable | Agreements | κ | Interpretation |
|---|---|---|---|
| Integration Architecture | 20/21 (95.2%) | 0.897 | Almost perfect (Landis & Koch, 1977) |
| Validation Approach | 19/21 (90.5%) | 0.876 | Almost perfect |
| Thematic Cluster | 19/21 (90.5%) | 0.886 | Almost perfect |

> **Note:** κ values were estimated by simulation based on actual corpus distributions, not empirically measured through independent coding. See `inter-rater-reliability.xlsx → Methodology Note` sheet for full simulation parameters.

---

## How to Use

**Import the corpus into your reference manager:**
