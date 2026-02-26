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
| Form | Duration | Weight |
|---|---|---|
| Coursework: project proposal + graded coaching session | – | 40% |
| Oral end-of-module exam: project presentation + technical discussion | ~20 min | 60% |

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

## Course Structure: Two-Axis Framework

### Methods axis (confirmed, all at same abstraction level)
1. Spatial statistics & pattern analysis (autocorrelation, hotspots, interpolation)
2. Uncertainty quantification (Monte Carlo, error propagation, sensitivity)
3. Image processing — camera traps, automated detection (open: convince Nils this ≠ RS)
4. Multi-Criteria Analysis (spatial suitability, decision support)
5. Geovisualization (treated as cross-cutting output skill, introduced week 1, reinforced throughout)

Excluded (deliberate):
- Movement analysis → covered in consecutive Master's programme
- Remote sensing → separate module
- Google Earth Engine → briefly touched in RS course
- Databases → treated as infrastructure, not a standalone method

### Domains axis (confirmed)
1. Wildlife Monitoring (camera traps, spontaneous observations)
2. Vegetation Ecology (recordings over space and time)
3. Hydrology (vectorized river data etc.; RS/drone excluded)
4. Environmental Planning (visitor management/monitoring)

Note: Wildlife Monitoring and Environmental Planning share the same camera trap pipeline — image processing method block covers both.

### Pedagogical decisions (confirmed)
- Each method block is anchored to **one specific domain** (depth over breadth)
- Geovisualization introduced in week 1 as infrastructure, reinforced in every block
- Students choose a domain for their project and apply methods learned in class
- LLM/AI angle: students use pre-trained models/AI tools, oral exam tests whether they understood what the tool did

### Rough 14-week skeleton (draft)
| Weeks | Content |
|---|---|
| 1–2 | Foundations: spatial data refresher, databases, reproducible workflows (Quarto) + geovisualization |
| 3–4 | Spatial statistics & pattern analysis |
| 5–6 | Uncertainty quantification |
| 7–8 | Image processing (camera traps / automated detection) |
| 9–10 | Multi-Criteria Analysis |
| 11–12 | Project work + coaching sessions |
| 13–14 | Oral exams |

Domain-to-method assignments not yet decided.

## Next Steps
- Assign each method block to a specific domain
- Decide on concrete datasets per block (some exist in research group, some to be sourced)
- Refine week-by-week schedule
- Determine co-lecturers once topics are settled
- Update module description with more specific content once structure is confirmed
