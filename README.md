# Awesome-Transaction-Monitoring-Processing

# Awesome Transaction Monitoring & Processing

> A curated list of top Transaction Monitoring and Processing platforms — both SaaS/Hosted commercial solutions and open-source alternatives for real-time fraud detection, anti-money laundering (AML) compliance, and payment orchestration.  
> 🌟 Star this repo if you find it useful! 🌟

---

## 📋 Table of Contents

- [SaaS / Hosted Platforms](#-saas--hosted-platforms)
  - [ComplyAdvantage](#complyadvantage)
  - [Feedzai](#feedzai)
  - [Unit21](#unit21)
  - [Stripe Radar](#stripe-radar)
  - [Sardine](#sardine)
  - [SEON](#seon)
  - [Flagright](#flagright)
  - [Actimize](#actimize)
  - [Hawk AI](#hawk-ai)
- [Open-Source Software](#-open-source-software)
  - [Tazama](#tazama)
  - [Marble (CheckMarble)](#marble-checkmarble)
  - [ezrules](#ezrules)
  - [Hyperswitch](#hyperswitch)
  - [Mifos Payment Hub](#mifos-payment-hub)
  - [FraudSentinel](#fraudsentinel)
- [Comparison at a Glance](#-comparison-at-a-glance)
- [Contributing](#-contributing)

---

## 🟦 SaaS / Hosted Platforms

Commercial, cloud-hosted Transaction Monitoring and Processing platforms. These are not open-source but are included as reference points for feature comparison.

### ComplyAdvantage
**Type:** AML and financial crime risk data  
ComplyAdvantage provides AML screening, transaction monitoring, and adverse media checks using a proprietary risk database. Suited for regulated financial institutions needing comprehensive sanctions and PEP screening alongside monitoring workflows.

### Feedzai
**Type:** AI-powered fraud and financial crime prevention  
Feedzai uses machine learning to detect fraud across transactions, account openings, and payments in real time. Known for its risk engine that combines behavioral analytics with rule-based controls, serving large banks and payment processors.

### Unit21
**Type:** No-code risk and compliance platform  
Unit21 provides a no-code platform for fraud detection, AML monitoring, and case management. Teams can build rules, investigate alerts, and file SARs without engineering involvement. Positioned for fintechs and financial institutions wanting flexible compliance tooling.

### Stripe Radar
**Type:** Fraud detection within Stripe payments  
Stripe Radar is built into the Stripe payment platform, using machine learning trained on billions of transactions to block fraudulent payments. Available by default for Stripe users, with advanced rules and custom ML models on higher tiers.

### Sardine
**Type:** Fraud and compliance platform for fintechs  
Sardine combines fraud detection, AML compliance, and device intelligence for fintechs and digital wallets. Uses behavioral biometrics and device signals to detect account takeover and payment fraud in real time.

### SEON
**Type:** Fraud prevention with open data intelligence  
SEON detects and stops fraud in real time using open and social data combined with machine learning . Offers modular APIs, custom rules, and coverage for online gambling, e-commerce, digital financial services, and marketplaces. Positioned for businesses wanting flexible fraud tooling without extensive integration effort.

### Flagright
**Type:** AI-native AML compliance and risk management  
Flagright provides AI-native solutions for AML compliance and risk management, with automated risk detection, no-code configurability, and centralized operations . Advanced AI agents help reduce false positives and minimize operational errors in AML workflows. Trusted by regulated financial institutions globally.

### Actimize
**Type:** Enterprise financial crime and compliance  
Actimize (NICE) is a long-standing enterprise platform for AML, fraud prevention, and trade surveillance. Used by major banks and financial institutions for transaction monitoring, case management, and regulatory reporting at scale.

### Hawk AI
**Type:** AI-powered AML and fraud detection  
Hawk AI provides AML transaction monitoring, fraud detection, and customer screening for banks and payment providers. Emphasizes explainable AI and regulatory compliance, with deployment options for cloud and on-premises.

---

## 🟩 Open-Source Software

Self-hosted, community-driven Transaction Monitoring and Processing tools. The open-source ecosystem splits between **real-time fraud/AML detection engines** and **payment orchestration platforms**.

### Tazama
**Stack:** TypeScript / Docker / Kubernetes | **License:** Apache-2.0  
Tazama is an open-source, real-time transaction monitoring platform designed to detect fraud and money-laundering typologies as transactions happen [citation:5][citation:9]. The platform evaluates each transaction using rules-based monitoring with historical participant behavior, combining results into typologies with configurable thresholds. Features include **Connection Studio** for ingesting any message format, a **low-code Rule Studio** for rapid rule deployment, AI that recommends rules and optimizes thresholds to reduce false positives, and end-to-end case management with JupyterLab-based analytics [citation:9]. Deploys via Helm or Docker Compose, with 66 repositories covering the full stack [citation:5]. Focused on emerging markets and financial inclusion.  
**Best for:** Financial institutions and payment ecosystems wanting a production-ready, open-source real-time fraud and AML detection platform with low-code rule authoring and full auditability.

### Marble (CheckMarble)
**Stack:** HTML / Docker | **License:** Open Source (per project)  
Marble is an open-source, real-time decision engine for fraud and AML workflows [citation:12]. It provides a no-code platform for compliance teams to create and A/B test transaction monitoring rules, perform sanctions and watchlist screening, customer risk scoring, alert triage, and case investigation. Deployable on-premises or as SaaS, with an open core that enables auditor inspection. Claims to protect billions of transactions annually while reducing manual review workload . With 517 GitHub stars and recent activity, it is suitable for prototyping and internal use, though production deployment requires careful validation of integration details and dependency footprint [citation:12].  
**Best for:** Teams wanting an open-core, no-code platform for fraud/AML rule authoring and case management, accepting that some integration and production hardening effort is required.

### ezrules
**Stack:** Python / FastAPI / PostgreSQL / Redis / Docker | **License:** Open Source (per PyPI)  
ezrules is an open-source transaction monitoring platform focused on **clear rule control, auditability, and fast operational changes** [citation:2]. Provides a web workspace for managing decision rules without engineering involvement: rules can be drafted, tested, reviewed, promoted, paused, rolled out, and audited from one place. Features include shadow mode for observe-only comparison, percentage rollouts for controlled traffic exposure, backtesting against historical events, precision/recall/F1 quality reports with labeled events, and graph investigation through configured entity links [citation:2][citation:6]. Your application sends events to a simple evaluation API, and ezrules returns the resolved outcome. Self-hosted with PostgreSQL, Redis, FastAPI, Celery, and a web UI [citation:2].  
**Best for:** Fraud, risk, and compliance teams wanting self-hosted transaction monitoring with strong rule lifecycle management, audit trails, and evidence-based rule quality measurement.

### Hyperswitch
**Stack:** Rust | **License:** Apache-2.0  
Hyperswitch is an open-source payments platform from Juspay, designed as a **payment orchestration layer** that unifies payments across providers, networks, and channels [citation:3][citation:15]. Connects to multiple payment, payout, fraud, vault, and tokenization providers through a single API. Features include intelligent routing for authorization uplift and cost optimization, revenue recovery with smart retries, cost observability, and automated reconciliation [citation:15]. PCI-DSS compliant, with both SaaS and self-hosted deployment options. Built in Rust for performance and safety, supporting peak loads up to ~10K TPS [citation:3]. With 43k+ GitHub stars, it is one of the most mature open-source payment platforms available. **Note:** This is payment orchestration and processing, not transaction monitoring for fraud detection.  
**Best for:** Digital businesses wanting to self-host payment orchestration across multiple PSPs with intelligent routing, retries, and reconciliation, rather than fraud/AML monitoring.

### Mifos Payment Hub
**Stack:** Java / Zeebe / BPMN | **License:** Open Source (Digital Public Good)  
Mifos Payment Hub-EE is an open-source payment orchestration layer that routes transactions between core banking systems and payment networks using BPMN workflows on the Zeebe engine [citation:7]. Connectors cover mobile money, bulk disbursements, P2P, and QR payments, with support for ISO 20022 and the GSMA Mobile Money API. New payment systems are added through connectors and workflow definitions rather than code changes [citation:7]. Recognized as a Digital Public Good, designed for population-scale financial inclusion. **Note:** Like Hyperswitch, this is payment processing/orchestration infrastructure, not transaction monitoring for fraud.  
**Best for:** Financial service providers and national payment schemes wanting an open, interoperable orchestration layer for mobile money and core banking integrations.

### FraudSentinel
**Stack:** Python (LightGBM + GNN) | **License:** Apache-2.0  
FraudSentinel provides fast statistical scorers for the **Tier-1** of a two-tier fraud-detection architecture [citation:4]. The card fraud LightGBM model scores 100% of the transaction stream in single-digit milliseconds, achieving PR-AUC 0.967 and ROC-AUC 0.999 on held-out test data. At the routing threshold, it catches 90% of fraud while sending less than 0.4% of traffic to a more expensive Tier-2 LLM for explanation and SAR drafting. The AML GNN scorer (GINE edge-classifier) achieves ROC-AUC 0.894 on the IBM AML benchmark, beating the tabular baseline by 83% on PR-AUC [citation:4]. **Note:** This is a model/scorer library, not a complete monitoring platform.  
**Best for:** Data science teams wanting pre-trained, high-performance fraud and AML scorers as building blocks for a custom detection pipeline.

---

## 📊 Comparison at a Glance

| Software | License | Type | Real-Time Detection | Rule Management | Payment Orchestration | Self-Hosted | Best For |
|----------|---------|------|---------------------|-----------------|----------------------|-------------|----------|
| **ComplyAdvantage** | Proprietary | AML screening + monitoring | ✅ | ✅ | ❌ | ❌ | Sanctions/PEP screening |
| **Feedzai** | Proprietary | AI fraud prevention | ✅ | ✅ | ❌ | ❌ | Large bank fraud detection |
| **Unit21** | Proprietary | No-code risk/compliance | ✅ | ✅ | ❌ | ❌ | Fintech compliance teams |
| **Stripe Radar** | Proprietary | Payment fraud | ✅ | ✅ | (Stripe only) | ❌ | Stripe payment users |
| **Sardine** | Proprietary | Fraud + compliance | ✅ | ✅ | ❌ | ❌ | Fintech/wallet fraud |
| **SEON** | Proprietary | Fraud prevention | ✅ | ✅ | ❌ | ❌ | Modular fraud APIs |
| **Flagright** | Proprietary | AI-native AML | ✅ | ✅ | ❌ | ❌ | Regulated AI AML |
| **Actimize** | Proprietary | Enterprise financial crime | ✅ | ✅ | ❌ | (Enterprise) | Large bank compliance |
| **Hawk AI** | Proprietary | AI AML/fraud | ✅ | ✅ | ❌ | (Enterprise) | Explainable AML |
| **Tazama** | Apache-2.0 | Real-time fraud/AML | ✅ | ✅ Low-code | ❌ | ✅ | Open-source production monitoring |
| **Marble** | Open Source | Fraud/AML decision engine | ✅ | ✅ No-code | ❌ | ✅ | Open-core no-code rules |
| **ezrules** | Open Source | Transaction monitoring | ✅ | ✅ Lifecycle | ❌ | ✅ | Auditable rule control |
| **Hyperswitch** | Apache-2.0 | Payment orchestration | ❌ | ❌ | ✅ Multi-PSP | ✅ | Payment routing + retries |
| **Mifos PH-EE** | Open Source | Payment orchestration | ❌ | ❌ | ✅ Mobile money | ✅ | Financial inclusion payments |
| **FraudSentinel** | Apache-2.0 | ML scorers | ✅ (Scoring) | ❌ | ❌ | ✅ (Library) | Pre-trained fraud/AML models |

---

## 🤝 Contributing

Contributions are welcome! If you know of an open-source Transaction Monitoring or Processing tool that should be listed here, please open a pull request with:

- Project name and URL
- Brief description (1–2 sentences)
- Stack and license
- Why it stands out

Please ensure the project is actively maintained (releases within the last 12 months) and genuinely open-source. Note that the open-source ecosystem **splits** between **fraud/AML detection engines** (Tazama, Marble, ezrules) and **payment orchestration platforms** (Hyperswitch, Mifos). Tazama is currently the most production-ready open-source alternative to commercial transaction monitoring suites, with a complete ecosystem covering rule authoring, case management, and analytics.

---

## 📄 License

This list is released under CC0 1.0 Universal (Public Domain). The software projects listed retain their respective licenses.

---

⭐ **If this list helped you discover a useful tool, please star the repo!** ⭐
