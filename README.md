# PILOT-HARMONY  
High-dimensional data standardization and metadata harmonization within TRR-359 (PILOT)

---

## Overview

**PILOT-HARMONY** is an INF-led coordination and documentation effort within the TRR-359 (PILOT) consortium  
(*Perinatal Development of Immune Cell Topology*).

The project supports PILOT researchers by:
- improving interoperability of high-dimensional biological data,
- harmonizing metadata and naming conventions,
- and enabling cross-dataset discovery and pattern-matching use cases.

PILOT-HARMONY does **not** aim to host research data or enforce rigid standards.  
Instead, it provides a **pragmatic, use-case-driven framework** for aligning data formats, metadata, and workflows across participating groups.

---

## Context and Responsibility

Within TRR-359, the **INF (Information Infrastructure)** project is responsible for research data management (RDM), data interoperability, and sustainable data workflows.

PILOT-HARMONY is coordinated by the Research Data Management group at the  
Institute of Medical Biometry and Statistics (IMBI), University of Freiburg,  
under the supervision of Prof. Harald Binder.

The repository serves as a **transparent record of decisions, timelines, and recommendations** emerging from INF activities.

---

## Origin of the Project

The project builds on discussions from the:

- **PILOT–RDM High-dimensional Data Meeting (05 Dec 2025)**  
  → identification of key challenges in data formats, metadata consistency, and dataset comparability  
  → definition of two initial use cases

- **Technical follow-up meeting (13 Jan 2026)**  
  → detailed discussion of existing data structures and realistic next steps  
  → agreement on reusing selected existing datasets as initial test data

---

## Initial Use Cases

### Use Case 1 — Internal Dataset Discovery by Biology  
Enable discovery of datasets based on biological characteristics  
(e.g. cell types, immune states, tissues), independent of original annotation choices.

### Use Case 2 — Internal Pattern Matching Across Datasets  
Enable identification of similar biological patterns across datasets  
(e.g. comparable gene expression signatures or cell states).

These use cases are intentionally scoped to be **testable, realistic, and extensible**.

---


## Roadmap

<details>
  <summary>
Table view
  </summary>

| What | When | Responsible | Outcome / Comment |
|---|---|---|---|
| Identification of challenges & use cases | 05 Dec 2025 | Dr. Felix Engel, Dr. Katrin Kierdorf, Prof. Dr. med. Markus Sperandio, Prof. Dr. Claus-Werner Franzke, Dr. Anneke Haddad, Thomas, Maria, Dr. Sagar Sagar, Prof. Dr. Harald Binder, Dr. Michele Proietti, Dr. Gabriele Lubatti, PD Dr. Roman Sankowski, Aref Kalantari | Two initial use cases defined |
| Technical follow-up meeting & selection of initial test datasets | 26 Jan 2026 | Aref Kalantari , Dr. Felix Engel, Dr. Sagar Sagar | Detailed discussion of existing data structures; agreement on next steps; selected initial test datasets |

</details>

---

### Project #1: Data-intrinsic annotation and discovery using gene-to-text

Project #1 implements the two agreed use cases by introducing a **data-intrinsic annotation layer**, derived directly from high-dimensional expression data rather than relying solely on author-provided labels or metadata.

The central idea is to translate quantitative gene expression profiles into **standardized textual representations** (“gene-to-text”), which can be compared, searched, and validated across datasets in a reproducible manner.

---

#### Use Case 1 — Internal Dataset Discovery by Biology

**Goal**  
Enable discovery of datasets based on biological characteristics (e.g. cell types, immune states, activation patterns), even when original annotations differ between studies.

---

#### Use Case 2 — Internal Pattern Matching Across Datasets

**Goal**  
Given a biological pattern observed in one dataset, identify similar patterns in other datasets.

---

## Participation

PILOT-HARMONY is a **collaborative effort**.

Researchers are invited to:
- contribute datasets for testing use cases,
- provide feedback on metadata conventions,
- and participate in refining recommendations.

Participation does not imply loss of data ownership.

---


## Contact

For questions or contributions related to PILOT-HARMONY, please contact the INF coordination team  
at the Institute of Medical Biometry and Statistics (IMBI), University of Freiburg or directly:
 
Email: [aref.kalantari@uniklinik-freiburg.de](mailto:aref.kalantari@uniklinik-freiburg.de)
