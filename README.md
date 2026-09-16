# Fengzhe Li

Software Engineer focused on **backend, systems, cloud, and applied machine learning**.

I build engineering systems that connect research, infrastructure, and production-style software — from cross-machine process migration and probabilistic motorsport decision support to FinTech data platforms, full-stack applications, ML services, and event-driven cloud systems.

Currently based in the UK (MSc, University College London), and interested in software engineering roles across backend, platform, cloud, applied ML, and motorsport technology.

## Selected Projects

### 🏁 [Indy 500 Point-in-Time Probabilistic Decision Support System](https://github.com/fengzhe-li/indy500-point-in-time-decision-support)

A physics-conditioned probabilistic decision-support system for Indianapolis 500 qualifying, built through an identifiability-driven research process. Point-in-time leakage control, forecast-vintage provenance, Monte Carlo uncertainty propagation, evidence-aware abstention, and historical shadow replay sit behind a FastAPI application layer and a React/TypeScript pit-wall interface, packaged with Docker and CI, with frozen scientific assets and immutability checks.

The system estimates `p(Δv | H = h)` — conditional physical-performance change given a future opportunity horizon. It does **not** estimate `P(H = h)`, does not predict queue waiting time, and does not directly recommend a retain/withdraw strategy. Human-in-the-loop by design.

### 🔀 [Cross-Machine Session Migration](https://github.com/fengzhe-li/cross-machine-session-migration)

A systems research project exploring how running computation and active TCP sessions can move across machines while preserving state and client-visible continuity — Docker + CRIU checkpoint/restore, native CRIU, Telefork, established-TCP restoration, and floating-VIP handover, validated through repeated experimental runs. My strongest systems/networking project.

### 💹 [Financial Knowledge Intelligence Platform](https://github.com/fengzhe-li/financial-knowledge-intelligence-platform)

A production-style FinTech backend and data platform for ingesting, validating, indexing, searching, and analysing financial documents — FastAPI, PostgreSQL, Qdrant, and Airflow-compatible orchestration, containerised with Docker and Alembic-managed migrations, with explicit data quality and lineage tracking and deterministic cited retrieval plus optional RAG summarisation. My strongest backend / FinTech / data-platform project.

## Other Projects

**[Full-Stack Recommendation Platform — MeetEat](https://github.com/fengzhe-li/fullstack-recommendation-platform)**
Full-stack group restaurant recommendation platform (React, TypeScript, FastAPI, PostgreSQL, SQLAlchemy/Alembic) with deterministic ranking logic and voting workflows — AI is used for explanation only, never for ranking control — with Playwright accessibility testing and GitHub Actions CI.

**[Respiratory Audio AI Engineering Platform](https://github.com/fengzhe-li/respiratory-audio-ai-engineering-platform)**
An MSc respiratory-sound classification project refactored into a complete ML engineering system: patient-independent, leakage-safe evaluation, TensorFlow CNN inference served via FastAPI, Docker packaging, model-contract tests, and an optional LLM reporting layer. Reports modest grouped-holdout performance honestly; not a clinical diagnostic tool.

**[Edge-to-Cloud IoT Event Platform](https://github.com/fengzhe-li/edge-to-cloud-iot-event-platform)**
Event-driven AWS IoT backend (IoT Core, Lambda, API Gateway, PostgreSQL, DynamoDB) for sensor ingestion, state management, operational analytics, alert handling, and remote actuation, with retry-safe event deduplication, compare-and-swap alert handling, and integration tests in CI. Not exactly-once delivery, and not claimed production-ready.

**[Job Intelligence Platform](https://github.com/fengzhe-li/job-intelligence-platform)**
A personal job-search system turned backend/data-engineering portfolio project: seven-source ingestion behind a shared connector abstraction, layered cross-source deduplication, evidence-backed candidate capability profiling, explainable ranking, saved searches, workflow tracking, source health, and freshness-aware views. PostgreSQL is currently a schema contract, not yet wired in.

**[STM32 Fall Detection System](https://github.com/fengzhe-li/stm32-fall-detection-system)**
Embedded fall-detection prototype built around STM32 firmware, sensor processing, and GSM/SMS communication, originally demonstrated on physical hardware. The recovered and hardened firmware has since been validated with host-side compiler and sanitizer testing.

**[Telecom Research Intelligence](https://github.com/fengzhe-li/telecom-research-intelligence)**
An earlier document-intelligence pipeline for collecting, extracting, structuring, and summarising telecom research papers — part of the design lineage behind the Financial Knowledge Intelligence Platform above.

**[AWS IoT Smart Spill Detection System](https://github.com/fengzhe-li/aws-iot-smart-spill-detection-system)**
An earlier collaborative team project using AWS IoT Core, Lambda, API Gateway, PostgreSQL, DynamoDB, and SES for spill-sensor monitoring. Later became the starting point for my independently upgraded [Edge-to-Cloud IoT Event Platform](https://github.com/fengzhe-li/edge-to-cloud-iot-event-platform).

## Technical Focus

**Languages:** Python · TypeScript · SQL · C / Embedded C
**Backend & Data:** FastAPI · PostgreSQL · SQLAlchemy · Alembic · Qdrant · REST APIs
**Systems & Cloud:** Linux · Docker · AWS · CRIU · GitHub Actions
**ML / AI:** Probabilistic modelling · uncertainty quantification · TensorFlow · RAG · model serving
**Frontend:** React · TypeScript · Vite

## Interests

Backend Engineering · Distributed Systems · Platform Engineering · Cloud · Applied ML · Motorsport Technology
