# Lombardia Verde Idrogeno — Asset Lifecycle Platform Demo

Interactive prototype demonstrating an integrated asset lifecycle workflow across four vendor systems for a 100 MW green hydrogen plant facing a fleet-wide PEM electrolyzer contamination event.

## Story arc

**AVEVA CONNECT** (Monitor) → **Resolve Predict** (Diagnose & Prescribe) → **IFS Cloud** (Execute) → **Copperleaf** (Optimize)

The demo walks through a 22:1 consequence event: a deferred €50K resin replacement causing €4.5M in downstream membrane damage across 20 modules — and shows how the four systems together would have caught it, routed action across three lanes (emergency O&M, capital through portfolio optimization, conditional budget for lower-confidence diagnoses), and adapted the capital plan as new data arrived.

## Stack

Single-file static HTML. React 18, Recharts, Tailwind (via CDN). No build step required.

## Theme

Includes a light/dark theme toggle (top right of the toolbar). Light mode uses the NxB Predict palette; dark mode uses the IFS / AVEVA charcoal-navy aesthetic.

## Deploy

Drop into any static host. For Vercel: New Project → Import → Deploy (no build settings needed).

---

Demo prototype — synthetic data, for IFS + AVEVA storyboard illustration only.
