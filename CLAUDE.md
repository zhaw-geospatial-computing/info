# Project Memory: Geospatial Computing Course Development

## Context
- Module: **Geospatial Computing** (new course under development)
- Institution: ZHAW, Institut für Umwelt und Natürliche Ressourcen
- Study programme: BSc Umweltingenieurwesen
- Module coordinator: **Nils Ratnaweera** (+41 58 934 55 63 / nils.ratnaweera@zhaw.ch)
- Cohort: UI24

## Module Structure
- **Semester:** 5th (HS)
- **Type:** Wahlpflichtmodul (Elective Module)
- **Minor:** Spatial Data Science
- **ECTS:** 5 (= 150h total workload)
- **Contact hours:** ~4 × 45 min/week × 14 weeks ≈ 56h contact
- **Language:** English
- **Prerequisite:** Geoinformatik und GIS (3rd semester)
- **Follow-up modules:** None
- **Attendance requirement:** None

## Target Audience
- 5th semester environmental engineering students (~30 students)
- Focus: "Naturmanagement" with minor "Spatial Data Science" (but not exclusively)
- Have prior GIS experience (Geoinformatik und GIS) and some programming background

## Workload Breakdown
| | Hours |
|---|---|
| Contact Hours | 56 |
| Guided Self-Study | 34 |
| Independent Self-Study | 60 |
| Total | 150 |

## Assessment (confirmed)
| Form | Weight |
|---|---|
| Predicate: Project proposal (pass/fail) | – |
| Predicate: Written project report (pass/fail) | – |
| Predicate: Coaching session attendance (pass/fail, Präsenzpflicht Fall 2) | – |
| Oral end-of-module exam: project presentation + technical discussion (~20 min) | 100% |

- All predicates must be passed to sit the oral exam / pass the module
- The oral exam tests understanding of methods/results, NOT the project output itself (guard against unreflected AI use)
- 30 students × 20 min = 10 hours of examining → needs 2–3 exam days + co-examiner
- Co-lecturers: to be determined after topics are settled

## Module Content (from studienplanner)
- Advanced concepts of vector and raster geospatial data
- Script-based spatial data processing and analysis (R)
- Integration of scripting workflows with GUI-based GIS software (e.g. QGIS)
- Spatial analysis and transformation of geospatial datasets
- Visualisation and communication of spatial information
- Automation and reproducibility of geospatial workflows
- AI-assisted approaches to geospatial analysis and coding
- Applied case studies in environmental and spatial data analysis

## Key Files
- `geospatial_computing_studienplanner.md` — short module description (source of truth for content)
- `geospatial_computing_modulbeschreibung_draft.md` — filled module description (English only; German translation handled by Language Services)
- `Word_Modulbeschreib_vorlage_neues_curriculum_de_en.md` — official Word template (bilingual)
- `bsc-ui-moduluebersicht.pdf` — full BSc module overview (2 pages, visual)

## Admin Notes
- German translation of module description handled by Language Services team
- "Scal" enters Studiengang and Rechtsordnung fields
- Template field "Leistungsnachweis" is displayed differently in Moku vs. the Word template

## Course Structure

### Blocks (confirmed, no numbers)

- **Introduction** (week 1, rata) — module intro, toolchain setup, CRS/projections recap
- **Terrain & Water** (murj, weeks 2–3) — domain: Hydrology
- **Spatial Ecology & Occurrence Data** (rahn, weeks 4–5) — domain: Wildlife Monitoring
- **Paths & Flows** (rata, weeks 6–7) — domain: Environmental Planning
- **Semester Project** (rata, week 8) — introduction & topic finding
- **Advanced / Applied Sessions** (weeks 9–11) — one per block, see below
- **Semester Project** (all, weeks 12–14) — coaching and guided self-study

### Weeks 9–11: Advanced Sessions (one per block)

| W | Block | Subtitle | Lecturer |
|---|---|---|---|
| 9 | Terrain & Water | Workflow Automation (QGIS Graphical Modeler, batch processing) | murj |
| 10 | Spatial Ecology & Occurrence | Webmapping in the Open Source Ecosystem | rahn |
| 11 | Paths & Flows | Uncertainty in Geodata (OSM quality, routing/isochrone sensitivity, Monte Carlo) | rata |

- Uncertainty is covered in week 11, tied to the Paths & Flows domain (concrete, visual examples)
- The three standalone "Uncertainty in X" sessions were dropped as too abstract

### Domains (confirmed)
- Wildlife Monitoring (camera traps, opportunistic observations)
- Hydrology (vectorised river data; RS/drone excluded)
- Environmental Planning (visitor management/monitoring)

## Semester Plan (Geospatial-Computing-CurrFS27.xlsx → Sheet: Wochenprogramm)

- Source of truth for the weekly plan is the xlsx file, Sheet "Wochenprogramm" (other sheets are from a different module)
- Read the xlsx with openpyxl (file can be open in LibreOffice while reading)
- File was renamed from SpatialDataScienceDotationCurrFS27.xlsx to Geospatial-Computing-CurrFS27.xlsx

### Column structure (as of 2026-05-07)
- **Block** — topic spanning multiple weeks (cells merged in Excel)
- **Subtitle** — short per-week description
- **Details / keywords** — current combined column; being split into:
  - **Theory** — concepts and background covered in lecture
  - **Labs** — hands-on exercises
  - **Seminar / Group work** — interactive activities (not every week; more = better)

### Weekly plan summary

| W | Block | Subtitle |
|---|---|---|
| 1 | Introduction | Module Introduction |
| 2 | Terrain & Water | Raster Data Fundamentals |
| 3 | Terrain & Water | Terrain Analysis & Hydrological Modelling |
| 4 | Spatial Ecology & Occurrence | From Observations to Spatial Data |
| 5 | Spatial Ecology & Occurrence | Spatial Patterns in Point Data (KDE, IDW) |
| 6 | Paths & Flows | Networks & Graph Theory |
| 7 | Paths & Flows | Routing & Accessibility Analysis |
| 8 | Semester Project | Introduction & Topic Finding |
| 9 | Terrain & Water | Workflow Automation |
| 10 | Spatial Ecology & Occurrence | Webmapping in the Open Source Ecosystem |
| 11 | Paths & Flows | Uncertainty in Geodata |
| 12 | Semester Project | Coaching Sessions |
| 13 | Semester Project | Guided Self-Study |
| 14 | Semester Project | Guided Self-Study |

## Next Steps
