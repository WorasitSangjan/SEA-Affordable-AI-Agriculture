# Affordable AI for Agriculture in Southeast Asia
### Screened Literature Database and Search Strategy

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Associated paper:** *(Under soon)*

---

## About this repository

This repository contains the screened literature database and Boolean search strategy underlying the systematic review paper above. The database documents peer-reviewed studies on AI, remote sensing, IoT, robotics, and digital technology adoption in Southeast Asian (SEA) agriculture published between 2015 and 2026.

The database was compiled from Web of Science Core Collection and Scopus exports, supplemented by targeted hand-searches to fill thematic gaps (IoT, adoption studies, AI models). All entries were screened by title and abstract for agricultural relevance and geographic scope, then tagged by technology domain, SEA relevance status, and manuscript section.

**Key statistics:**
- **502** total screened entries
- **428** studies with SEA or SEA_CORE status (conducted in or directly about Southeast Asia)
- **171** papers cited in the associated manuscript
- **95%** of entries have a verified DOI link
- Coverage: Indonesia, Vietnam, Thailand, Malaysia, Philippines, Myanmar, Cambodia, Laos, Singapore, Brunei + global background references

---

## Repository contents

| File | Description |
|---|---|
| `database/SEA_AI_database.csv` | Primary screened literature database — 502 entries, 14 columns. DOI links verified May 2026. |
| `database/SEA_AI_database_enhanced.xlsx` | Full Excel version with additional sheets (`raw data`, `title&tool`). Mirrors all DOI and title corrections in the CSV. |
| `search-strategy/search_strategy.md` | Complete WoS/Scopus Boolean search strings (Sets A–E) used to build the database, with estimated yields and execution guidance. |

---

## Database columns

| Column | Description |
|---|---|
| `Full author list` | All authors as listed in the original publication |
| `First Author(s) & Year` | Short citation key used throughout the manuscript (e.g., "Smith et al., 2023") |
| `Article Title` | Full article title |
| `Application/Technology` | Primary technology category (Remote Sensing, IoT, Robotics, AI Models, etc.) |
| `Tech Used` | Specific tools, platforms, or methods used (e.g., Sentinel-2, Arduino, YOLOv8) |
| `Drone type` | UAV/drone platform if applicable |
| `is_ag` | Is this an agricultural application? (Yes / No) |
| `DOI Link` | Full DOI URL |
| `Abstract` | Article abstract |
| `Country(ies)` | Country or countries of study |
| `Tools` | Software or hardware tools mentioned in the paper |
| `SEA_status` | Relevance classification (see table below) |
| `Section_relevance` | Which manuscript section(s) this paper supports |
| `In_manuscript` | Whether this paper is cited in the associated manuscript (Yes / No / blank) |

---

## SEA_status values

| Value | Meaning |
|---|---|
| `SEA` | Study conducted in or directly about Southeast Asia |
| `SEA_CORE` | Foundational SEA paper cited across multiple sections |
| `Background (keep)` | Non-SEA paper retained for methodological or global context |
| `GLOBAL_BG` | Global or non-SEA paper used as broad background |
| `Borderline-SEA → reclassify as SEA` | Paper flagged for reclassification |
| `Non-SEA → review for removal` | Non-SEA paper flagged for possible removal |

---

## Section_relevance labels

Papers are tagged to one or more of the following manuscript sections:

| Tag | Manuscript section |
|---|---|
| `2.1 Remote Sensing` | Section 2.1 — Remote Sensing and UAV Imaging |
| `2.2 IoT` | Section 2.2 — IoT and In-Field Sensing |
| `2.3 Robotics` | Section 2.3 — Robotics and Automation |
| `2.4 AI Models` | Section 2.4 — AI Models and Data Analytics |
| `2.5 Integration` | Section 2.5 — Integration and System Design |
| `3.1 HTP/Phenotyping` | Section 3.1 — High-Throughput Phenotyping |
| `3.2 CEA` | Section 3.2 — Controlled Environment Agriculture |
| `4 Smallholders` | Section 4 — Technologies with Proven Practical Use |
| `4/5 Practical/Adoption` | Sections 4–5 — Practical use and adoption pathways |
| `5 Pathways` | Section 5 — Pathways to Adoption |
| `Intro/Background` | Introduction or general background |

---

## How to cite

If you use this database or search strategy in your own work, please cite the associated paper:

>  *(Under soon)*

---

## License

The database and search strategy files in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material for any purpose, provided you give appropriate credit.

---

## Contact

Worasit Sangjan — worasitsangjan.ws@gmail.com
