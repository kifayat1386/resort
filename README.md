# Sreemangal Tea Resort & Golf — Master Project Proposal

A complete master project proposal for the development of an international 5-star eco-luxury tea-heritage resort on the Bangladesh Tea Board (BTB) property at Sreemangal, Moulvibazar, Bangladesh.

## Project at a Glance

| Parameter | Value |
|-----------|-------|
| Project Name | Sreemangal Tea Resort & Golf |
| Property Owner | Bangladesh Tea Board (Ministry of Commerce) |
| Location | Sreemangal, Moulvibazar, Bangladesh |
| Total Land Area | 26.00 Acres (78.70 Bigha) |
| Submitted By | Blue Mirror Project Group |
| Submission Date | October 2026 |
| Document Version | v1.0 — Concept Master Plan |
| Final Proposal Length | 40 pages (1 cover + 39 body) |

## Proposed Development Summary

| Zone | Component | Acreage |
|------|-----------|---------|
| 1 | Eco-Luxury & Duplex Cottages (110 units) | 6.81 |
| 2 | 5-Star U/L-Shaped Hotel Complex (150 rooms) | 3.66 |
| 3 | Mega Waterfront Lake & Floral Arboretum | 3.30 |
| 4 | Cable Car Transit System (0.5 km) | 0.57 |
| 5 | Eco-Heritage Mosque (200–300 musalli) | 0.28 |
| 6 | VIP Helipad (ICAO-compliant) | 0.34 |
| 7 | 9-Hole Golf Course | integrated |
| 8 | Conserved Tea Ridges & Green Buffer | 11.04 |
| **Total Built** | | **14.96** |
| **Total Conserved** | | **11.04** |
| **Grand Total** | | **26.00** |

## Repository Contents

```
.
├── README.md                                            This file
├── proposal/
│   └── Sreemangal_Tea_Resort_and_Golf_Master_Proposal.pdf   Final 40-page proposal
├── source-data/
│   ├── pdf/
│   │   └── PROFILE_TEA_RESORT_and_MUSEUM.pdf           Original BTB profile dossier (37 MB)
│   └── website/
│       ├── index.html                                   Live site HTML (60 KB)
│       ├── slides.json                                  Parsed slide deck (25 slides, structured)
│       ├── menu.json                                    Navigation menu (40 items)
│       ├── assets_manifest.json                         List of all 81 asset paths
│       ├── transcript.md                                Human-readable slide-by-slide transcript
│       └── assets/
│           ├── style_app.css                            Site stylesheet (12 KB)
│           ├── favicon.png
│           ├── images/                                  81 scraped images (renderings, plans, photos)
│           └── videos/                                  Video assets (if any)
└── assets/                                              (Reserved for future rendered diagrams)
```

## Source Materials

This proposal has been developed from two verified source materials:

1. **BTB Tea Resort & Museum Profile Dossier** (PDF, 37 MB)
   - The official project profile document of the Bangladesh Tea Board
   - Covers heritage context (1840s origin), ownership, timeline, existing infrastructure, proposed development zones, architectural concepts, and land balance sheet
   - Bilingual (English + Bengali)

2. **Interactive Project Presentation** (Website, https://bluemirror.24bd7.com/)
   - 25-slide interactive presentation covering all components of the proposed master plan
   - Sections include: project overview, executive summary, main gate, museum area, theme park, boundary wall, cable car, 9-hole golf course, 150-room hotel, cottages, accommodation, dining, swimming pool, waterway, cable car plan, tea garden, museum heritage, recreation, infrastructure, environmental plan, implementation roadmap, indicative budget, financial model, expected outcomes, and conclusion
   - Scraped in full (HTML + all static assets + parsed JSON)

## Proposal Structure

The 40-page proposal is organised as follows:

| Chapter | Title |
|---------|-------|
| Cover | Sreemangal Tea Resort & Golf — Master Project Proposal |
| TOC | Table of Contents |
| 1 | Executive Summary |
| 2 | Project Background & Heritage Context |
| 3 | Vision, Mission & Strategic Objectives |
| 4 | Existing Site Conditions & Asset Inventory |
| 5 | Proposed Master Plan & Components |
| 6 | Architectural & Design Philosophy |
| 7 | Environmental Sustainability & Conservation Plan |
| 8 | Implementation Roadmap & Phasing |
| 9 | Investment Framework & Financial Model |
| 10 | Risk Management & Governance Framework |
| 11 | Expected Outcomes & Socio-Economic Impact |
| 12 | Conclusion & Request for Approval |
| 13 | Annexures (A: Land Balance, B: Helipad Specs, C: Cable Car Params, D: Museum Artefacts, E: Source Materials, F: Contact) |

## How to Use This Repository

### To view the final proposal
Open `proposal/Sreemangal_Tea_Resort_and_Golf_Master_Proposal.pdf` in any PDF viewer.

### To review the original source materials
- BTB profile dossier: `source-data/pdf/PROFILE_TEA_RESORT_and_MUSEUM.pdf`
- Scraped website HTML: `source-data/website/index.html` (open in a browser)
- Structured slide content: `source-data/website/slides.json`
- Human-readable transcript: `source-data/website/transcript.md`

### To review the scraped images
Browse `source-data/website/assets/images/` — 81 PNG/JPG files covering:
- Current site photos (gate, cottages, museum, pool, aerial)
- Proposed renderings (gate, hotel, cottages, cable car, lake, helipad)
- Master plan diagrams (9-hole golf map, cable car plan, land use)

## Reproducibility

The proposal was generated using:
- **PDF skill (ReportLab + Playwright)** for body and cover
- **Python scraping script** (`scripts/scrape_bluemirror.py`) for website extraction
- **Python ReportLab script** (`scripts/generate_proposal.py`) for body PDF
- **HTML cover** (`scripts/proposal_cover.html`) rendered via Playwright
- **Merge script** (`scripts/merge_proposal.py`) using pypdf

All generation scripts are preserved outside this repo for reproducibility.

## Disclaimer

All figures, areas, and configurations in the proposal are based on the verified source materials and remain indicative pending:
- Detailed topographical survey
- Geotechnical investigation
- Environmental Impact Assessment (EIA)
- Verified Bill of Quantities (BOQ) and current market rates
- Formal approval by the Bangladesh Tea Board
- Statutory approvals from MOCA, DOE, CAAB, and local authorities

No total budget figure should be considered final until the BOQ is verified and tendered.

## Contact

- **Submitted By:** Blue Mirror Project Group
- **Submitted To:** Chairman, Bangladesh Tea Board
- **Project Location:** Sreemangal, Moulvibazar, Bangladesh
- **Document Version:** v1.0 — Concept Master Plan
- **Submission Date:** October 2026

---

*Confidential — For Official Review by the Bangladesh Tea Board.*
