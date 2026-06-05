# Literature Search Strategy

**Paper:** Affordable AI for Agriculture in Southeast Asia: Insights and Lessons for Developing Countries  
**Databases:** Web of Science Core Collection · Scopus · Google Scholar  
**Generated:** 2026-04-16

---

## 1. Current Database Status

The screened literature database (`SEA_AI_database.csv`) contains 502 entries compiled from:
- Original Web of Science export (432 records)
- Manuscript citations and hand-searched references
- Targeted web searches to fill thematic gaps (IoT, adoption, AI models)

Sections 2.2 (IoT), 2.4 (AI Models), and 4–5 (Practical adoption) were identified as the primary coverage gaps. The search sets below were designed specifically to fill these gaps.

---

## 2. Search Sets

### Set A — Section 2.2: IoT and In-Field Sensing

Target: Low-cost IoT sensors, microcontrollers, weather/soil monitoring, and time-series data collection applied to agriculture in Southeast Asia.

**A1 — Core IoT + SEA** (Web of Science / Scopus)

```
TS = ("Internet of Things" OR "IoT" OR "wireless sensor" OR "smart sensor"
      OR "microcontroller" OR "Arduino" OR "Raspberry Pi" OR "LoRa"
      OR "MQTT" OR "edge computing" OR "in-field sensor")
AND TS = (agriculture OR farm* OR crop OR rice OR "soil monitoring"
          OR "irrigation" OR "precision agriculture")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR Myanmar OR Cambodia
          OR Laos OR Singapore OR Brunei)
```

> Expected yield: 60–120 records. Filter to 2018–2026.

---

**A2 — Low-cost sensing + smallholders**

```
TS = ("low-cost sensor*" OR "affordable sensor*" OR "cheap sensor*"
      OR "low-power sensor*" OR "WSN" OR "wireless sensor network")
AND TS = (agriculture OR "crop monitoring" OR "soil moisture"
          OR "weather station" OR "microclimate")
AND TS = ("developing countr*" OR "smallholder*" OR "Southeast Asia"
          OR Indonesia OR Vietnam OR Thailand OR Malaysia)
```

> Expected yield: 30–60 records.

---

**A3 — Smart greenhouse / controlled environment IoT in SEA**

```
TS = ("smart greenhouse" OR "greenhouse automation" OR "controlled environment"
      OR "hydroponic*" OR "vertical farm*" OR "indoor farm*")
AND TS = ("Internet of Things" OR IoT OR sensor OR Arduino OR "Raspberry Pi")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR Myanmar OR Singapore)
```

> Expected yield: 40–80 records. Much of this will also support Section 3.2.

---

### Set B — Section 2.3: Robotics and Automation

Target: Agricultural robots, automated sprayers, harvest robots, and mechanization for tropical/SEA crops.

**B1 — Agricultural robots in SEA / tropical crops**

```
TS = (robot* OR "autonomous vehicle" OR "unmanned ground vehicle" OR UGV
      OR "automated sprayer" OR "harvest robot*" OR "picking robot*"
      OR "agricultural mechanization" OR "farm automation")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "tropical crop*"
          OR rice OR "oil palm" OR sugarcane OR durian OR mango
          OR banana OR rubber OR cassava)
```

> Expected yield: 40–70 records. Filter 2018–2026.

---

**B2 — Low-cost / affordable robotics for smallholders**

```
TS = ("low-cost robot*" OR "affordable robot*" OR "simple robot*"
      OR "small-scale mechanization" OR "mini tractor" OR "power tiller"
      OR "drone sprayer" OR "UAV sprayer")
AND TS = ("smallholder*" OR "small farm*" OR "developing countr*"
          OR "Southeast Asia" OR Indonesia OR Vietnam OR Thailand)
```

> Expected yield: 20–40 records.

---

### Set C — Section 2.4: AI Models and Data Analytics

Target: Lightweight ML/DL models, TensorFlow Lite, edge AI, mobile-deployable models, and open-source AI tools applied to agriculture in SEA.

**C1 — Lightweight / edge AI for agriculture in SEA**

```
TS = ("TensorFlow Lite" OR "edge AI" OR "edge computing" OR "on-device"
      OR "lightweight model*" OR "model compression" OR "pruning"
      OR "quantization" OR "mobile deep learning" OR "MobileNet"
      OR "EfficientNet" OR "YOLO" OR "YOLOv*")
AND TS = (agriculture OR farm* OR crop OR "plant disease" OR "pest detect*"
          OR "yield predict*" OR "crop classif*")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "developing countr*"
          OR "low-resource" OR "resource-constrained")
```

> Expected yield: 30–60 records.

---

**C2 — Decision support systems and mobile AI tools for farmers**

```
TS = ("decision support system*" OR "DSS" OR "advisory system*"
      OR "mobile application" OR "smartphone app*" OR "farmer app*"
      OR "digital advisory" OR "AI advisory")
AND TS = (agriculture OR farm* OR crop OR rice OR "pest management"
          OR "disease management" OR "fertilizer" OR "irrigation")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "developing countr*"
          OR smallholder*)
```

> Expected yield: 40–80 records.

---

**C3 — Open-source ML/DL platforms in agricultural research (SEA-focused)**

```
TS = ("open-source" OR "open source" OR GitHub OR "Google Earth Engine"
      OR "OpenDroneMap" OR "BreedBase" OR "FieldBook"
      OR "scikit-learn" OR "PyTorch" OR "Keras" OR "R package")
AND TS = (agriculture OR "crop monitoring" OR phenotyp* OR "remote sensing"
          OR "yield estimation" OR "disease detection")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "developing countr*")
```

