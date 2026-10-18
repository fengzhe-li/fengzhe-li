# Fengzhe Li

**Software Engineer · Applied AI · Backend & Systems**

I build Python services, evidence-grounded AI workflows and systems tools, with an emphasis on testing, data provenance and reproducible evaluation. My work spans LLM research agents, retrieval-augmented applications, vision-language model integration, audio classification and Linux process migration.

Based in the UK · MSc Telecommunications, UCL · [Email](mailto:fengzheli048@gmail.com)\
Seeking **Graduate / Junior Software Engineering** roles across Python backend, applied AI, full-stack/cloud, and automotive or motorsport software.

**Start here:** [Interactive automotive demo](https://fengzhe-li.github.io/vehicle-aware-human-fallback/) · [Backend & RAG platform](https://github.com/fengzhe-li/financial-knowledge-intelligence-platform) · [Systems experiments](https://github.com/fengzhe-li/cross-machine-session-migration)

## Featured Projects

### 1. [Cross-Machine Session Migration](https://github.com/fengzhe-li/cross-machine-session-migration)

Experimental migration of running processes and established TCP sessions using **Docker/CRIU**, native CRIU and floating-VIP handover. Shell orchestration, Python clients and recorded source/target evidence distinguish preserved process state from client-visible session continuity. Includes reproduction and validation of the upstream Telefork approach.

**Linux · Python · Bash · Docker · CRIU · TCP/IP**\
Results are bounded to the tested compatible environments; container checkpoint failures remain documented. [Experiment evidence](https://github.com/fengzhe-li/cross-machine-session-migration/blob/main/docs/EXPERIMENT_EVIDENCE.md)

### 2. [Auditable Financial Research Agent](https://github.com/fengzhe-li/auditable-financial-research-agent)

An LLM-assisted research workflow with controlled retrieval, explicit state transitions, independent deterministic citation validation, versioned governance and human approval gates. The React assurance console exposes evidence, claim revisions and review decisions; backend/frontend tests and Docker builds run in CI.

**Python · FastAPI · React / TypeScript · Docker**\
Evaluation uses frozen synthetic tasks; citation checks do not establish general semantic truth or production compliance. [Validation methodology](https://github.com/fengzhe-li/auditable-financial-research-agent/blob/main/docs/PHASE_6_5_REAL_MODEL_REPORT.md)

### 3. [Financial Knowledge Intelligence Platform](https://github.com/fengzhe-li/financial-knowledge-intelligence-platform)

A financial-document ingestion and **RAG** platform with validation, duplicate detection, PostgreSQL metadata and run lineage, Qdrant retrieval, and a React research workspace. Answers expose source passages and citations. Extractive answers are the default; optional LLM summarisation stays behind the retrieval interface.

**Python · FastAPI · PostgreSQL · Qdrant · React / TypeScript · Docker**\
Includes API, pipeline and browser tests. Raw documents use local object storage; the packaged MinIO service is not an implemented storage adapter.

### 4. [Vehicle-Aware Human Fallback](https://github.com/fengzhe-li/vehicle-aware-human-fallback)

Integrates pretrained **AutoVLA / Qwen2.5-VL** with independent trajectory checks and a braking-only human-fallback model. A separate **YOLO11n** extension adds reproducible 2D perception experiments and read-only comparison with saved VLA results. Includes an interactive browser demonstrator, provenance checks and offline verification in CI.

**Python · PyTorch · Transformers · Computer Vision**\
Recorded open-loop predictions and model-based necessary conditions—not validated autonomous-driving safety. [Demo](https://fengzhe-li.github.io/vehicle-aware-human-fallback/) · [YOLO extension](https://github.com/fengzhe-li/vehicle-aware-human-fallback/tree/main/extensions/yolo_perception)

### 5. [Indy 500 Racing Point-in-Time Decision Support](https://github.com/fengzhe-li/indy500-racing-point-in-time-decision-support)

A **FastAPI + React/TypeScript** application for point-in-time qualifying analysis, combining physical modelling, forecast-vintage provenance, historical replay and evidence-aware abstention. Keeps hypothetical scenarios separate from historical evidence, with documented external validation and reproducibility boundaries.

**Python · Probabilistic Modelling · FastAPI · React / TypeScript**\
Does not infer unsupported queue waiting times or issue retain/withdraw recommendations. [Application](https://github.com/fengzhe-li/indy500-racing-point-in-time-decision-support/tree/main/v3_point_in_time) · [Validation](https://github.com/fengzhe-li/indy500-racing-point-in-time-decision-support/blob/main/docs/validation.md) · [Earlier project URL](https://github.com/fengzhe-li/indy500-point-in-time-decision-support)

### 6. [Respiratory Audio AI Engineering Platform](https://github.com/fengzhe-li/respiratory-audio-ai-engineering-platform)

Refactors an MSc audio-classification project into a reusable **Mel-spectrogram CNN** pipeline with FastAPI inference, Docker packaging and model-contract tests. Patient-independent grouped evaluation keeps patients and augmented cycles separate, exposing the limitations of the original sample-level split. Optional LLM reporting is separate from prediction.

**Python · TensorFlow / Keras · librosa · FastAPI · Docker**\
Grouped-holdout performance is modest and variable; this is an engineering/research prototype, not a clinical diagnostic tool.

### 7. [Edge-to-Cloud IoT Event Platform](https://github.com/fengzhe-li/edge-to-cloud-iot-event-platform)

An event-driven backend around **AWS IoT Core**, **Lambda** and **API Gateway** with transactional retry deduplication, timestamp-guarded state updates, compare-and-swap alerting and read-only operational analytics across PostgreSQL and DynamoDB. Verified with 102 local tests (including real PostgreSQL and DynamoDB-emulator integration tests) and GitHub Actions CI.

**Python · AWS IoT Core · Lambda · API Gateway · PostgreSQL · DynamoDB**\
Evolved from the original collaborative IoT prototype; remote IoT actuation publish is disabled by default and fire-and-forget. [Engineering design](https://github.com/fengzhe-li/edge-to-cloud-iot-event-platform/blob/main/docs/ENGINEERING.md)

## Additional Engineering Projects

- **[NFL QB Pressure Replay](https://github.com/fengzhe-li/nfl-qb-pressure-replay)** — Interactive tracking-data replay, kinematic analysis and public **Qwen2.5-VL** evaluation against independent tracking ground truth. The published implementation analyses rendered replay frames; it does not claim a video detector/tracker extension.
- **[Job Intelligence Platform](https://github.com/fengzhe-li/job-intelligence-platform)** — Multi-source ingestion, deduplication, explainable matching and evidence-backed CV generation. The [published feature-branch release](https://github.com/fengzhe-li/job-intelligence-platform/tree/592abeb21750ea100d10966d126d698ec5dfa919) adds JD lexical alignment, repository evidence mapping and supervised browser handoff; it is not yet merged into `main`. Private candidate data stays local and final submission remains human-controlled.
- **[MeetEat — Full-Stack Recommendation Platform](https://github.com/fengzhe-li/fullstack-recommendation-platform)** — React/TypeScript, FastAPI and PostgreSQL group recommendations and voting. Deterministic ranking controls results; optional AI explains them. Includes browser tests and CI.
- **[STM32 Fall Detection System](https://github.com/fengzhe-li/stm32-fall-detection-system)** — Embedded C sensor processing, GPS and GSM/SMS alerts. Historical physical-prototype evidence is distinguished from host-side checks of the current firmware.

## Technical Focus

- **Backend:** Python, FastAPI, PostgreSQL, SQLAlchemy/Alembic, REST APIs and state machines.
- **Applied AI:** LLM agents, evidence-grounded workflows, RAG/Qdrant, PyTorch, Qwen2.5-VL/AutoVLA integration, YOLO11n, TensorFlow/Keras CNNs and evaluation design.
- **Full-stack & cloud:** React, TypeScript, Docker, AWS IoT Core, Lambda, API Gateway and DynamoDB.
- **Systems & quality:** Linux, CRIU, TCP/IP, automated tests, GitHub Actions CI, provenance auditing and reproducible experiments.

<details>
<summary><strong>Earlier projects and engineering lineage</strong></summary>

- [Telecom Research Intelligence](https://github.com/fengzhe-li/telecom-research-intelligence) — arXiv document ingestion and keyword/report generation; an earlier foundation for the financial knowledge platform.
- [AWS IoT Smart Spill Detection](https://github.com/fengzhe-li/aws-iot-smart-spill-detection-system) — Original collaborative IoT prototype, retained separately from the upgraded event platform.
- [IoT Sensor Data Analysis](https://github.com/fengzhe-li/iot-sensor-data-analysis) — Python time-series exploration and threshold-based anomaly analysis.
- [Cycling Business Analysis](https://github.com/fengzhe-li/cycling-business-analysis-sql-tableau) — PostgreSQL analysis and Tableau dashboards.
- [Customer Revenue Analytics](https://github.com/fengzhe-li/End-to-End-SQL-Data-Analysis-Movie-Renting-Dataset) — SQL Server rental-data analysis and Power BI reporting.
- [Retail Sales Analytics](https://github.com/fengzhe-li/retail-sales-analytics-dashboard) — SQL KPI analysis and dashboard reporting.

</details>
