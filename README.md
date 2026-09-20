# Awesome-Know-Your-Business

Top Know Your Business (KYB) Tools Ecosystem

Curated List of SaaS Products & Open-Source GitHub Projects
Focused on Business Verification, UBO Discovery, Corporate Registry Data & Compliance Onboarding
Last updated: September 2026

This repository tracks notable SaaS platforms and open-source projects for Know Your Business (KYB). These tools help banks, fintechs, payment platforms, and marketplaces verify business entities, uncover Ultimate Beneficial Ownership (UBO) structures, screen directors against sanctions, and automate merchant onboarding compliance.

Examples include Middesk, Alloy, Persona, Trulioo, Sumsub, ComplyAdvantage, FullCircl, Creditsafe, Encompass, Kyckr, Socure, Signzy, Veriff, and Incode (the category leaders).

Open-source emphasis: This section is heavily expanded with every major active project for self-hosting, custom risk workflows, and transparent business verification — ideal for compliance teams, fintech developers, and organizations that need full control over sensitive KYB data without per-verification pricing.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

Table of Contents

SaaS/Hosted Platforms

Open-Source GitHub Projects

How to Contribute

Disclaimer

SaaS/Hosted Platforms

Middesk
Business identity verification platform that automates KYB compliance, UBO discovery, and ongoing monitoring for fintechs and financial institutions.

Alloy
Identity risk and compliance platform covering KYC, KYB, and transaction monitoring. Orchestrates data from multiple vendors into unified decisioning workflows.

Persona
Identity verification platform with configurable workflows for KYC, KYB, and AML compliance. Strong developer experience and global coverage.

Trulioo
Global identity verification platform covering 195+ countries. Provides real-time identity checks, business verification, and AML watchlist screening.

Sumsub
All-in-one verification platform for KYC, KYB, AML, and transaction monitoring. Popular with crypto exchanges and fintechs for merchant onboarding.

ComplyAdvantage
AML and KYB compliance platform with global sanctions screening, adverse media monitoring, and business risk intelligence.

FullCircl
Customer lifecycle intelligence platform combining KYB, credit risk, and compliance data for financial services.

Creditsafe
Global business credit and risk intelligence platform with company reports, director search, and KYB data across 200+ countries.

Encompass
Automated KYB and AML platform that orchestrates data from multiple sources into streamlined compliance workflows.

Kyckr
Real-time corporate registry data platform providing direct access to official company information from 170+ jurisdictions.

Socure
Identity verification and fraud prevention platform with KYB capabilities for business account opening and merchant onboarding.

Signzy
Digital onboarding and KYB platform focused on India and emerging markets. Provides business verification, GST validation, and director checks.

Veriff
AI-powered identity verification with KYB capabilities for business entity validation and UBO identification.

Incode
Identity verification and onboarding platform with KYB modules for business verification and beneficial ownership discovery.

Open-Source GitHub Projects

Ballerine
Open-source infrastructure and data orchestration platform for risk decisioning. Provides KYB collection flows with UBO discovery, case management dashboard, workflow engine, and plugin system for third-party vendor integration. Self-hostable for data ownership. Y Combinator-backed. License: Open source -
4
-
9
-
13
.

KYC/KYB Entity Risk Scoring Engine
End-to-end KYB due diligence platform that models synthetic business entity data and scores entities using Gradient Boosting ML across 9 risk dimensions. UBO Opacity Score carries 28.1% feature importance — highest of all factors. Includes watchlist screening, adverse media, jurisdiction risk, and corporate structure complexity. Python, scikit-learn, Pandas -
2
.

BODS Visualisation Library
Open-source library for visualising beneficial ownership structures from data in Beneficial Ownership Data Standard (BODS) format. Supports time-slider to see ownership changes over time, clickable nodes for detailed information, and SVG output. Published as NPM package. License: Open source -
3
-
7
-
8
.

BODS Data Standard
The Beneficial Ownership Data Standard — an open specification for modelling and publishing beneficial ownership and control information. Foundation for interoperable UBO data across jurisdictions. Python-based. 63 stars -
7
-
8
-
17
.

Open Ownership Register
Demonstration transnational register of beneficial ownership data from UK, Denmark, Slovakia, and Armenia. Includes ingestion, transformation, and analysis pipelines for BODS-formatted data -
7
-
12
.

Neo4j Company House UBO Demo
Demonstrates UBO and company ownership analysis using UK Companies House data modelled in Neo4j Graph Database. Traverses multi-level ownership structures, identifies ultimate beneficial owners, and measures ownership depth and complexity. Relevant for AML, compliance, and corporate structure analysis. Includes Jupyter notebooks and Cypher query examples -
11
.

AML UBO Project
Entity-based graph built from normalized CSV/JSON/XML data using blocking-key data integration strategy. Answers critical AML queries through SPARQL and OWL ontology: UBO discovery, PEP exposure, circular ownership detection, cross-batch identity tracking, and offshore risk analysis -
16
.

ARES MCP Server
MCP server for Czech business registry (ARES) verification. Tools include company lookup by IČO, statutory body extraction, trade license verification, VAT payer check, insolvency red-flag detection, and full due diligence reports with risk flagging. Includes cross-company person analysis to identify multi-directorship networks -
1
.

Indian BizVerify MCP
MCP server for verifying Indian business entities using free government APIs. Tools: company search (MCA/CIN), GST validation, PAN verification, director lookup, and MSME Udyam registration check. TypeScript, deployable on AWS Lambda -
5
.

OSINT Agent
B2B due diligence and supplier risk verification tool using public data (OSINT). Generates professional HTML reports covering company background, financial analysis, supply chain tracing, decision-maker profiles, and risk ratings (🔴/🟡/🟢). Supports 15+ investigation types including supplier verification and Amazon seller background checks -
6
.

Creditsafe MCP Server
MCP server providing programmatic access to Creditsafe's global business credit and risk API. Tools: company search, company reports, director search, and director reports across 200+ countries. Requires Creditsafe API credentials -
14
.

Additional Strong Open-Source Options

UBO Graph Analysis: openownership/bodsanalysis (Jupyter notebooks for BODS data analysis), openownership/bodsriskdetection (RDF-based risk & compliance use cases for BO data) -
7
-
8
.

Company Registry Data: OpenCorporates bulk data ingesters (via Open Ownership register-ingester-oc), GLEIF BODS pipeline for Legal Entity Identifier data -
7
-
8
.

Risk Scoring: KYC/KYB Entity Risk Scoring Engine for ML-powered business risk assessment with 9 risk dimensions -
2
.

MCP Integrations: ARES MCP (Czech), Indian BizVerify MCP (India), Creditsafe MCP (global) — AI-native business verification tools -
1
-
5
-
14
.

Frameworks for building custom systems: Combine Ballerine for KYB workflow orchestration, Neo4j + BODS for UBO graph analysis, Entity Risk Scoring Engine for ML risk assessment, and PostgreSQL + Elasticsearch for business data persistence. Add OpenCorporates or national registry APIs for source data.

How to Contribute

Fork the repo.

Add/edit entries in README.md (follow existing format).

Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

Submit PR with a short explanation.

Star the repo if you find it useful!

Disclaimer

This is a community-curated list — not exhaustive and not an endorsement.

KYB tools process sensitive business and personal data; ensure compliance with AML regulations, GDPR, and regional corporate registry requirements.

Self-hosted open-source solutions require proper security hardening, data source licensing verification, and regular audits.

Made for fintech compliance teams, KYB engineers, AML analysts, and corporate onboarding specialists.
Let's make business verification more open, transparent, and auditable.
