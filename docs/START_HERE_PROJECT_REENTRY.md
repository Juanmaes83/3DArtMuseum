# START HERE — PROJECT REENTRY

Status: **MASTER TRANSVERSAL TEMPLATE / REENTRY DOCTRINE / NOT A PROJECT-SPECIFIC EXECUTION ROADMAP**

Purpose: this document is designed to be copied into interactive-world repositories so that, when a project is resumed after weeks or months, the next AI/person understands the architectural doctrine **before** investing time in implementation or visual polish.

This document does **not** replace the local project's canonical roadmap, contracts or execution logs. It is the reentry gate that tells the reader how to think, what to protect and what to read next.

---

## 0. REENTRY INSTRUCTION

Before changing code, visuals or architecture:

1. Read this file completely.
2. Identify the local project's canonical `START_HERE`, roadmap or authority document.
3. Read only the active domain/phase documentation needed for the task.
4. Inspect the current branch / PR / execution state before acting.
5. Do not reopen historical decisions unless new evidence requires it.

If this template conflicts with an explicit, newer, project-specific approved decision, the newer approved local authority wins. Record the conflict before acting; do not silently choose one.

---

# 1. ORGANISM RULE

The current visual representation of a project must **never be confused with the permanent organism of the project**.

Every project should be understood through four layers:

```text
DNA
= purpose / identity / product thesis / non-negotiable rules

BRAIN
= semantics / state / content / POIs / product logic / progress / continuity / meaning

SKELETON
= runtime / navigation / movement / collision / camera / interaction engine / pathfinding / anchors / authority boundaries

SKIN
= meshes / GLB / GLTF / materials / textures / vegetation / props / lighting / atmosphere / sound / post-processing / visual UI
```

The project may change SKIN dramatically while remaining the same organism.

The project must not lose DNA, BRAIN or SKELETON merely because its visual body evolves.

---

# 2. SNAKE-SKIN INVARIANT

Design all new work knowing that the current visual layer may be replaced later.

A valid future skin migration may replace rendered geometry, models, materials, vegetation, props, lighting, atmosphere, audio presentation, visual UI treatment, LOD/render strategy and art direction.

A skin migration must **not silently replace or corrupt** semantic IDs, entity identity, state, POI/progress meaning, authoritative transforms, navigation/collision contracts, interaction descriptors, anchors, camera/movement authority, user continuity or product/business logic.

The operation is **skin migration**, not world replacement.

---

# 3. CURRENT VISUALS ARE ALLOWED TO BE PROVISIONAL

Procedural geometry, low-poly assets, primitives and placeholders remain valuable for blockout, semantic/collision proxies, interaction testing, layout, authoring, debug, fallback/LOD and early UX validation.

They are **not automatically final art**.

Do not spend large amounts of time or money polishing a provisional layer when the underlying brain, skeleton, engine, usability or interaction model is still unstable.

---

# 4. PRIORITY RULE

```text
1. DNA / PRODUCT THESIS
2. BRAIN / SEMANTICS / STATE
3. SKELETON / ENGINE / USABILITY
4. SKIN / FINAL VISUAL FIDELITY
```

Visual research may proceed, but avoid mass visual production before structural gates are stable.

---

# 5. UNIVERSAL EXECUTION METHOD

```text
FREEZE MOTHER BASELINE
→ ARCHAEOLOGY
→ QUARRY MAP / EXACT STONES
→ ISOLATED SCULPTURE
→ COMPATIBILITY GATE
→ MINIMAL INTEGRATION SEAM
→ POST-INTEGRATION SURGERY / PERSONALIZATION
→ FUNCTIONAL + VISUAL + PERFORMANCE + REGRESSION VALIDATION
→ HUMAN APPROVAL
→ PROMOTE COMPLETE IMPLEMENTATION
```

Core rule: proven donor stone > reinventing from scratch; exact useful stone > importing an entire donor; reuse/adapt/minimal seam > parallel replacement system.

---

# 6. DONOR-FIRST RULE

Before building from zero, inspect the current project, the ecosystem and external donors. A donor is a quarry, not automatically a new mother architecture. Preserve provenance and license constraints.

---

# 7. VISUAL DECOUPLING RULE

Business logic, semantics and interactions should not depend unnecessarily on a concrete visual asset. Visual filenames are representation details, not semantic identity.

---

# 8. SKIN-READINESS CHECK

When resuming a project, ask:

> **If we removed today's meshes/materials/visual assets, would the project still know what everything is and how it behaves?**

If NO, identify coupling before expanding the project. Record debt; do not necessarily refactor everything immediately.

---

# 9. FUTURE VISUAL BINDING DIRECTION

```text
SEMANTIC ENTITY
→ VISUAL BINDING
→ CURRENT SKIN
```

The exact implementation may differ by project. The invariant is separation.

---

# 10. ASSET / CODE PROVENANCE

Before production adoption, record source, creator/provider, license, attribution, format, semantic role, optimization history and restrictions as applicable.

---

# 11. PROJECT-SPECIFIC REENTRY BLOCK

```text
PROJECT NAME: 3DArtMuseum
PROJECT PURPOSE / DNA: simple Three.js art-museum/gallery experience with artwork placement, audio and text-description insertion functions.
MOTHER / BASE RUNTIME: this repository is a reference implementation; do not assume it is the future Museum mother product.
CURRENT PRIORITY: preserve the content-placement/interaction idea; no large visual investment before deciding future museum architecture.
CURRENT ACTIVE PHASE: dormant/reference unless a newer local authority says otherwise.
CURRENT SKIN CLASSIFICATION: reference/provisional.
LOCAL CANONICAL START_HERE: README.md
LOCAL ACTIVE ROADMAP: VERIFY ON REENTRY; none is assumed from the current README.
DO NOT REOPEN / DO NOT TOUCH: do not treat source geometry/assets as product truth; verify provenance/license before reusing code or media.
NEXT VALIDATION GATE: museum-family reentry audit before selecting any mother or donor role.
```

Keep this block concise. It is a reentry snapshot, not a second roadmap.

---

# 12. WHAT TO READ AFTER THIS FILE

Read this file, then the local canonical start/README, then only the active roadmap/domain contract/log needed for the task. Historical documentation is evidence, not active authority.

---

# 13. DOCUMENTATION DISCIPLINE

Default: **UPDATE EXISTING CANONICAL DOCUMENT > CREATE NEW DOCUMENT**. Mark historical/superseded documents explicitly.

---

# 14. AI / AGENT BEHAVIOR ON REENTRY

Preserve the mother/base unless explicitly authorized otherwise; identify current branch and authority before writes; separate Brain/Skeleton/Skin; treat current visuals as replaceable unless explicitly approved final; avoid large visual investment while structural gates are open; search donor stones before rewriting; validate high-risk capabilities in isolation; preserve provenance/licenses; never claim visual approval from compilation/tests alone.

---

# 15. HUMAN APPROVAL RULE

Functional/runtime/performance/regression PASS does not automatically equal **FINAL VISUAL APPROVAL**. Human approval remains required.

---

# 16. CORE MEMORY

> **Build the organism so well that it can change skin without losing its DNA, brain, bones, memory or movement.**

> **Do not spend final-art effort on a skin that the architecture already expects to shed.**

---

## Template governance

This file is the universal reentry template. Project-specific copies may add their local reentry block and references, but should not silently weaken the organism/skin-migration doctrine.