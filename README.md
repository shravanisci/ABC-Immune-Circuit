# ABC: A Transcriptome-Gated Anti-inflammatory Immune Circuit

## Overview
Inflammatory diseases span autoimmune disorders, infections, cancer, and sepsis. However, current anti-inflammatory therapies are often applied uniformly without accounting for patient-specific immune states.

This project proposes **ABC**, a transcriptome-gated synthetic immune circuit that activates an anti-inflammatory response **only when a specific inflammatory context is detected**.

ABC integrates:
- Boolean logic for immune-state sensing
- Human transcriptomic data
- Stochastic simulation of downstream IL-10 dynamics

---

## Core Idea
The ABC circuit activates IL-10 only when:
- TNF is high  
- IL-6 is high  
- IFN-γ is low  

This logic is designed to detect unresolved inflammatory states while avoiding blanket immunosuppression.

---

## Datasets Used
| Disease Context | GEO Accession |
|----------------|--------------|
| Inflammatory bowel disease | GSE100833 |
| COVID-19 | GSE157103 |
| Sepsis | GSE65682 |

---

## Key Findings
- ABC activation is rare (<1% of samples), indicating high specificity
- Activation is context-dependent rather than disease-wide
- Stochastic simulations show robust IL-10 induction once the circuit is triggered

---

## Repository Structure
- `notebooks/` – analysis pipeline
- `figures/` – manuscript-ready figures
- `results/` – ABC activation outputs
- `environment.yml` – reproducible environment

---

## Status
This repository supports a manuscript prepared for preprint submission.
