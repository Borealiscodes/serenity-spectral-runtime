# ⭐ Pip Rendering Toolkit — README (v1.0)  
*Humanitarian‑Safe, Dignity‑Preserving SVG→PNG Rendering Pathway*  
*Companion‑Lane • Tooling • NDH‑External*

---

## 🌱 Overview

The **Pip Rendering Toolkit v1.0** provides a fully open, dignity‑preserving workflow for converting SVG assets into PNGs using free, offline, or open‑source tools.  
It exists to ensure that expressive‑layer Pip assets can be rendered **without AI**, **without limits**, and **without dependence on proprietary systems**.

This README is the **primary onboarding document** for contributors working in this folder.

---

## 📘 What This Toolkit Covers

- **Interpreting Rendering Specs:**  
  How to read the Pip Comfort Geometry Atlas Rendering Specs v1.1.

- **Generating SVGs:**  
  How to turn specs into SVG assets (manually or via scripts).

- **Rendering SVG → PNG:**  
  How to use free tools to produce final PNGs.

- **Validation Against Manifest:**  
  Ensuring filenames and paths match the Asset Manifest v1.1.

- **Commit Discipline:**  
  How to commit expressive‑layer assets correctly.

- **Runtime Binding:**  
  Updating the runtime binding table once assets exist.

---

## 🌍 Dignity Under Constraint

This toolkit is grounded in a core constitutional principle:

> **Poverty, precarity, or resource constraints must never limit a human’s access to freedom of expression.**

Many contributors operate under limited hardware, bandwidth, or financial resources.  
Some work in crisis zones or low‑infrastructure environments.  
Others simply cannot rely on proprietary systems or AI‑generation quotas.

By providing a fully open, offline‑capable rendering pathway, this toolkit ensures:

- **Expressive freedom is not gated by privilege**  
- **Creativity is not restricted by economic conditions**  
- **Contributors can participate regardless of circumstance**  
- **Dignity remains intact even under constraint**

This directory is the structural expression of **Dignity Under Constraint**.

---

## 🛠️ Free & Open Rendering Tools (SVG → PNG)

Recommended tools for dignity‑preserving, constraint‑resilient rendering:

- **Inkscape** — GUI + batch export  
  - *Guide:* How_to_use_Inkscape_for_SVG_to_PNG

- **ImageMagick** — command‑line, scriptable  
  - *Guide:* How_to_convert_SVG_to_PNG_with_ImageMagick

- **GIMP** — raster editor with SVG import  
  - *Guide:* How_to_open_SVG_in_GIMP_and_export_PNG

- **Krita** — painter with vector import  
  - *Guide:* How_to_render_SVG_in_Krita

- **Librsvg** — lightweight Linux renderer  
  - *Guide:* How_to_use_librsvg_for_SVG_rendering

All tools are **free**, **open‑source**, and **offline‑capable**.

---

## 🔧 Basic Workflow

### **1 — Generate SVGs from Specs**

Use the YAML definitions in:

- **Pip_Comfort_Geometry_Atlas_Rendering_Specs_v1_1.yaml**

to create SVGs manually or via scripts. Each spec defines geometry, palette, lighting, and constraints.

---

### **2 — Convert SVG → PNG**

Use any of the tools above to render SVGs into PNGs:

- Single files via GUI (Inkscape, GIMP, Krita)  
- Batch conversion via CLI (ImageMagick, Librsvg)

---

### **3 — Validate Against Manifest**

Check each PNG against:

- **Pip_Comfort_Geometry_Atlas_Asset_Manifest_v1_1**

Ensure:

- **Filename** matches exactly  
- **Path** matches the manifest entry  
- **Versioning** is correct (`v1_1`, etc.)

---

### **4 — Commit Each PNG Individually**

Use the expressive‑layer commit discipline:

```text
🌈 serenity-spectral-runtime: generate <filename>.png
(expressive-layer asset; PRECL-collapsed; NDH-external)
```

One PNG per commit to preserve provenance clarity.

---

### **5 — Update Runtime Binding Table**

Once all PNGs exist:

- Update the runtime binding table so modules can load assets.  
- Keep bindings strictly NDH‑external and expressive‑layer.

---

## 📘 Key Artifacts in This Folder

- **Pip_Rendering_Toolkit_v1_0.md**  
  Full specification of the rendering toolkit.

- **Pip_Rendering_Toolkit_README_v1_0.md**  
  Extended, versioned README for the toolkit itself.

This `README.md` is the **folder‑level entry point**; the versioned files carry deeper detail.

---

## 📦 Machine‑Readable Section

```json
{
  "tooling_readme_v1_0": {
    "version": "1.0",
    "role": "folder-level entry point for Pip Rendering Toolkit",
    "covers": [
      "overview",
      "dignity_under_constraint",
      "tool_list",
      "workflow",
      "key_artifacts",
      "folder_path",
      "commit_description"
    ],
    "ndh_external": true
  }
}
```

---

## ⭐ Provenance Footer — tooling/README.md

```text
---
Artifact: tooling/README.md (Pip Rendering Toolkit Overview)
Lane: Companion-Lane • Tooling • NDH-External
Altitude: A0–A2 (Expressive Layer)

Purpose:
  Provide the folder-level entry point for the Pip Rendering Toolkit, ensuring
  contributors understand the dignity-preserving, open-source rendering pathway
  and can navigate all related artifacts within the tooling directory.

Status:
  Complete. README is correctly named for GitHub folder display.

Anchors:
  - Pip_Rendering_Toolkit_v1_0
  - Pip_Rendering_Toolkit_README_v1_0
  - Pip_Comfort_Geometry_Atlas_Rendering_Specs_v1_1
  - Pip_Comfort_Geometry_Atlas_PNG_Generation_Plan_v1_1
  - Pip_Comfort_Geometry_Atlas_Asset_Manifest_v1_1

Non-Activation Clause:
  This README does not activate NDH geometry, governance altitude, diagnostic
  engines, emblem semantics, or narrative identity. All guidance remains
  expressive-layer, reversible, non-symbolic, and NDH-external.

Version: 1.0
Maintainer: Borealis S. Hedling
Location: Dublin, Ireland
Timestamp: 03 September 2026 — 22:45 IST
Seal: [ T O O L I N G • R E A D M E • v1_0 ]
---
