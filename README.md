# Affordable AI for Agriculture in Southeast Asia
### Screened Literature Database and Search Strategy

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> **Associated paper:** Worasit Sangjan, Sirapoom *(TBC)*, Ittipon *(TBC)*, Kittiphum *(TBC)* — *"Affordable AI for Agriculture in Southeast Asia: Insights and Lessons for Developing Countries"* — *(Under review)*

---

## What is in this repository

| File | Description |
|---|---|
| `database/SEA_AI_database.csv` | Screened literature database — 502 entries covering AI, remote sensing, IoT, robotics, and adoption studies in Southeast Asian agriculture (2015–2026) |
| `database/SEA_AI_database_enhanced.xlsx` | Full Excel version with additional sheets (`raw data`, `title&tool`) |
| `search-strategy/search_strategy.md` | Complete WoS/Scopus Boolean search strings (Sets A–E) used to build the database |

---

## Database columns

| Column | Description |
|---|---|
| `Full author list` | All authors as listed in the original publication |
| `First Author(s) & Year` | Short citation key (e.g., "Smith et al., 2023") |
| `Article Title` | Full article title |
| `Application/Technology` | Primary technology category (Remote Sensing, IoT, Robotics, AI Models, etc.) |
| `Tech Used` | Specific tools/methods used |
| `Drone type` | UAV/drone platform if applicable |
| `is_ag` | Is this an agricultural application? (Yes / No) |
| `DOI Link` | DOI URL |
| `Abstract` | Article abstract |
| `Country(ies)` | Country/countries of study |
| `Tools` | Software/hardware tools mentioned |
| `SEA_status` | Relevance classification: `SEA`, `SEA_CORE`, `Background (keep)`, `Non-SEA → review for removal`, etc. |
| `Section_relevance` | Which manuscript section(s) this paper supports (e.g., `2.1`, `2.2`, `4.1`) |
| `In_manuscript` | Is this paper cited in the manuscript? (Yes / No / blank) |

---

## SEA_status values

| Value | Meaning |
|---|---|
| `SEA` | Study conducted in or directly about Southeast Asia |
| `SEA_CORE` | Foundational SEA paper — cited in multiple sections |
| `Background (keep)` | Non-SEA paper retained for context/methods background |
| `GLOBAL_BG` | Global/non-SEA paper used as global background |
| `Borderline-SEA → reclassify as SEA` | Flagged for reclassification |
| `Non-SEA → review for removal` | Non-SEA paper flagged for possible removal |

---

## How to cite

If you use this database or search strategy in your own work, please cite the associated paper:

> Sangjan W. et al. (2026). *Affordable AI for Agriculture in Southeast Asia: Insights and Lessons for Developing Countries*. *(Under review)*

---

## License

The database and search strategy files in this repository are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/). You are free to share and adapt the material for any purpose, provided you give appropriate credit.

---

## Contact

Worasit Sangjan — worasitsangjan.ws@gmail.com
