# Angelos Fikias

Platform engineer focused on cloud-native infrastructure, automation, and scalable system architecture. I design and build platforms for high reliability, performance, and long-term evolution - end to end.

## Stack

![Kubernetes](https://img.shields.io/badge/Kubernetes-326CE5?style=for-the-badge&logo=kubernetes&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0089D6?style=for-the-badge&logo=microsoftazure&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=githubactions&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)

## Connect

[![Portfolio](https://img.shields.io/badge/Portfolio-angelosfikias.dev-000000?style=for-the-badge&logo=google-chrome&logoColor=white)](https://angelosfikias.dev/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/angelos-fikias/)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:angelosfikias@gmail.com)

---

## Currently · Associate Platform Engineer at Dataviva

- 🧪 Built a distributed E2E browser load testing platform on Kubernetes - real Playwright sessions at scale, deployed to production
- 🚀 Own CI/CD pipelines, Docker deployments, and cloud-native infrastructure on Kubernetes and Azure
- 📊 Drive observability with Prometheus, Grafana, and SQLite-backed regression tracking

---

## Projects

### ⚙️ Platform & DevOps Engineering

#### [Cloud-Native Browser Load Testing Platform](https://github.com/AngelosFikias0) · *Dataviva*

Built the first distributed E2E load testing platform to run real Playwright browser sessions at scale on Kubernetes - replacing synthetic HTTP simulation with actual end-user workflows under full parallel load, orchestrated via Artillery. Owned the project end-to-end: architecture, implementation, client delivery, and production rollout.

Architected a two-layer system: an internal orchestration layer and a client-facing in-pod runtime, both delivered independently. The orchestration layer manages Kubernetes Job lifecycle with exact VU auto-splitting, wave-based execution with pre-flight quota enforcement, and CSV-driven batch injection with row packing - across six configurable load profiles (Fixed, Rate, Ramp, Spike, ConstantVU, SingleRun). Test campaigns are defined declaratively in YAML with per-step flow control, delay, and failure handling. A dry-run mode validates configuration and cluster quota before committing to execution. Production environment handling is built-in - proxy configuration, in-cluster DNS resolution, and namespace-aware RBAC are managed automatically across environments.

The test generator applies 35+ framework-aware transformation rules to raw Playwright recordings, producing reliable, load-ready scripts for Angular SPAs. It is backed by a Python engine and a structured JSON knowledge base: fixable patterns are transformed automatically; patterns that can't be resolved programmatically are rewritten with root cause and actionable guidance for the tester. A visual verification suite wraps every test with automatic video capture, headed/headless auto-detection, and artifact retrieval commands for remote K8s runs. A standalone zero-dependency reporting engine produces HTML dashboards with Canvas charts, machine-readable JSON with exit codes, and formatted plain text - running identically across local, CI, Kubernetes, and terminal environments.

A native desktop GUI handles test execution, live log streaming, process management, and artifact retrieval. Each run gets isolated log directories, structured JSONL indexing, and full artifact output stored in object storage or on-system. Metrics flow through Prometheus Pushgateway with a ServiceMonitor, visualized in Grafana, and persisted in a SQLite trend store for regression tracking. Jobs run in security-hardened pods - non-root, capability-dropped, seccomp-enforced.

Extended with a Helm-based environment lifecycle operator for autonomous namespace management. Implements cluster-aware auto-discovery across four lookup strategies - registry, Helm release scan, namespace probe, and literal match - so operators work without hardcoded cluster assumptions. Supports full lifecycle operations: provision, status, destroy, and cleanup, with GUI-confirmed destructive actions and masked credential entry. Environments are tracked via live directory watching with auto-refresh.

The client-facing image and test scripts are built and published automatically via GitHub Actions to Azure Container Registry, enabling air-gapped and production deployments with zero manual intervention.

Deployed to production to stress test the platform to its absolute limits - the highest concurrent real-browser VU count ever run on the system.

**Stack:** `Python` `Artillery` `Playwright` `Kubernetes` `Helm` `Docker` `Azure Container Registry` `Prometheus` `Grafana` `MinIO` `SQLite` `GitHub Actions` `JavaScript`

---

### 🏗️ Enterprise & System Architecture

#### [EfficienCity RMS - Municipal Resource Management System](https://github.com/AngelosFikias0/Resource_Management_System)

Enterprise-grade municipal resource management platform, designed end-to-end from stakeholder analysis through cloud architecture, enabling inter-municipality asset sharing, real-time inventory tracking and citizen-facing transparency.

- Led full systems analysis across the complete SDLC: stakeholder mapping, BPMN AS-IS/TO-BE modeling, Root Cause Analysis, SWOT, and MoSCoW prioritization
- Designed a microservices system on Azure AKS with Kafka event-driven communication, multi-layer data pipeline across PostgreSQL and ClickHouse, and immutable audit ledger ensuring 100% transaction traceability and GDPR compliance
- Delivered a React + TypeScript MVP across three role-based interfaces (Citizen, Municipal Employee, Administrator), designed in Figma with full UX journey documentation

**Stack:** `React` `TypeScript` `Spring Boot` `PostgreSQL` `ClickHouse` `Kafka` `Docker` `Azure AKS` `BPMN` `Figma`

#### [SafeCar Insurance Management System](https://github.com/AngelosFikias0/Safe_car_insurance_System)

Enterprise insurance platform managing full policy lifecycle from proposals through claims. Applied TOGAF and Zachman frameworks to align software architecture with business strategy. Modeled workflows via BPMN and UML end-to-end.

**Stack:** `Java` `UML` `BPMN` `TOGAF` `Zachman` `Figma`

---

### 📡 Distributed Systems & Backend

#### [Java Network Services Hub](https://github.com/AngelosFikias0/Java_Network_Services_Hub)

Multi-protocol distributed service framework supporting HTTP, TCP, UDP, and RMI communication. Implements concurrent request handling with thread pooling and a Swing-based orchestration interface for unified service management.

**Stack:** `Java` `Multi-threading` `Sockets` `RMI` `PostgreSQL` `Distributed Systems`

#### [TikiPark - Smart Android Parking Application](https://github.com/AngelosFikias0/TikiPark)

Offline-first Android parking app with real-time slot synchronization, Google Maps integration, and SQLite caching for full network resilience. Modular backend with RBAC and RESTful APIs ready for payment gateway extension.

**Stack:** `Java` `Android SDK` `PHP` `MySQL` `SQLite` `Google Maps API` `REST`

---

### 🔍 Data Engineering & Analytics

#### [Crime Intelligence Platform](https://github.com/AngelosFikias0/Crime_Management_System)

Graph-based investigative intelligence platform using the JUNG library and advanced graph theory. Computes centrality metrics (betweenness, closeness, degree) to identify key suspects and uncover criminal relationship patterns.

**Stack:** `Java` `JUNG` `Graph Theory` `Swing` `Data Visualization` `MVC`

#### [Data Structures & Algorithms Library](https://github.com/AngelosFikias0/Data_Structures_and_Algorithms)

Comprehensive implementation library covering BST, AVL trees, graphs, hash tables, heaps, sorting, searching, dynamic programming, and graph traversal — with complexity analysis and performance benchmarking.

**Stack:** `Java` `Algorithms` `Data Structures` `Big O Analysis`

---

### 🌐 Web & Full-Stack

#### [Full-Stack Blog Platform with RBAC](https://github.com/AngelosFikias0/Interactive_Role_Based_Web_App)

LAMP stack application with granular role-based access control, parameterized queries preventing SQL injection, and dynamic admin/user dashboards.

**Stack:** `PHP` `MySQL` `Apache` `Linux` `HTML5` `CSS3`

#### [Runners App - Spring Boot REST API](https://github.com/AngelosFikias0/Runners_App)

Spring Boot RESTful API with clean three-tier architecture, H2 in-memory database, and Maven dependency management. Architected for horizontal scalability.

**Stack:** `Spring Boot` `REST API` `H2` `Maven` `Java`

+ [Student Records Portal](https://github.com/AngelosFikias0/Student_Records_Web_Portal) · [Weather App](https://github.com/AngelosFikias0/Weather_App) · [Web Calculator](https://github.com/AngelosFikias0/Interactive_Web_Calculator) · [Task Manager](https://github.com/AngelosFikias0/Task_Manager_App)

---

### 🖥️ Desktop Applications

#### [Python Text Editor](https://github.com/AngelosFikias0/Python_Text_Editor)

Cross-platform text editor with Tkinter GUI, multi-format support, syntax highlighting, and customizable themes.

**Stack:** `Python` `Tkinter`

#### [Student Management System](https://github.com/AngelosFikias0/Student_Management_System)

Desktop application with Swing GUI and file-based persistence. Implements course and student lifecycle management following OOP and MVC.

**Stack:** `Java` `Swing` `OOP` `MVC`

+ [Quiz Game](https://github.com/AngelosFikias0/Quiz_game) · [Hangman](https://github.com/AngelosFikias0/Hangman_game)

---

*Full portfolio at [angelosfikias.dev](https://angelosfikias.dev)*
