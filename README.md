# Fengzhe Li

Software Engineer focused on **backend, systems, cloud, and applied machine learning**.

I build backend and systems software where state, correctness, provenance, and failure boundaries matter — from process migration and event-driven cloud systems to FinTech platforms and applied ML. MSc Telecommunications, University College London (UCL).

Based in the UK · [Email](mailto:fengzheli048@gmail.com)

## Featured Projects

### [Cross-Machine Session Migration](https://github.com/fengzhe-li/cross-machine-session-migration)
Systems research on moving running computation and active TCP sessions across machines while preserving state and client-visible continuity. Covers Docker/CRIU checkpoint-restore (8/10 final trials), native CRIU (5/5), Telefork (5/5), and established-TCP restoration with floating-VIP handover (5/5).

### [Auditable Financial Research Agent](https://github.com/fengzhe-li/auditable-financial-research-agent)
An assurance layer for AI-assisted financial research enforcing controlled retrieval, an explicit state machine, deterministic independent claim validation, versioned governance policy, and a mandatory human review publication gate. Built with FastAPI, React/TypeScript, and Docker, with 437 backend tests and 27 frontend tests; unsupported-claim rate fell from 52% to 0% across the frozen 50-task deterministic benchmark.

### [Indy 500 Point-in-Time Decision Support](https://github.com/fengzhe-li/indy500-point-in-time-decision-support)
A point-in-time decision-support system for Indy 500 qualifying built around a frozen physics-conditioned probabilistic core with forecast-vintage provenance, fail-closed leakage control, uncertainty-aware inference, and evidence-aware abstention behind FastAPI and React/TypeScript. Evaluated across 15 external hybrid-era cases (MAE 0.492 mph); deliberately does not estimate queue waiting time or issue retain/withdraw decisions.

### [Financial Knowledge Intelligence Platform](https://github.com/fengzhe-li/financial-knowledge-intelligence-platform)
A production-style FinTech data platform for financial document ingestion, validation, duplicate detection, and run lineage. Built with FastAPI, PostgreSQL (with Alembic migrations), Qdrant vector retrieval, and Docker with Airflow-compatible orchestration. Implements deterministic cited retrieval by default, keeping optional LLM summarisation strictly inside the RAG layer.

### [Edge-to-Cloud IoT Event Platform](https://github.com/fengzhe-li/edge-to-cloud-iot-event-platform)
An event-driven AWS IoT backend (IoT Core, Lambda, API Gateway, DynamoDB, PostgreSQL) featuring retry-safe transactional event deduplication, timestamp-guarded state updates, and compare-and-swap alert handling. Verified with 102 local tests, including 15 real PostgreSQL and 4 DynamoDB-emulator integration tests; GitHub Actions runs the test suite with PostgreSQL and configuration checks.

### [Vehicle-Aware Human Fallback](https://github.com/fengzhe-li/vehicle-aware-human-fallback)
Braking-only recoverability and evidence-boundary analysis for Level 3 automated-driving takeovers. Audits the TU Delft D003 simulator dataset (513 trials, 57 drivers), showing that independent human driver braking cannot be identified from telemetry. Applies an interval-bounded braking model classifying 150 scenario cases into 58 robustly satisfied, 47 parameter-sensitive, and 45 robustly unsatisfied — within-model necessary-condition classifications, not safety labels.

## Additional Engineering Projects

**[STM32 Fall Detection System](https://github.com/fengzhe-li/stm32-fall-detection-system)**  
Embedded fall-detection prototype with MPU6050 sensor processing, GPS localization, and GSM/SMS alerting, originally demonstrated on physical STM32 hardware. The recovered and hardened C firmware has since been verified host-side using compiler and sanitizer checks.

**[Respiratory Audio AI Engineering Platform](https://github.com/fengzhe-li/respiratory-audio-ai-engineering-platform)**  
An engineered ML system refactored from an MSc research project: patient-independent, leakage-safe grouped evaluation, Mel-spectrogram CNN inference served via FastAPI, Docker packaging, and model-contract tests. Reports modest grouped-holdout performance honestly; not a clinical diagnostic tool.

**[Full-Stack Recommendation Platform — MeetEat](https://github.com/fengzhe-li/fullstack-recommendation-platform)**  
Full-stack group restaurant recommendation platform (React, TypeScript, FastAPI, PostgreSQL, SQLAlchemy/Alembic, Docker) where deterministic ranking controls recommendation order and voting workflows; optional AI explanations do not control ranking. Verified with Playwright accessibility tests and CI.

**[Job Intelligence Platform](https://github.com/fengzhe-li/job-intelligence-platform)**  
A multi-source job-search backend/data pipeline built on the Python standard library, featuring seven source connectors behind a shared interface, normalization, layered cross-source deduplication, evidence-backed capability matching, saved searches, and workflow tracking. PostgreSQL is defined as a schema contract.

<details>
<summary><strong>Earlier / lineage projects</strong></summary>

- **[Telecom Research Intelligence](https://github.com/fengzhe-li/telecom-research-intelligence)** — Automated batch document ingestion and keyword extraction pipeline for arXiv research papers; provided the initial architectural pattern later expanded into the Financial Knowledge Intelligence Platform.
- **[AWS IoT Smart Spill Detection System](https://github.com/fengzhe-li/aws-iot-smart-spill-detection-system)** — Original collaborative team IoT prototype using AWS IoT Core, Lambda, and DynamoDB; served as the starting baseline for the independently upgraded Edge-to-Cloud IoT Event Platform.

</details>

## Technical Focus

- **Languages:** Python · TypeScript · SQL · C / Embedded C
- **Backend & Distributed Systems:** FastAPI · PostgreSQL · SQLAlchemy · Alembic · Qdrant · REST APIs · State Machines · Event-Driven Architecture
- **Systems & Cloud:** Linux · Docker · AWS (IoT Core, Lambda, API Gateway, DynamoDB, SES) · CRIU · GitHub Actions CI
- **Applied ML & Data:** Probabilistic modelling · Uncertainty quantification · Information retrieval / RAG · Evaluation benchmarking · TensorFlow
