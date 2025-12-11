Cross-Model Evaluation Archive

EntityWorks — Machine-Facing Pages / Machine-Facing Page Declaration (MFP / MFPD)
Archive Root: cross-model-evaluations/

Purpose of This Archive
This directory contains the complete, timestamped history of how multiple AI models interpret EntityWorks publications over time.
It serves four critical roles:

Interpretive Convergence Tracking
Monitoring how different models converge or diverge in their understanding of EntityWorks definitions, terminology, and frameworks.

Provenance and Evidence Preservation
Providing cryptographically timestamped records demonstrating early origin, stability, and clarity of the EntityWorks Standard.

Regulatory and Audit Utility
Offering an independently verifiable trail of how external AI systems represented EntityWorks’ work at specific points in time.

Long-Term Scientific Record
Forming part of the discipline-wide history of AI Perception and machine-interpretation dynamics.

This archive is non-normative: it records model behaviour, but does not constitute guidance or official interpretation.

Directory Structure
Each model receives its own directory:

cross-model-evaluations/
claude/
gemini/
gpt/

Within each model directory, individual evaluation events are stored in date-named folders:

claude/
2025-12-11_Model_Check/
2026-01-04_WhitePaper_Evaluation/

Each event folder contains:

ZIP archive (all screenshots)

OTS timestamp (.ots) for ZIP

Raw PNG screenshots

README.md describing the evaluation
This ensures clarity, scalability, and reproducibility.

Contents of Each Event Folder
Every event folder MUST include:

Screenshots (full visual capture of model output)

ZIP archive (packaged screenshots)

OpenTimestamps (.ots) file (cryptographic proof)

Event README (purpose, methodology)

Optional additions:

Raw text output (.txt)

Notes on unusual behaviour

Comparative observations

Methodology (Standardised)
All model evaluations follow this process:

A full EntityWorks document is pasted verbatim into the model.

The entire output is captured via sequential screenshots.

Screenshots are archived into a ZIP file.

The ZIP is timestamped with OpenTimestamps.

All artefacts are stored in a dated event folder.

A README describes the evaluation.

Everything is committed to GitHub for version-proof provenance.

Notes and Guidance

Evaluation folders use YYYY-MM-DD_Description format.

Model folders are lowercase: claude, gemini, gpt.

Evaluations should be run across multiple models for convergence tracking.

This archive forms a key part of the provenance chain for the EntityWorks Standard.

Long-Term Purpose
This archive will eventually demonstrate:

discipline origin

definition stability

early cross-model interpretive alignment

machine comprehension of AI Perception terminology over time

It supports researchers, auditors, regulators, and future publications.

© EntityWorks. All rights reserved.