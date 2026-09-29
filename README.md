# Awesome-Case-Management-For-AML

# Top AML Case Management Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Alert Triage, Investigation Workflows, SAR Filing & Regulatory Case Documentation*  
**Last updated: September 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **AML Case Management**. These tools help financial crime analysts, compliance officers, and AML investigators manage alerts, document investigations, file Suspicious Activity Reports (SARs), and maintain audit-ready case histories.

**Examples** include NICE Actimize, Oracle FCCM, FICO TONBELLER, SAS AML, ComplyAdvantage Case Manager, Unit21, Flagright, Feedzai, AMLYZE, and Fenergo (the category leaders).

**Open-source emphasis**: This section is heavily expanded with every major active project for self-hosting, custom investigation workflows, and transparent case documentation — ideal for fintechs and financial institutions that need full control over sensitive AML data without per-case SaaS fees or vendor lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents

- [SaaS/Hosted Platforms](#saas-hosted-platforms)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[NICE Actimize](https://www.niceactimize.com/)**  
  Leading AML and financial crime platform with comprehensive case management, alert triage, and investigation workflows. Used by major banks and financial institutions worldwide.

- **[Oracle FCCM](https://www.oracle.com/)**  
  Financial Crime and Compliance Management suite with case management, investigation, and SAR filing capabilities. Part of Oracle's enterprise risk platform.

- **[FICO TONBELLER](https://www.fico.com/)**  
  AML compliance platform with case management, alert investigation, and regulatory reporting. Combined with FICO's broader risk analytics capabilities.

- **[SAS AML](https://www.sas.com/)**  
  AML solution with case management, investigation workflows, and regulatory reporting. Part of SAS's financial crimes compliance suite.

- **[ComplyAdvantage Case Manager](https://complyadvantage.com/)**  
  Case management module within ComplyAdvantage's AML platform. Provides investigation workflows, documentation, and SAR preparation.

- **[Unit21](https://www.unit21.ai/)**  
  No-code AML and fraud platform with case management, investigation workflows, and automated SAR filing. Popular with fintechs and payment platforms.

- **[Flagright](https://www.flagright.com/)**  
  AI-native AML compliance platform with case management, real-time transaction monitoring, and investigation tools.

- **[Feedzai](https://feedzai.com/)**  
  Financial crime prevention platform with case management and investigation capabilities. Uses AI for risk detection and alert prioritization.

- **[AMLYZE](https://amlyze.com/)**  
  AML compliance platform focused on case management, investigation, and regulatory reporting for financial institutions.

- **[Fenergo](https://www.fenergo.com/)**  
  Client lifecycle management and AML compliance platform with case management and investigation workflows for financial institutions.

## Open-Source GitHub Projects

- **[Jube](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  
  Open-source AML and fraud detection platform with **case management** capabilities. Written in C# (.NET), licensed under AGPL-3.0. Features real-time transaction monitoring, ML-based detection, flexible rule engine with thresholds, velocity checks, aggregation counts, and sanctions screening. **Full audit trails for all actions**, multi-tenancy support, and Docker/Kubernetes deployment. Includes case management for investigating alerts and decisions. ~29 stars . **AGPL-3.0**.

- **[Marble](https://github.com/checkmarble/marble)**  
  Real-time decision engine for fraud and AML with an integrated **case manager**. Written in Go/TypeScript, licensed under Elastic License 2.0 (ELv2). Features rule-based detection scenarios, batch and real-time execution, **case management for investigating decisions and creating escalations**, custom lists, and full audit trails with versioning. Self-hosted version is free; cloud version priced like SaaS. Backed by €6.5M Series A (Smartfin lead), with 100+ institutions in 25+ countries using it in production . **Elastic License 2.0**.

- **[Ballerine](https://github.com/ballerine-io/ballerine)**  
  Open-source infrastructure for identity and risk management with a **case management dashboard for manual user approval**. TypeScript-based, ~2,065 stars. Features KYC/KYB UI flows, rule engine for automated decisioning, and integrations with identity verification providers. The case management dashboard allows manual review and approval of users, supporting AML onboarding and ongoing risk assessment. **Open source** .

- **[Tazama](https://github.com/tazama-lf)**  
  Open-source real-time transaction monitoring platform for fraud and money laundering detection, launched by the Linux Foundation with support from the Bill and Melinda Gates Foundation. Apache-2.0 licensed, Digital Public Good verified. Features rule processors, typology scoring, **case management integration** (alerts and case data sent to external case management systems), ISO 20022 compliance, and Kubernetes deployment. Used by COMESA JOPACC and BCEAO (in development) . **Apache-2.0**.

- **[Argus Investigator](https://github.com/Cesco556/argus-investigator)**  
  Modern AML investigator workspace with **case management UI**. Powered by Claude AI agent with MCP tools, defensible decision trail, and append-only event logging. Features case triage with severity and SAR clock, agent-powered reasoning with citations, network graph visualization (Sigma.js), and UK-scoped SAR rules (NCA DAML semantics). Next.js 16, MongoDB Atlas. **Open source** .

- **[AML Transaction Monitoring Engine](https://github.com/Cesco556/aml-transaction-monitoring-engine)**  
  Production-grade AML platform with ML anomaly detection, sanctions screening, network analysis, and **FinCEN SAR compliance reporting**. Python/FastAPI with Docker Compose deployment. Features real-time streaming (Redis Streams), **case management with investigation workflows**, FinCEN SAR generation (BSA E-Filing format), PDF investigation reports, audit export with hash chain verification, and regulatory timelines (FinCEN 30/60d, UK FCA 15/30d, EU AMLD 30/45d). **Open source** .

- **[Nexus AML Compliance](https://packagist.org/packages/azaharizaman/nexus-aml-compliance)**  
  Framework-agnostic PHP package for AML risk assessment and **transaction monitoring with SAR generation**. Features risk scoring (0-100) for parties and transactions, transaction monitoring for unusual patterns, **automated Suspicious Activity Report (SAR) generation**, jurisdiction risk assessment, and configurable thresholds. Pure PHP 8.3+, works with any framework. **Open source** .

- **[Clarium](https://github.com/QuantSingularity/Clarium)**  
  RegTech compliance module with FastAPI KYC/AML engine, **hash-chained audit trail**, jurisdiction rules, and React admin dashboard. Features AML transaction monitoring with four rules (amount threshold, velocity, geographic risk, PEP matching), **case review endpoints** (`PATCH /aml/review/{id}`), jurisdiction rules for US/GB/EU/SG/AE, webhooks with HMAC signing, and tamper-detection via SHA-256 hash chaining. **Open source** .

- **[ThreatLens](https://github.com/innovatewithkishlay/ThreatLens)**  
  AI-powered AML investigation platform for detecting and visualizing suspicious money laundering patterns. Creates interactive spider maps showing money flow between accounts, linking account holders, IPs, phone numbers, and emails. MIT licensed. **Open source** .

- **[FMS (Fraud Monitoring System)](https://www.linkedin.com/posts/tochukwu-iloani-166259100_aml-regtech-frauddetection-activity-7484713507054346240-ZRel)**  
  Open-source project exploring risk-based transaction monitoring and AML workflows. Features risk-based transaction monitoring, rule engine, customer risk profiling, **CTR/SAR workflow**, OFAC/sanctions screening, **case management**, audit trails, and analytics/reporting. Python-based. **Open source** .

- **[Graphomaly](https://pypi.org/project/graphomaly/)**  
  Automatic tool for Anti-Money Laundering (AML) and detecting abnormal behavior in graph and network structures. Uses machine learning for anomaly detection in financial transactions. Scikit-learn API compatible. **Open source** .

### Additional Strong Open-Source Options

- **Case Management UI**: **Argus Investigator** (AI-powered workspace with decision trail), **ThreatLens** (visual investigation platform) .
- **Full AML Platforms**: **Jube** (transaction monitoring + case management), **Marble** (decision engine + case manager), **AML Transaction Monitoring Engine** (SAR compliance + case management) .
- **Compliance Packages**: **Nexus AML Compliance** (PHP, SAR generation), **Clarium** (FastAPI, hash-chained audit) .
- **Transaction Monitoring**: **Tazama** (Linux Foundation, case management integration), **Graphomaly** (ML anomaly detection) .

**Frameworks for building custom systems**: Combine **Jube** or **Marble** for the core AML detection and case management engine, **Tazama** for ISO 20022-compliant transaction monitoring with case integration, **Argus Investigator** or **ThreatLens** for the investigation UI, and **Nexus AML Compliance** or **Clarium** for SAR generation and audit trails. Add **PostgreSQL** for persistence, **MongoDB** for event logging, and **Docker** for deployment.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- AML case management platforms handle sensitive financial and personal data; ensure compliance with BSA/AML, FinCEN, OFAC, and relevant regional regulations.
- **Open-source reality**: The open-source ecosystem for AML case management is **developing but not yet enterprise-grade**. **Jube** and **Marble** offer production-ready transaction monitoring with case management, but neither matches the full investigation workflow polish of NICE Actimize or Unit21. **Argus Investigator** and **ThreatLens** provide modern investigation UIs but are early-stage. For regulated institutions requiring immediate compliance, commercial platforms remain the primary choice.
