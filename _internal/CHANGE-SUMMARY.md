# CHANGE SUMMARY — AAS Structural + MEP Integration Brochure (v1.2)

**Source:** Allied Buildings *Custom Structural Rack Solutions* brochure (6 pages, A4 landscape, Canva, May 2026)  
**Output:** 8-page adoption-ready draft under `/workspace/aas-brochure/`  
**Author intent:** Expand Allied rack brochure for **Allied Advanced Systems (AAS)** plant-integration / MEP face — work-facing capabilities only.  
**This pass (v1.2):** Blend original brochure photography / illustrations into matching product pages so the draft feels like the real Allied brochure, not diagram-only. Keep MEP-engineering-available language from v1.1.

**Credit:** Imagery adapted from Allied structural rack brochure.

---

## Brand assumption (flag for Michael)

| Item | Assumption |
|---|---|
| Primary brand line | **Allied Advanced Systems** |
| Pedigree line | *Built on Allied’s structural steel pedigree* |
| Dual lockup | AAS lead + Allied Buildings mark until AAS logo approved |
| Contacts | **Keep source Allied contacts** (1.877.997.8335 / INFO@ALLIEDBUILDINGS.COM / alliedbuildings.com) until AAS-specific contact exists |
| Product family | Retain RK-MAS, RK-MEP, RK-CUDR; add **RK-INT** as clearly marked **draft** offering name |

---

## What changed in v1.2 (art from original)

### Crops → `/workspace/aas-brochure/assets/from-original/`

Source PDF re-rendered at 250 dpi → `assets/source-pages-hires/page-1.png` … `page-6.png`. Useful hero/product imagery cropped with ImageMagick/PIL (text-only blocks skipped).

| Crop file | From source page | Content | Lands in 8-page layout |
|---|---|---|---|
| `cover-layers-illustration.png` | p1 (right) | Cable tray / utility / piping layers art | **p01 Cover** hero visual |
| `cover-bg-darkened.png` | p1 (left) | Data-center aisle photo (darkened) | **p01 Cover** sheet background |
| `cover-hero-aisle.png` / `cover-hero-wide.png` / `cover-aisle-floor.png` | p1 (left) | Aisle / rack photo variants | Asset bank (cover bg uses darkened full) |
| `why-fab-detail.png` | p6 | Robotic welding / steel fab detail | **p02 Why Allied** sidebar |
| `texture-navy-grid.png` | p1 (right) | Navy blueprint grid sample | **p03 Scope Map** + **p07 RK-INT** subtle bg |
| `rk-mas-aisle-render.png` | p3 (right) | Modular aisle structure 3D render | **p04 RK-MAS** |
| `rk-mep-platform-photo.png` | p4 (inset) | Outdoor multi-level platform photo | **p05 RK-MEP** inset |
| `rk-mep-platform-render.png` | p4 (main) | Platform + stairs 3D render | **p05 RK-MEP** main |
| `rk-cudr-pipe-photo.png` | p5 (inset) | Blue/yellow rack with multi-trade piping | **p06 RK-CUDR** inset |
| `rk-cudr-rack-render.png` | p5 (main) | Long-span utility rack isometric | **p06 RK-CUDR** main |
| `cta-welding-fab.png` | p6 (right) | Robot welding sparks / fab | **p08 Delivery + CTA** |
| `accent-photo-strip.png` | p1 | Slim industrial strip | Asset bank |

**Not cropped:** Original p2 (*Why Allied*) is text-only — no product photography; Why page uses closing/fab art from p6 instead.

### Kept (no original equivalent)
- `assets/scope-map.svg` → Scope Map (p03)
- `assets/rk-int-flow.svg` → RK-INT (p07)
- Product diagram SVGs retained on disk for reference; product pages now prefer original brochure art.

### Copy / MEP claim
- Unchanged from v1.1: default = structural + coordinate; **full MEP engineering available when required**; PE stamp jurisdiction TBD.
- Captions credit: *Imagery adapted from Allied structural rack brochure.*
- No invented project photos; no email/upload.

### PDF + previews
- Regenerated: `AAS_Structural_MEP_Integration_Brochure-vDRAFT.pdf` (Chromium headless)
- Previews: `previews/v1.2-page-*.png`

---

## Remaining TBDs

1. **Photography** — Additional real project / factory photos still optional; v1.2 uses original brochure imagery only.  
2. **PE stamp jurisdictions** — Confirm which states / provinces AAS can stamp for MEP; leave TBD until known.  
3. **Logo / identity** — AAS wordmark, dual-lockup rules with Allied Buildings.  
4. **Brand lead** — Confirm AAS primary vs Allied Buildings primary with AAS capability banner.  
5. **Contact** — AAS-specific phone / email / URL.  
6. **RK-INT name** — Draft SKU; confirm before print.  
7. **Page count / trim** — Letter landscape 8 pp vs A4; designer rebuild in Canva/InDesign optional.  
8. **1M+ metric label** — Clarify unit with marketing before print.  
9. **Controls language** — Confirm depth of commissioning handoff vs licensed controls EOR.  
10. **Cover aisle text bleed** — Original cover photo has baked-in Canva text; darkened as background + layers illustration as primary hero to avoid double-copy.

---

## Files

| Path | Purpose |
|---|---|
| `/workspace/aas-brochure/AAS_Structural_MEP_Integration_Brochure-vDRAFT.html` | Print-oriented HTML with original imagery + diagrams |
| `/workspace/aas-brochure/AAS_Structural_MEP_Integration_Brochure-vDRAFT.pdf` | Chromium headless PDF |
| `/workspace/aas-brochure/AAS_Structural_MEP_Integration_Brochure-vDRAFT.md` | Full page-by-page copy |
| `/workspace/aas-brochure/CHANGE-SUMMARY.md` | This document |
| `/workspace/aas-brochure/assets/from-original/*.png` | Crops from Allied rack brochure |
| `/workspace/aas-brochure/assets/*.svg` | Diagram assets (Scope Map / RK-INT kept in layout) |
| `/workspace/aas-brochure/assets/source-pages-hires/*.png` | 250 dpi source page renders |
| `/workspace/aas-brochure/previews/v1.2-page-*.png` | v1.2 page previews |

---

## Exclusions (per brief — verified absent)

- Ownership / deal structures, Spinoff Forge  
- NDA finance numbers, bonus pools, Jet, compensation  
- Invented certifications, tonnage, country counts, or PE state licenses  
- Invented proprietary SKUs beyond marked draft name **RK-INT**  
- Claims that new diagrams are project photos  
- Fake / invented project photography  
- Email send / Drive upload  
