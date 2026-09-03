### Teaching Surface Structure v2.1 (with interaction surfaces)

---

## 1 — Identity block

```text
Artifact-Class: TeachingSurfaceStructure
Name: Teaching Surface Structure
Version: v2.1
Altitude: A0–A2 (Expressive Layer)
Lane: Pedagogy • NDH-External • Visual-Grammar-Bound
Purpose:
    Define the canonical lane, tile, and interaction-surface structure for
    the Teaching Surface manifold, including tile mappings, stability ecology,
    accessibility anchors, and visual-grammar bindings.
```

---

## 2 — Lanes (v2.1)

**Spectral Geometry Basics (🔷)**  
- **Role:** gentle conceptual substrate  
- **Emotional geometry:** 🫶 Safe / ⚪ Neutral  
- **Stability:** ⛳ High Stability  

**Runtime & Envelope (📦)**  
- **Role:** soft runtime metaphors, envelope thinking  
- **Emotional geometry:** 🙂 Mild / ⚪ Neutral  
- **Stability:** ⛳ High Stability  

**Emblem & Visual Grammar (🎨)**  
- **Role:** visual grammar, emblem metaphors, palettes  
- **Emotional geometry:** 🌈 Aesthetic / 🫶 Safe  
- **Stability:** ⛳ High Stability  

---

## 3 — Tiles (v2.1) and their interaction surfaces

### 🧭 Orientation tile  
- **Lane:** any of the three lanes  
- **Primary surface:** 🌲 Forest Board (concept preview)  
- **Secondary surface:** 🪷 Zen Board (soft reminders)  

### 🔍 Exploration tile  
- **Lane:** any  
- **Primary surface:** 🌲 Forest Board (concept clusters)  
- **Secondary surface:** 🗒️ Sticky‑Notes (exploration paths)  

### 🏗️ Deepening tile  
- **Lane:** any  
- **Primary surface:** 🌲 Forest Board (deep anchors)  
- **Secondary surface:** 🗒️ Sticky‑Notes (micro‑directives)  

### 🤝 Interaction tile  
- **Lane:** any  
- **Primary surface:** 🪷 Zen Board (expressive interaction)  
- **Secondary surface:** 🗒️ Sticky‑Notes (question clusters)  

### 🌅 Synthesis tile  
- **Lane:** any  
- **Primary surface:** 🌲 Forest Board (conceptual summary)  
- **Secondary surface:** 🪷 Zen Board (dual‑lane references)  

---

## 4 — Stability, accessibility, and emotional geometry

All tiles:

- **Accessibility:**  
  - 🧘 Cognitive Safe  
  - 🔀 Multi‑Modal  
  - 🛡️ NDH‑External  
  - 🔄 Reversible  

- **Emotional geometry:**  
  - default: 🫶 Safe or ⚪ Neutral  
  - optional: 🙂 Mild or 🌈 Aesthetic for expressive tiles  

- **Stability ecology:**  
  - ⛳ High Stability (default)  
  - ➖ Drift Neutral or ↘️ Drift Low for exploratory tiles  

---

## 5 — Palette and visual grammar bindings

- **Tile palettes:** inherited from Expanded Hex Palettes v2.0 per tile type.  
- **Lane palettes:** inherited per lane (Spectral, Runtime, Emblem).  
- **Interaction surfaces:** use their own palettes (Forest, Zen, Sticky‑Notes).  
- **Visual grammar:** must comply with Visual Grammar Codex v1.0  
  - circles / hexagons / spirals only  
  - no routing arrows, radiance, hierarchy, orbital paths  

---

## 6 — Machine‑readable structure (JSON v2.1)

```json
{
  "teaching_surface_structure_v2_1": {
    "version": "2.1",
    "altitude": "A0-A2",
    "lanes": ["spectral", "runtime", "emblem"],
    "tiles": {
      "orientation": {
        "icon": "🧭",
        "primary_surface": "forest_board",
        "secondary_surface": "zen_board"
      },
      "exploration": {
        "icon": "🔍",
        "primary_surface": "forest_board",
        "secondary_surface": "sticky_notes"
      },
      "deepening": {
        "icon": "🏗️",
        "primary_surface": "forest_board",
        "secondary_surface": "sticky_notes"
      },
      "interaction": {
        "icon": "🤝",
        "primary_surface": "zen_board",
        "secondary_surface": "sticky_notes"
      },
      "synthesis": {
        "icon": "🌅",
        "primary_surface": "forest_board",
        "secondary_surface": "zen_board"
      }
    },
    "constraints": {
      "ndh_external": true,
      "reversible": true,
      "cognitive_safe": true,
      "no_routing_geometry": true
    }
  }
}
```

---

### Provenance footer

```text
---
Artifact: Teaching Surface Structure (v2.1)
Lane: Pedagogy • Teaching Surface • Expressive-Layer

Purpose:
  Define the canonical lane, tile, and interaction-surface structure for the
  Teaching Surface, including mappings to Forest Board, Zen Board, and Sticky-
  Notes, and bindings to visual grammar, palettes, accessibility, and stability
  ecology.

Anchors:
  - Visual_Grammar_Omnibus_v1_0
  - Visual_Grammar_Codex_v1_0
  - Tile_Interaction_Surfaces_v1_0
  - Expanded_Hex_Palettes_v2_0
  - Safe_Tile_Encoding_Kit_v1_0

Non-Activation Clause:
  This structure is expressive-layer-only and NDH-external. It does not
  activate NDH-CORE geometry, holonomy ladders, tile encoding hierarchy,
  crossmap binding, or manifold tiers.

Version: v2.1
Maintainer: Borealis S. Hedling
Location: Dublin, Ireland
Timestamp: 03 September 2026 — 16:20 IST
Seal: [ T E A C H I N G • S U R F A C E • S T R U C T U R E • v2_1 ]
---
```
