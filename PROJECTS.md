# Project index

This catalog represents the projects consolidated on October 22, 2026. Import dates describe repository housekeeping, not when the projects were developed. A source archive preserves implementation work; it does not imply a complete runnable release or fresh validation.

Most source repositories are private. Their names below identify them for account-level organization without presenting inaccessible links as public demos. Public source and portfolio links are labeled explicitly. New snapshot repositories include `MIGRATION.md` with provenance, exclusions and verification limits.

## Applications and analytical products

| Project | Technical focus | Source / public entry point | State |
| --- | --- | --- | --- |
| NeuroTrace MRI | Local MRI segmentation review, measurements, evidence export | `neurotrace-mri`; [case study and Windows download](https://lukasschulmeyer.com/projects/neurotrace-mri) | Desktop portfolio release; research use |
| Rankify | Normalized university course data, cohort views, read-only API/GPT integration | `rankify`; [case study](https://lukasschulmeyer.com/projects/rankify) | Public application; private source |
| Housing Market Observatory | Multi-source geographic data integration and explicit observed/derived/imputed lineage | `housing-market-observatory`; [case study](https://lukasschulmeyer.com/projects/housing-market-observatory) | Public application; private source |
| AniRec | MyAnimeList API integration, normalized community signals, deterministic ranking and caching | [Public source](https://github.com/lukaschulmeyer/anirec); [case study](https://lukasschulmeyer.com/projects/anirec) | Public application and source |
| US Food Prices Over Time | Published retail-price acquisition, source validation and comparable time-series views | `amazon-price-tracker`; [case study](https://lukasschulmeyer.com/projects/us-food-prices) | Existing implementation branches indexed from main |
| Classic Can Sales Explorer | Package eligibility, provenance and approximate case-to-can conversion | `alcohol-sales-explorer` | Local prototype; bounded county/product/month coverage; earlier alcohol explorer preserved |
| Storage Optimizer | Local model-assisted configuration, tabular data selection, storage/retrieval comparison workflow | `storage-optimizer` | Development/testing build; private source |
| iRec legacy | Movie/TV recommendation pipelines, catalog integration, ranking and review-coverage experiments | `irec-legacy` | Historical source plus newer legacy supplement; external data required; AniRec is the successor |
| Japan Trip Companion | Offline PWA, local planning, geolocation, phrasebook, backup and persistence | `japan-trip-companion` | Private synthetic-data demo; personal itinerary excluded |

## Biomedical data and reproducibility

These are research and portfolio tools. They do not establish clinical validity. Historical benchmark and test statements remain historical unless a repository's migration note explicitly records a new check.

| Project | Technical focus | Repository | State |
| --- | --- | --- | --- |
| BioData Benchmark Studio | Unified API reliability, ECG QC, expression-cohort and multi-omics surfaces | `biodata-benchmark-studio` | Source suite; generated data/evidence excluded |
| Biomedical Image Benchmark QA Lab | MedMNIST benchmark reproducibility, image QA and evidence packaging | `biomedical-image-benchmark-qa-lab` | Research prototype archive |
| Gene Evidence Atlas | Gene alias resolution and joins across public reference/evidence sources | `gene-evidence-atlas` | Research prototype archive |
| NGS Workflow Reproducibility Lab | Workflow/run evidence, reproducibility checks and report export | `ngs-workflow-reproducibility-lab` | Research prototype archive |
| Evidence Workbench | Provenance, claim boundaries, checksums and reproducible evidence packages | `quality-max-evidence-workbench` | Research prototype archive |
| RNA-Seq Cohort Explorer | Count-based cohort exploration and reproducible analytical outputs | `rna-seq-cohort-explorer` | Research prototype archive |
| Single-Cell Atlas QC | Single-cell quality-control summaries and source-linked exports | `single-cell-atlas-qc` | Research prototype archive |
| Source Health and Expression Cohort Explorer | Source contracts, drift/failure fixtures and cohort evidence packaging | `source-health-expression-cohort` | Exporter prototype; depends on BioData Benchmark Studio outputs |

BioData Benchmark Studio also preserves its API Reliability Harness, MIT-BIH ECG Signal QC Explorer, GSE45827 expression dashboard, cBioPortal BRCA multi-omics dashboard and earlier gene/single-cell/image modules. Some later lab repositories extend those earlier modules; they are not counted as unrelated inventions.

## Games, utilities and workflow tools

| Project | Technical focus | Repository | State |
| --- | --- | --- | --- |
| Threshold: Backrooms | Unity room generation, portals, geometry validation, shaders and authored layouts | `threshold-backrooms` | Source archive; external/restricted art and build dependencies excluded |
| One Shot Bird | Phaser/TypeScript browser-game and rendering experiment | `one-shot-bird` | Private local calibration project; original distribution boundaries retained |
| Sky Chirp | Canvas game loop, interaction and Web Audio | `sky-chirp` | Private local game prototype |
| Vibe Dev Environment / Quality Max Studio | Reusable development workflows, skill templates and verification tooling | `vibe-dev-environment` | Current local workflow source snapshot |
| Automated Help Tools | Email connector inputs, classification and triage/reporting logic | `automated-help-tools` | Private utility; credentials and mailbox records excluded |
| Monitor Hotkey | Windows hotkey and monitor power control | `monitor-hotkey` | Small PowerShell utility |
| Noir Corner Wallpaper | Canvas lighting/rain effects and multiple display layouts | `noir-corner-wallpaper` | Effect source; original artwork replaced with labeled neutral previews |
| eBay Listing Toolkit | Reusable CSV mapping and answer-review helpers | `ebay-listing-toolkit` | Sanitized utility subset with synthetic examples; inventory excluded |

## Portfolio and design work

| Project | Scope | Repository | State |
| --- | --- | --- | --- |
| Current portfolio | Project identity system, case studies and project navigation | `portfolio-website`; [website](https://lukasschulmeyer.com) | Production website |
| Desktop Portfolio Archive | Earlier Astro shell, evidence contracts and the Source Health Monitor application | `desktop-portfolio` | Historical source; generated evidence and personal artwork excluded |
| Portfolio Redesign Study | Editorial Ledger direction and earlier five-concept comparison | `portfolio-redesign-study` | Original two-commit history preserved |
| Portfolio Design Experiments | Four separate concepts: Archive, Gallery Archive, Rubberhose Theater and Studio Table | `portfolio-design-experiments` | Historical experiment collection |
| Anja Renovation Demo | Static renovation-site layout and local form feedback | `anja-renovation-demo` | Demonstration site; no live customer workflow implied |

## Other private project archives

- `focus-group-workflow`: generalized research workflow and blank templates. Personal opportunity records excluded. This is a document workflow, not a software application.
- `creative-story-development`: private creative-writing archive, listed separately from software.
- `mp2-app`: existing coursework repository retained with its original scope and history.

`portfolio-project-releases` holds [public release artifacts](https://github.com/lukaschulmeyer/portfolio-project-releases); this profile repository holds the catalog. They support the projects above rather than adding separate product claims.

Empty project folders, empty `mp4-backend`/`mp4-frontend` repositories, tooling smoke tests, unmodified upstream clones, dependency caches and duplicate backups are not presented as completed projects. Their status is recorded in the private migration audit.
