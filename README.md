# Adaptive Biocomputational Control (ABC)

## Overview
Adaptive Biocomputational Control (ABC) is a systems immunology framework that models immune responses as logic-gated control systems rather than isolated gene expression changes.

The framework distinguishes **regulatory** and **effector** immune dominance using interpretable cytokine logic and tests robustness under biological noise using stochastic simulations.

Status: Research framework and exploratory analysis (ongoing)
This repository contains dataset-specific notebooks implementing the ABC immune control framework described in the accompanying LinkedIn post. Code is modular, exploratory, and intended to demonstrate conceptual validity rather than final optimization.


## Core Idea
Immune behavior is treated as a **state-based decision system** governed by interacting cytokines:

- Cytokines act as input signals
- Logic-gated rules define immune state transitions
- Regulatory and effector programs act as mutually exclusive control modules
- Stochastic dynamics are used to assess robustness

This moves beyond descriptive transcriptomics toward **mechanistic immune decision modeling**.

---

## Datasets Used
The framework is evaluated across distinct immune contexts:

- **Inflammatory Bowel Disease (GSE100833)**  
  Chronic tissue inflammation with regulatory–effector imbalance

- **COVID-19 PBMCs (GSE157103)**  
  IFN-γ–dominated effector immune activation

- **Melanoma under Immunotherapy (GSE165278)**  
  Effector reactivation versus immune exhaustion

Each dataset is processed independently to preserve biological context.

---

## Repository Structure

- Dataset notebooks perform immune state classification
- Stochastic and cross-disease analyses are handled separately

---

## Planned Extensions
- Data-calibrated logic using interpretable machine learning
- Expanded cytokine networks
- Multi-layer immune control modeling

---

## Author
Shravani B.S. Bollapragada  
Independent Undergraduate Researcher

