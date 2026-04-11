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

Built a distributed E2E browser load testing platform on Kubernetes, running real Playwright browser sessions at scale via Artillery with exact VU auto-splitting, wave-based batch execution, and six configurable load profiles. 

- Playwright workers run as isolated Kubernetes Jobs per wave, orchestrated by Artillery with CSV-driven test data injection, per-session video capture, and a zero-dependency HTML reporting engine for result aggregation.
- Angular-aware test generator backed by a structured diagnostic knowledge base: auto-fixes 35+ known E2E pitfalls and surfaces targeted remediation for patterns it cannot resolve. 
- Helm-based environment lifecycle operator handles cluster-aware auto-discovery across four lookup strategies, full namespace provisioning and teardown, and GUI-guarded destructive operations. 
- Full observability via Prometheus and Grafana with SQLite regression tracking, shipped via GitHub Actions to Azure Container Registry. Deployed to production.

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
