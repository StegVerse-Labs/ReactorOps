# ReactorOps

**ReactorOps** is the DiamondOps asset-lifecycle layer.

It exists to help synthetic crystal producers:
- keep expensive reactors running longer
- reduce downtime and scrap
- survive price compression
- avoid unnecessary capital replacement

ReactorOps is intentionally **vendor-agnostic** and **non-OEM-locked**.

---

## What ReactorOps Is

ReactorOps provides:
- inspection and risk classification
- maintenance and uptime frameworks
- retrofit planning and execution metadata
- refurbishment and resale grading
- downtime root-cause analysis

It does **not**:
- replace OEM documentation
- provide unsafe construction instructions
- control equipment directly

---

## Core Capabilities (v0.3)

### 🔍 Asset Inspection
Structured inspections captured as `asset_inspection_event` records:
- baseline / quarterly / annual
- prepurchase and resale
- post-incident assessments

Each inspection includes:
- risk rating (low / medium / high)
- findings and recommended actions
- evidence references (documents, photos, reports)

---

### 🔧 Maintenance & Downtime Analysis
ReactorOps standardizes:
- `maintenance_event` records
- `downtime_event` classification
- root-cause attribution

This allows:
- downtime trend analysis
- maintenance effectiveness review
- cross-asset comparison in YieldOS

---

### ♻️ Retrofit Lifecycle Tracking
Retrofits are tracked via `retrofit_event`:
- proposal → approval → execution → completion
- category (power, cooling, controls, vacuum, gas, safety)
- expected impact metadata (availability, downtime reduction)

This enables ROI-based retrofit decisions rather than guesswork.

---

### 🧰 Refurbishment & Resale Grading
Used assets are evaluated and graded:
- Grade A: low risk, documented history
- Grade B: moderate risk, remediation recommended
- Grade C: high risk, refurbishment required

ReactorOps provides:
- risk transparency
- asset value preservation
- safer secondary-market operation

---

## Integration with DiamondOps Platform

ReactorOps **emits metadata only**:
- no secrets
- no raw telemetry
- no facility-specific sensitive data

### Exported Events
- `maintenance_event`
- `downtime_event`
- `asset_inspection_event`
- `retrofit_event`

These are ingested by **YieldOS** for analytics and reporting.

---

## Why ReactorOps Matters Strategically

As diamond prices compress:
- new reactor purchases slow
- asset life extension becomes critical
- refurbishment demand increases

ReactorOps becomes **more valuable in downturns**, not less.

It is designed to:
- reduce stranded-asset risk
- support pivots to industrial and advanced materials
- operate across diamonds, sapphire, SiC, GaN, and future crystals

---

## Versioning & Compatibility

- ReactorOps aligns to **DiamondOps-Core v0.3.x**
- Changes are additive and backward-aware
- Service definitions evolve independently of Core schemas

---

## Status

- **v0.3**: fully wired to Core operational contracts
- Next: pricing SKUs, intake workflows, and YieldOS-driven benchmarking