> Expected yield: 20–50 records.

---

### Set D — Sections 3.1 & 3.2: HTP and Controlled Environments *(optional top-up)*

Run these only if additional coverage is needed after Sections 3.1–3.2 are finalised.

**D1 — HTP / plant phenotyping in SEA**

```
TS = ("high-throughput phenotyp*" OR "HTP" OR "plant phenotyp*"
      OR "UAV phenotyp*" OR "field phenotyp*" OR "image-based phenotyp*")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR Myanmar OR "tropical crop*")
```

> Expected yield: 15–30 records.

---

**D2 — AI in controlled environment agriculture in SEA**

```
TS = ("controlled environment agriculture" OR "plant factory"
      OR "greenhouse" OR "hydroponic*" OR "aeroponic*"
      OR "vertical farm*" OR "indoor cultivation")
AND TS = ("machine learning" OR "deep learning" OR "artificial intelligence"
          OR "computer vision" OR "image processing" OR IoT OR sensor)
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR Singapore)
```

> Expected yield: 30–60 records. Will overlap with Search Set A3.

---

### Set E — Sections 4 & 5: Practical Adoption and Pathways

Target: Technology adoption by smallholders, barriers to digital agriculture, service models, policy frameworks, and lessons from other developing regions.

**E1 — Technology adoption barriers in SEA agriculture**

```
TS = ("technology adoption" OR "digital adoption" OR "ICT adoption"
      OR "precision agriculture adoption" OR "AI adoption"
      OR "barrier*" OR "challenge*" OR "obstacle*")
AND TS = (agriculture OR farm* OR "smallholder*" OR "small farm*"
          OR "rural farmer*")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR Myanmar OR "developing countr*")
```

> Expected yield: 50–100 records. Central for Section 5.1.

---

**E2 — Service-based and cooperative models for affordable ag-tech**

```
TS = ("UAV-as-a-service" OR "drone service*" OR "drone hire"
      OR "IoT cooperative*" OR "shared service*" OR "pay-per-use"
      OR "agricultural service provider*" OR "custom hiring centre"
      OR "precision agriculture service*")
AND TS = (agriculture OR farm* OR rice OR "oil palm" OR sugarcane
          OR "smallholder*")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "developing countr*")
```

> Expected yield: 20–40 records. Central for Section 5.2.

---

**E3 — Policy and capacity building for digital agriculture in developing countries**

```
TS = ("digital agriculture polic*" OR "agricultural digital transformation"
      OR "capacity building" OR "farmer training" OR "extension service*"
      OR "digital literacy" OR "e-agriculture" OR "agri-digital")
AND TS = ("Southeast Asia" OR Indonesia OR Vietnam OR Thailand
          OR Malaysia OR Philippines OR "developing countr*"
          OR "low-income countr*" OR ASEAN)
```

> Expected yield: 40–80 records. Supports Sections 5.2, 5.3, and 6.3.

---

**E4 — Lessons from other developing regions** *(for Section 5.5 comparison)*

```
TS = ("smallholder*" AND ("digital technology" OR "mobile technology"
      OR "precision agriculture" OR "AI" OR "machine learning"))
AND TS = ("sub-Saharan Africa" OR "South Asia" OR "Latin America"
          OR India OR "East Africa" OR "West Africa")
AND TS = (adoption OR "success factor*" OR "lesson*" OR "scale up"
          OR "transferable" OR "replicabl*")
```

> Expected yield: 30–60 records. Provides comparative cases for Section 5.5.

---

## 3. Execution Guidance

### Recommended database order

1. **Web of Science Core Collection** — primary (same source as existing database)
2. **Scopus** — run the same queries; cross-check for new titles not in WoS
3. **Google Scholar** — use for grey literature, reports, and policy documents (Sets E3, E4)

### Filters to apply in WoS / Scopus

- Publication year: 2018–2026
- Language: English
- Document types: Article, Review, Conference Paper (exclude Book Chapter unless key)
- After export: screen by title/abstract; apply `is_ag` and `SEA_status` columns as in the existing database

### Estimated new papers (after deduplication and screening)

| Search Set | Topic | Estimated new SEA papers |
|---|---|---|
| A (IoT) | In-field sensing | 40–70 |
| B (Robotics) | Agricultural robots | 20–40 |
| C (AI Models) | Lightweight/edge AI | 30–60 |
| D (HTP/Greenhouse) | Phenotyping *(optional)* | 15–30 |
| E (Adoption) | Barriers & pathways | 50–90 |
| **Total** | | **~155–290** |

### Priority by team member

| Author | Priority sets | Sections |
|---|---|---|
| Worasit | A1, A2, C1, C2 | 2.2, 2.4 |
| Sirapoom | E1, E2, E3 | 5.1–5.3 |
| Kittiphum | B1, B2 | 2.3 |
| Ittipon | D1, D2 *(if needed)* | 3.1–3.2 |

### Adding results to the database

Export new WoS/Scopus results as `.xlsx` or `.csv`. Add to `SEA_AI_database.csv` with the same column structure. Fill in: `Article Title`, `Full author list`, `First Author(s) & Year`, `DOI Link`, `Application/Technology`, `Country(ies)`, `is_ag`, `SEA_status`, `Section_relevance`, and `In_manuscript`.
