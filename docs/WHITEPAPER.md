# Technical Whitepaper — SPECKLE_SERVER

**Model:** PAX L5 Narrow L2 General 27B
**Company:** Anticloud FZ LLE
**Upstream:** https://github.com/specklesystems/speckle-server
**Category:** ARCHITECTURAL_DESIGN

## Abstract

This whitepaper describes the Anticloud integration of `SPECKLE_SERVER` (Architecture/engineering data platform)
with PAX L5 Narrow L2 General 27B, the offline-first AI model developed by Anticloud FZ LLE.
The integration produces a zero-cloud, single-binary deployment that exceeds upstream
capabilities while eliminating all third-party API dependencies.

## Technical Improvements

1. PAX L5 Narrow L2 General 27B local generative design and code compliance checking
2. AIOSS version chain for all design iterations with cryptographic proof
3. AES-256 encryption for client design files and proposals
4. Single-binary desktop tool replacing cloud-dependent design software
5. Offline rendering pipeline: ray tracing on local GPU without cloud render farm
6. GPU/CPU equalizer: full offline rendering from laptop CPU to workstation GPU
7. Zero-cloud client presentation: all assets served locally
8. Open format export: removes proprietary lock-in, outputs to IFC/DWG/PDF

## Architecture

See TECHNICAL/01_Architecture.md for the full architectural description.

## Benchmarks

See OFFICIAL_BENCHMARKS/04_PAX_Results.md for performance targets and measured results.