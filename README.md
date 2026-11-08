# Awesome Transaction Monitoring & Processing [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of top **Transaction Monitoring**, **Fraud Detection**, **Anti-Money Laundering (AML) Compliance**, and **Payment Processing Orchestration** platforms — comparing enterprise SaaS/Hosted commercial solutions with open-source alternatives.

---

## 📋 Table of Contents

- [Sector Overview & Market Dynamics](#-sector-overview--market-dynamics)
- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [Commercial Solutions Comparison Table](#commercial-solutions-comparison-table)
  - [Platform Profiles](#platform-profiles)
- [Open-Source Software](#-open-source-software)
  - [Open-Source Solutions Comparison Table](#open-source-solutions-comparison-table)
  - [Open-Source Project Profiles](#open-source-project-profiles)
- [Summary Matrix at a Glance](#-summary-matrix-at-a-glance)
- [Contributing](#-contributing)
- [License](#-license)

---

## 🌐 Sector Overview & Market Dynamics

The global transaction monitoring and financial crime detection market is valued at approximately **$15–$23 billion** and projected to exceed **$50–$100 billion by 2032–2035**, expanding at a Compound Annual Growth Rate (CAGR) of **13% to 17%**. 

The sector is **moderately fragmented and highly specialized rather than a winner-take-all monopoly**, driven by divergent regional compliance mandates (such as FinCEN, EU AMLA, and FATF guidelines), domain-specific fraud typologies across BFSI, fintech, crypto, and e-commerce, and the co-existence of legacy financial surveillance suites (e.g., NICE Actimize) alongside agile, AI-native decisioning engines and payment orchestration platforms (e.g., Stripe, Sardine, Tazama, and Hyperswitch).

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Transaction Monitoring, Risk Intelligence, and Payment Fraud platforms.

### Commercial Solutions Comparison Table

Sorted descending by company size (Valuation / Annual Revenue):

| Platform | Company Size (Valuation / Revenue) | Starting Tier Pricing | Free Tier / Free Trial Limits | Key Specialization |
| :--- | :--- | :--- | :--- | :--- |
| **[Stripe Radar](https://stripe.com/radar)** | **$159B+ valuation** (~$5.12B+ net rev) | Radar Lite included in processing; **$0.02 / screened transaction** for Radar for Fraud Teams ($0.07/txn for non-Stripe) | **Radar Lite is free forever** (built into all Stripe transactions with ML scoring); 30-day trial for Radar for Fraud Teams | Payment fraud detection & real-time risk scoring |
| **[NICE Actimize](https://www.niceactimize.com/)** | **~$1.5B–$2.0B valuation** ($485M+ annual rev) | Enterprise contract starting at **~$50,000 / year** (scaled per module & volume) | **No free tier**; 30-day proof-of-concept (PoC) sandbox for qualified enterprise RFPs | Tier-1 bank AML surveillance, FRAML, & trade compliance |
| **[Feedzai](https://feedzai.com/)** | **$2.0B valuation** | Enterprise contract starting at **~$40,000 / year** (AWS marketplace & modular licenses) | **No free tier**; custom guided sandbox/PoC demo by sales request (no public self-serve trial) | AI-powered omnichannel fraud prevention & AML |
| **[Sardine](https://www.sardine.ai/)** | **$660M valuation** ($170M+ funding) | Consumption plans starting at **$1,500 / month** minimum platform commit | **No free tier**; 14-day assisted staging sandbox environment upon enterprise qualification | Real-time fraud, behavioral biometrics, & fintech AML |
| **[Unit21](https://www.unit21.ai/)** | **$300M valuation** ($92M+ funding) | Starter compliance suite starting at **$33,000 / year** (~$2,750/month) | **No free tier**; guided sandbox demo with simulated test transaction streams upon sales request | No-code AML rule authoring, alert triage, & SAR filing |
| **[ComplyAdvantage](https://complyadvantage.com/)** | **$100M+ ARR est.** ($100M+ funding) | **$99 / month** (Essentials tier, up to 100 monitored entity searches) | **12 months free** via ComplyLaunch program (for qualifying startups); custom demo upon request | Real-time sanctions, PEP screening, & adverse media checks |
| **[SEON](https://seon.io/)** | **~$50M ARR est.** ($94M+ funding) | **$599 / month** (Starter plan with custom rule builder & full API access) | **Free forever plan** up to 2,000 API calls/month (2 QPS limit) + 14-day free trial of Pro tier | Digital footprint analysis, email/phone profiling, & fraud APIs |
| **[Hawk AI](https://hawk.ai/)** | **~$25M ARR est.** ($73M+ funding) | Modular tier starting at **$15,000 / year** for high-growth fintechs | **No free tier**; structured 30-day technical trial / PoC for regulated banks and fintechs | Explainable AI AML transaction monitoring & screening |
| **[Flagright](https://www.flagright.com/)** | **~$10M valuation est.** ($4.3M Seed) | Growth package starting at **$15,000 / year** (~$1,250/month) | **No free tier**; 30-day self-serve sandbox API access & developer testing playground | AI-native automated AML compliance & copilot case management |

---

### Platform Profiles

#### Stripe Radar
- **Overview:** Fraud detection engine built directly into the Stripe payment infrastructure, using ML models trained across millions of global businesses.
- **Key Features:** Machine learning risk scores, automated block/allow lists, 3D Secure dynamic authentication, and no-code custom rule engines on advanced tiers.
- **Pricing Details:** Radar Lite included with standard processing; Radar for Fraud Teams adds $0.02 per screened transaction. Free 30-day trial for Fraud Teams; Radar Lite is free forever.

#### NICE Actimize
- **Overview:** Long-standing enterprise standard for anti-money laundering, trade surveillance, and cross-channel financial crime detection.
- **Key Features:** Enterprise case management, SAR/CTR regulatory automated reporting, watchlists, customer due diligence, and anomaly modeling.
- **Pricing Details:** Custom annual enterprise contracts starting at ~$50,000/yr. No public free tier; sandbox environments provided during RFPs.

#### Feedzai
- **Overview:** AI-native risk management engine serving top-tier retail banks, card acquirers, and central bank digital currency (CBDC) pilots.
- **Key Features:** Real-time stream processing, behavioral profiling, automated fraud triage, and hybrid rule-plus-AI machine learning models.
- **Pricing Details:** Starting contracts around ~$40,000/yr. PoC and sandbox access upon sales qualification.

#### Sardine
- **Overview:** Integrated platform combining fraud prevention, identity verification, and AML compliance designed for fintechs, crypto exchanges, and neobanks.
- **Key Features:** Device fingerprinting, behavioral biometrics (keystroke dynamics, device angling), payment orchestration screening, and ACH chargeback mitigation.
- **Pricing Details:** Minimum monthly commitment starting at $1,500/month. Assisted sandboxes available for qualified engineering teams.

#### Unit21
- **Overview:** Flexible, no-code data platform for AML monitoring, fraud investigation, and regulatory reporting.
- **Key Features:** Visual rule builder, custom scenario backtesting against historical database events, workflow automation, and SAR e-filing.
- **Pricing Details:** Annual tiers starting around $33,000/year. Sandbox and trial environments available via sales consultations.

#### ComplyAdvantage
- **Overview:** Financial crime data intelligence providing automated watchlist checks, adverse media scanning, and transaction monitoring.
- **Key Features:** Proprietary dynamic risk graph, real-time PEP/sanctions database updates, automated batch screening, and API-first webhook notifications.
- **Pricing Details:** Starts at $99/month for the Essentials tier. Eligible startups can receive up to 12 months free through the ComplyLaunch startup accelerator program.

#### SEON
- **Overview:** Digital footprint analysis tool that enriches customer identifiers (email, phone number, IP address) using open-source intelligence and social signals.
- **Key Features:** 50+ social platform lookups, browser fingerprinting, reverse phone/email scoring, and transparent rule decision explanations.
- **Pricing Details:** Starter plan starts at $599/month. Features a **free forever plan** with 2,000 API calls/month and a 14-day full Pro free trial.

#### Hawk AI
- **Overview:** Cloud-native surveillance platform for banks and payment service providers focusing on explainable AI and transparent audits.
- **Key Features:** Real-time transaction pattern anomaly detection, false-positive reduction using supervised ML, customer risk rating, and audit logs.
- **Pricing Details:** Modular packages starting from $15,000/year. Structured 30-day technical pilot programs available.

#### Flagright
- **Overview:** Modern, AI-first AML and fraud engine enabling fast integration via modular REST APIs and AI compliance co-pilots.
- **Key Features:** Real-time rule evaluation (<100ms response), generative AI case summarization, sanctions screening, and merchant risk monitoring.
- **Pricing Details:** Packages start around $15,000/year for growth fintechs. Free 30-day developer sandbox environment upon request.

---

## 🟩 Open-Source Software

Self-hosted, transparent, and community-driven tools for fraud detection, AML screening, graph intelligence, and payment orchestration.

### Open-Source Solutions Comparison Table

Sorted descending by GitHub star count:

| Project | Stars | Stack | License | Primary Focus |
| :--- | :--- | :--- | :--- | :--- |
| **[Hyperswitch](https://github.com/juspay/hyperswitch)** | [![Stars](https://img.shields.io/github/stars/juspay/hyperswitch?style=social&color=white)](https://github.com/juspay/hyperswitch/stargazers) | Rust | Apache-2.0 | Payment orchestration, multi-PSP routing, smart retries & processing |
| **[DGFraud](https://github.com/safe-graph/DGFraud)** | [![Stars](https://img.shields.io/github/stars/safe-graph/DGFraud?style=social&color=white)](https://github.com/safe-graph/DGFraud/stargazers) | Python / PyTorch / DGL | Apache-2.0 | Deep Graph Neural Network (GNN) toolbox for transaction fraud detection |
| **[Fraud Detection Handbook](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook)** | [![Stars](https://img.shields.io/github/stars/Fraud-Detection-Handbook/fraud-detection-handbook?style=social&color=white)](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook/stargazers) | Python / Jupyter / Scikit-learn | MIT | Practical machine learning pipeline & credit card fraud benchmarks |
| **[Marble](https://github.com/checkmarble/marble)** | [![Stars](https://img.shields.io/github/stars/checkmarble/marble?style=social&color=white)](https://github.com/checkmarble/marble/stargazers) | TypeScript / Python / Docker | Open Source | Real-time rule decision engine for fraud prevention & AML monitoring |
| **[Moov Watchman](https://github.com/moov-io/watchman)** | [![Stars](https://img.shields.io/github/stars/moov-io/watchman?style=social&color=white)](https://github.com/moov-io/watchman/stargazers) | Go | Apache-2.0 | High-performance search for OFAC sanctions, PEP, & global watchlists |
| **[Tazama](https://github.com/tazama-lf/docs)** | [![Stars](https://img.shields.io/github/stars/tazama-lf/docs?style=social&color=white)](https://github.com/tazama-lf/docs/stargazers) | TypeScript / Docker / K8s | Apache-2.0 | Linux Foundation real-time fraud & AML transaction monitoring suite |
| **[AI-Based AML System](https://github.com/mominalix/AI-Based-Anti-Money-Laundering-AML-System)** | [![Stars](https://img.shields.io/github/stars/mominalix/AI-Based-Anti-Money-Laundering-AML-System?style=social&color=white)](https://github.com/mominalix/AI-Based-Anti-Money-Laundering-AML-System/stargazers) | Python / Microservices | Apache-2.0 | End-to-end AML transaction monitoring & regulatory reporting reference |
| **[ezrules](https://github.com/sofeikov/ezrules)** | [![Stars](https://img.shields.io/github/stars/sofeikov/ezrules?style=social&color=white)](https://github.com/sofeikov/ezrules/stargazers) | Python / FastAPI / Redis / Postgres | Open Source | Auditable transaction monitoring rule lifecycle & shadow rollout engine |
| **[Mifos Payment Hub EE](https://github.com/openMF/ph-ee-start-here)** | [![Stars](https://img.shields.io/github/stars/openMF/ph-ee-start-here?style=social&color=white)](https://github.com/openMF/ph-ee-start-here/stargazers) | Java / Zeebe / BPMN | Mozilla 2.0 | Open financial inclusion payment routing, ISO 20022, & mobile money hub |
| **[FraudSentinel](https://github.com/jibz33on/fraudsentinel)** | [![Stars](https://img.shields.io/github/stars/jibz33on/fraudsentinel?style=social&color=white)](https://github.com/jibz33on/fraudsentinel/stargazers) | Python / LightGBM / PyG | Apache-2.0 | Ultra-fast Tier-1 statistical fraud and AML GNN scorers (<5ms) |

---

### Open-Source Project Profiles

#### [Hyperswitch](https://github.com/juspay/hyperswitch) [![Stars](https://img.shields.io/github/stars/juspay/hyperswitch?style=social&color=white)](https://github.com/juspay/hyperswitch/stargazers)
- **Stack:** Rust | **License:** Apache-2.0  
- **Description:** A high-performance, open-source payment orchestration platform developed by Juspay. Hyperswitch acts as a unified payments gateway connecting dozens of payment service providers (PSPs), vaults, tokenization services, and fraud detection endpoints through a single API.
- **Key Capabilities:** Dynamic smart routing to optimize authorization rates and lower transaction costs, automated card vaulting, auto-retries, reconciliation, and peak capacity handling up to ~10,000 TPS.
- **Best For:** Engineering teams looking to self-host unified payment processing orchestration without vendor lock-in.

#### [DGFraud](https://github.com/safe-graph/DGFraud) [![Stars](https://img.shields.io/github/stars/safe-graph/DGFraud?style=social&color=white)](https://github.com/safe-graph/DGFraud/stargazers)
- **Stack:** Python / PyTorch / DGL | **License:** Apache-2.0  
- **Description:** A comprehensive Graph Neural Network (GNN) toolbox specifically engineered for graph-based fraud detection. Implements state-of-the-art algorithms tailored to uncover multi-hop financial crime, synthetic identities, and collusive fraud networks.
- **Key Capabilities:** Out-of-the-box implementations of graph models including SemiGNN, GraphConsis, CARE-GNN, and GasGNN, with benchmarks on transactional datasets.
- **Best For:** Data science and risk engineering teams building custom graph algorithms for detecting fraud rings and organized transaction laundering.

#### [Fraud Detection Handbook](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook) [![Stars](https://img.shields.io/github/stars/Fraud-Detection-Handbook/fraud-detection-handbook?style=social&color=white)](https://github.com/Fraud-Detection-Handbook/fraud-detection-handbook/stargazers)
- **Stack:** Python / Scikit-learn / Jupyter | **License:** MIT  
- **Description:** An industry-standard open-source code and educational reference for credit card fraud detection. Provides fully reproducible implementations covering data simulation, baseline ML modeling, cost-sensitive assessment, and sequential transaction feature engineering.
- **Key Capabilities:** Synthetic transaction generator with injected fraud patterns, imbalanced learning strategies, PR-AUC and cost-sensitive evaluation metrics, and real-time streaming simulation.
- **Best For:** Engineers and analysts transitioning into financial fraud machine learning and transaction risk scoring.

#### [Marble](https://github.com/checkmarble/marble) [![Stars](https://img.shields.io/github/stars/checkmarble/marble?style=social&color=white)](https://github.com/checkmarble/marble/stargazers)
- **Stack:** TypeScript / Python / Docker | **License:** Open Source  
- **Description:** An open-source, real-time decision engine and workflow platform for financial fraud, sanctions screening, and AML transaction monitoring.
- **Key Capabilities:** Visual rule creation interface, customer risk scoring pipelines, integrated watchlist screening, audit logs, and alert triage case management.
- **Best For:** Fintechs and compliance teams desiring an open-core, transparent alternative to proprietary risk engines.

#### [Moov Watchman](https://github.com/moov-io/watchman) [![Stars](https://img.shields.io/github/stars/moov-io/watchman?style=social&color=white)](https://github.com/moov-io/watchman/stargazers)
- **Stack:** Go | **License:** Apache-2.0  
- **Description:** A dedicated, lightweight microservice for searching US OFAC sanctions (SDN), Sectoral Sanctions Identifications (SSI), Politically Exposed Persons (PEP), and European Union consolidated lists.
- **Key Capabilities:** Automated watchlist downloads and indexing, fuzzy phonetic matching (Jaro-Winkler, Levenshtein), REST APIs, embedded Go library usage, and in-memory search pipelines.
- **Best For:** Payment gateways and compliance stacks needing self-hosted, ultra-low latency customer and transaction sanctions screening.

#### [Tazama](https://github.com/tazama-lf/docs) [![Stars](https://img.shields.io/github/stars/tazama-lf/docs?style=social&color=white)](https://github.com/tazama-lf/docs/stargazers)
- **Stack:** TypeScript / NodeJS / Docker / K8s | **License:** Apache-2.0  
- **Description:** Hosted under the Linux Foundation and recognized as a Digital Public Good with backing from the Bill & Melinda Gates Foundation, Tazama is a full-scale open-source transaction monitoring system.
- **Key Capabilities:** Real-time event evaluation against multi-rule typologies, ISO 20022 financial message compliance, low-code Rule Studio, connection adapters for legacy core banking systems, and automated threshold calibration.
- **Best For:** Central banks, national payment switches, and Tier-2 financial institutions requiring production-grade, audited real-time AML monitoring.

#### [AI-Based AML System](https://github.com/mominalix/AI-Based-Anti-Money-Laundering-AML-System) [![Stars](https://img.shields.io/github/stars/mominalix/AI-Based-Anti-Money-Laundering-AML-System?style=social&color=white)](https://github.com/mominalix/AI-Based-Anti-Money-Laundering-AML-System/stargazers)
- **Stack:** Python / Microservices / Docker | **License:** Apache-2.0  
- **Description:** A microservices reference architecture for real-time AML monitoring that integrates pattern analysis, sanction screening, and explainable AI risk scoring.
- **Key Capabilities:** Velocity checking, rule-based decisioning, SHAP-based machine learning explanations, and automated regulatory reporting scaffolding.
- **Best For:** Developers and researchers looking for an end-to-end blueprint to build custom transaction monitoring microservices.

#### [ezrules](https://github.com/sofeikov/ezrules) [![Stars](https://img.shields.io/github/stars/sofeikov/ezrules?style=social&color=white)](https://github.com/sofeikov/ezrules/stargazers)
- **Stack:** Python / FastAPI / Redis / PostgreSQL | **License:** Open Source  
- **Description:** An open-source transaction monitoring platform centered on granular rule control, historical backtesting, and full auditability.
- **Key Capabilities:** Web-based operational console, shadow rule evaluation mode (dry run without impacting live traffic), percentage-based rollout flags, precision/recall metrics calculation, and entity relationship visualization.
- **Best For:** Risk teams requiring a self-hosted, transparent rule evaluation engine with zero engineering dependency for day-to-day rule modifications.

#### [Mifos Payment Hub EE](https://github.com/openMF/ph-ee-start-here) [![Stars](https://img.shields.io/github/stars/openMF/ph-ee-start-here?style=social&color=white)](https://github.com/openMF/ph-ee-start-here/stargazers)
- **Stack:** Java / Zeebe / BPMN | **License:** Mozilla Public License 2.0  
- **Description:** An enterprise-grade payment orchestration engine designed for financial inclusion by the Mifos Initiative. Bridges core banking engines (such as Apache Fineract) with national payment switches and mobile wallets.
- **Key Capabilities:** Zeebe BPMN workflow orchestration, ISO 20022 and GSMA Mobile Money API compliance, asynchronous settlement, and pre-built connectors for instant payment networks (including Mojaloop).
- **Best For:** Microfinance institutions, regional digital banks, and sovereign mobile money networks.

#### [FraudSentinel](https://github.com/jibz33on/fraudsentinel) [![Stars](https://img.shields.io/github/stars/jibz33on/fraudsentinel?style=social&color=white)](https://github.com/jibz33on/fraudsentinel/stargazers)
- **Stack:** Python / LightGBM / PyG | **License:** Apache-2.0  
- **Description:** Ultra-fast Tier-1 statistical models built to pre-filter massive payment streams before invoking costly LLM inference or complex investigative pipelines.
- **Key Capabilities:** LightGBM card fraud scoring in under 5ms (ROC-AUC 0.999), GINE Graph Neural Network AML scoring (ROC-AUC 0.894), and edge-based routing thresholds.
- **Best For:** High-throughput fintech pipelines requiring sub-5ms transaction triage to isolate top 0.5% suspicious flows for human review or LLM reasoning.

---

## 📊 Summary Matrix at a Glance

| Tool / Platform | Category | Deployment | Real-Time Latency | Pricing / License | Core Focus |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Stripe Radar** | SaaS | Hosted | <50ms | Free Lite / $0.02 per txn | Integrated card payment fraud |
| **NICE Actimize** | SaaS / Hybrid | Hosted / On-Prem | <100ms | From ~$50,000/yr | Enterprise Tier-1 bank AML & FRAML |
| **Feedzai** | SaaS | Hosted / Cloud | <20ms | From ~$40,000/yr | AI behavioral fraud & financial crime |
| **Sardine** | SaaS | Hosted | <100ms | From $1,500/mo commit | Device & behavioral biometrics fraud |
| **Unit21** | SaaS | Hosted | <150ms | From $33,000/yr | No-code AML rule authoring & SARs |
| **ComplyAdvantage** | SaaS | Hosted | <100ms | From $99/mo | Sanctions, PEP, & watchlist screening |
| **SEON** | SaaS | Hosted | <200ms | Free tier (2k calls/mo) / $599/mo | Open data & digital footprint intelligence |
| **Hawk AI** | SaaS | Hosted / Cloud | <80ms | From $15,000/yr | Explainable AI AML transaction monitoring |
| **Flagright** | SaaS | Hosted | <100ms | From $15,000/yr | AI-native automated AML & copilot triage |
| **Hyperswitch** | Open Source | Self-Hosted / Cloud | <10ms | Apache-2.0 | Multi-PSP payment routing & orchestration |
| **DGFraud** | Open Source | Self-Hosted | Batch / Micro | Apache-2.0 | Graph Neural Networks (GNN) fraud models |
| **Fraud Handbook** | Open Source | Self-Hosted | N/A (Educational) | MIT | Reproducible ML fraud detection handbook |
| **Marble** | Open Source | Self-Hosted | <50ms | Open Source | Real-time rules & AML decision engine |
| **Moov Watchman** | Open Source | Self-Hosted | <5ms | Apache-2.0 | OFAC sanctions & PEP list screening |
| **Tazama** | Open Source | Self-Hosted / K8s | <50ms | Apache-2.0 | Full open-source AML monitoring platform |
| **AI AML System** | Open Source | Self-Hosted | <100ms | Apache-2.0 | Microservices AML reference architecture |
| **ezrules** | Open Source | Self-Hosted | <20ms | Open Source | Rule shadow testing & lifecycle management |
| **Mifos PH-EE** | Open Source | Self-Hosted | <200ms | Mozilla 2.0 | Payment orchestration & financial inclusion |
| **FraudSentinel** | Open Source | Self-Hosted (Lib) | <5ms | Apache-2.0 | Sub-5ms Tier-1 statistical fraud scorers |

---

## 🤝 Contributing

Contributions are welcome! Please feel free to open a pull request or submit an issue to suggest new platforms, update pricing benchmarks, or add open-source tools:

1. **Fork** this repository.
2. **Create a branch** for your updates (`git checkout -b feature/add-new-platform`).
3. Ensure open-source additions include:
   - Repository link with an official GitHub stars social badge
   - Tech stack & license details
   - Active maintenance status (commits/releases within the past 12 months)
4. **Commit & Push** your branch, then open a Pull Request.

---

## 📄 License

This repository and curated list are released under the [CC0 1.0 Universal (Public Domain)](https://creativecommons.org/publicdomain/zero/1.0/). Listed third-party tools, projects, and trademarks retain their respective licenses and rights.

---

<div align="center">
  <b>⭐ Found this repository helpful? Give it a star on GitHub! ⭐</b>
</div>
