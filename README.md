<p align="center">
  <a href="https://github.com/ishandutta2007/Awesome-Awesome-Awesome"><img src="https://img.shields.io/badge/Awesome-%E2%9C%94-blueviolet?style=flat-square&logo=github" alt="Awesome"/></a>
  <a href="https://discord.gg/jc4xtF58Ve"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
  <img src="https://img.shields.io/github/license/ishandutta2007/Awesome-Fraud-Orchestration-Platform?style=flat-square" alt="License"/>
  <img src="https://img.shields.io/github/last-commit/ishandutta2007/Awesome-Fraud-Orchestration-Platform?style=flat-square" alt="Last Commit"/>
  <img src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" alt="PRs Welcome"/>
  <a href="https://github.com/ishandutta2007"><img alt="GitHub followers" src="https://img.shields.io/github/followers/ishandutta2007?label=Follow" /></a>
</p>

<p align="center">
  <img src="assets/banner.svg" alt="Awesome Fraud Orchestration Platform Banner" width="100%" />
</p>

# 🛡️ Awesome Fraud Orchestration Platform

> **A curated ecosystem of SaaS products, open-source risk engines, device intelligence signals, and real-time transaction monitoring frameworks.**

Welcome to the **Awesome Fraud Orchestration Platform** directory. This repository provides a comprehensive, production-grade index of software platforms and open-source libraries used to orchestrate complex risk decisioning. Modern fraud orchestration platforms aggregate signals (device fingerprinting, behavioral biometrics, identity checks, velocity counters, and IP risk), execute business rules alongside machine learning models, dynamically route transactions to accept/review/decline flows, and provide operational case management for risk ops teams.

---

## 📌 Table of Contents

- [🌐 SaaS / Enterprise Hosted Platforms](#-saas--enterprise-hosted-platforms)
- [💻 Open-Source GitHub Projects](#-open-source-github-projects)
- [🏗️ Fraud Orchestration Architecture Patterns](#%EF%B8%8F-fraud-orchestration-architecture-patterns)
- [🤝 How to Contribute](#-how-to-contribute)
- [📈 Star History](#-star-history)
- [💖 Support & Community](#-support--community)
- [⚠️ Disclaimer](#%EF%B8%8F-disclaimer)

---

## 🌐 SaaS / Enterprise Hosted Platforms

💡 **Market Landscape:** The global Fraud Detection and Orchestration market is estimated at **$12.5B–$15.0B** (projected to reach ~$38B+ by 2032 at ~18.5% CAGR). The market structure is **moderately fragmented**—dominated by enterprise identity networks and chargeback guarantee leaders (*Forter, Feedzai, Signifyd, Sift, Riskified*) alongside fast-growing specialized risk-ops and device intelligence platforms (*Sardine, SEON, Unit21, Castle*).

*Platforms are sorted below by estimated company size / valuation in descending order.*

| Platform | Valuation / Company Size | Pricing Column | Free Tier / Trial Limits | Core Specialization & Features |
| :--- | :--- | :--- | :--- | :--- |
| **[Forter](https://www.forter.com/)** | **~$3.0B Valuation** (~$103M ARR) | GMV-based pricing (% of approved transaction volume) | Guided Demo & Custom Sandbox (No self-serve free tier) | Identity-network fraud decisioning engine returning instant approve/decline with optional chargeback liability protection. |
| **[Feedzai](https://www.feedzai.com/)** | **~$2.0B+ Valuation** (~$167M ARR) | Enterprise Custom Contract (Based on modules & volume) | Guided Demo & Enterprise Proof-of-Concept (No self-serve free tier) | Enterprise AI risk and financial crime prevention platform for major banks and card processors with deep RiskOps governance. |
| **[Signifyd](https://www.signifyd.com/)** | **~$1.34B Valuation** (~$292M ARR) | Custom GMV % (Min. annual commit starting ~$1,500/mo) | Free Risk Assessment & Custom Demo (No self-serve free tier) | Commerce protection platform providing 100% financial chargeback guarantees and automated checkout decisioning. |
| **[Sift](https://sift.com/)** | **~$1.0B+ Valuation** (~$35M ARR) | Pay-as-you-go from ~$0.06/event (~$500/mo min. spend) | **30-Day Free Trial** with developer sandbox access | Digital Trust & Safety suite offering ML risk scoring, account takeover (ATO) prevention, and dispute management. |
| **[Riskified](https://www.riskified.com/)** | **~$804M Market Cap** (NYSE: RSKD, ~$368M TTM) | Performance-based % fee on approved orders only | Free Merchant Risk Assessment & Live Demo (No self-serve free tier) | E-commerce fraud decisioning platform offering chargeback guarantees on approved orders for high-volume merchants. |
| **[Unit21](https://www.unit21.ai/)** | **~$700M Valuation** (~$25M ARR) | Custom Tiered ($33,000 to $740,000/year contract ranges) | Guided Sandbox Trial (Custom evaluation duration) | No-code risk operations platform combining rule builders, transaction monitoring, automated SAR filings, and case workflows. |
| **[SEON](https://seon.io/)** | **~$500M Valuation** (~$35M ARR) | Free Plan; Starter at $599/mo; +$0.05–$0.30/call enrichment | **Free-Forever Plan** (Up to 2,000 API calls/month, 2 QPS, 10 custom rules, 2 user seats) | Modular fraud API integrating digital footprinting (email, phone, social), device intelligence, and transparent rule management. |
| **[Sardine](https://www.sardine.ai/)** | **~$171M Funding** (~$23M ARR) | Per-decision API ($0.01–$0.10/call) + ~$1,000/mo base commit | Demo-led Developer Sandbox Evaluation (Custom trial length) | Unified risk platform for fintech & crypto, combining device intelligence, behavioral biometrics, and real-time bank transfer risk. |
| **[Castle](https://castle.io/)** | **~$15M Funding** (~$9.3M ARR) | Pro Plan at $200/mo ($0.005/request); Enterprise custom | **Free-Forever Plan** ($5/mo credit, ~1,000 requests/month forever) | Product security and account takeover prevention platform tracking device telemetry, session anomalies, and bot risks. |
| **[Fraud.net](https://www.fraud.net/)** | **~$6.85M Funding** (~$5.5M ARR) | Module-based starting at ~$1,000/mo base + API volume | Free Fraud Audit & Custom Demo (No self-serve free tier) | Cloud-native AI fraud orchestration ecosystem combining collective intelligence, AML compliance, and rule management. |

---

## 💻 Open-Source GitHub Projects

These open-source tools provide the foundational building blocks for engineering custom risk decision engines, streaming feature stores, rule execution DAGs, and transaction monitoring pipelines.

*Repositories are sorted below by GitHub star count in descending order.*

| Project & Link | Star Count | Tech Stack | Description & Core Capability |
| :--- | :--- | :--- | :--- |
| **[feast-dev/feast](https://github.com/feast-dev/feast)** | [![GitHub stars](https://img.shields.io/github/stars/feast-dev/feast?style=social&color=white)](https://github.com/feast-dev/feast/stargazers) | Python / Go | Open-source feature store used to compute, store, and serve real-time velocity counters and ML features to fraud detection pipelines. |
| **[j-easy/easy-rules](https://github.com/j-easy/easy-rules)** | [![GitHub stars](https://img.shields.io/github/stars/j-easy/easy-rules?style=social&color=white)](https://github.com/j-easy/easy-rules/stargazers) | Java | Lightweight, POJO-based Java rules engine designed to evaluate business and validation rules in low-latency decision pipelines. |
| **[CacheControl/json-rules-engine](https://github.com/CacheControl/json-rules-engine)** | [![GitHub stars](https://img.shields.io/github/stars/CacheControl/json-rules-engine?style=social&color=white)](https://github.com/CacheControl/json-rules-engine/stargazers) | JavaScript / Node.js | Rules engine specified in JSON format, allowing dynamic rule execution and policy evaluation in Node.js and browser environments. |
| **[gorules/zen](https://github.com/gorules/zen)** | [![GitHub stars](https://img.shields.io/github/stars/gorules/zen?style=social&color=white)](https://github.com/gorules/zen/stargazers) | Rust / Go / Python / JS | High-performance GoRules Business Rules Engine supporting Decision Tables (JDM) and DAG execution for ultra-low latency risk scoring. |
| **[feathr-ai/feathr](https://github.com/feathr-ai/feathr)** | [![GitHub stars](https://img.shields.io/github/stars/feathr-ai/feathr?style=social&color=white)](https://github.com/feathr-ai/feathr/stargazers) | Scala / Python | Enterprise feature store (originally created by LinkedIn) for defining, managing, and serving features in real-time fraud models. |
| **[jube-home/aml-fraud-transaction-monitoring](https://github.com/jube-home/aml-fraud-transaction-monitoring)** | [![GitHub stars](https://img.shields.io/github/stars/jube-home/aml-fraud-transaction-monitoring?style=social&color=white)](https://github.com/jube-home/aml-fraud-transaction-monitoring/stargazers) | Go / TypeScript | AGPLv3 open-source platform for real-time transaction monitoring, hybrid rule + ML risk scoring, audit trails, and investigation case management. |
| **[zhucl121/risk-engine](https://github.com/zhucl121/risk-engine)** | [![GitHub stars](https://img.shields.io/github/stars/zhucl121/risk-engine?style=social&color=white)](https://github.com/zhucl121/risk-engine/stargazers) | Go | High-performance open-source risk engine in Go featuring RiskDSL, DAG pipeline execution, shadow/canary deployments, and ONNX model evaluation. |
| **[databricks-industry-solutions/fraud-orchestration](https://github.com/databricks-industry-solutions/fraud-orchestration)** | [![GitHub stars](https://img.shields.io/github/stars/databricks-industry-solutions/fraud-orchestration?style=social&color=white)](https://github.com/databricks-industry-solutions/fraud-orchestration/stargazers) | PySpark / Python | Lakehouse solution blueprint demonstrating rule-based filtering combined with real-time ML anomaly detection algorithms on Databricks. |

---

## 🏗️ Fraud Orchestration Architecture Patterns

A complete production fraud orchestration pipeline typically links these operational layers:

```
[ User Event / Payment ]
           │
           ▼
[ Signal Collectors ] (Device Fingerprint, Behavioral Telemetry, IP / Email Risk APIs)
           │
           ▼
[ Feature Enrichment ] (Kafka / Redis Velocity Counters, Feast / Feathr Feature Store)
           │
           ▼
[ Decision Engine ] (Zen Engine / Easy Rules / RiskEngine DSL + ONNX ML Inference)
           │
      ┌────┴────────────────────────┐
      ▼                             ▼
[ Accept / Decline ]       [ Manual Review Queue ] (Jube Case Ops / Analyst Dashboard)
```

---

## 🤝 How to Contribute

Contributions are warmly welcomed! Please follow these simple guidelines:

1. Fork the repository.
2. Add or update SaaS entries or open-source repositories in `README.md`.
3. Ensure descriptions are accurate, factual, and formatted according to existing tables.
4. Open a Pull Request detailing your additions.

For a full directory of awesome open-source lists, check out [Awesome-Awesome-Awesome](https://github.com/ishandutta2007/Awesome-Awesome-Awesome).

---

## 📈 Star History

[![Star History Chart](https://star-history.dera.page/svg?repos=ishandutta2007/Awesome-Fraud-Orchestration-Platform&type=date&legend=top-left)](https://star-history.dera.page/#ishandutta2007/Awesome-Fraud-Orchestration-Platform&type=date&legend=top-left)

---

## 💖 Support & Community

Thank you for exploring the **Awesome Fraud Orchestration Platform** ecosystem! If you find this curated directory helpful for your risk operations, engineering, or compliance teams:

- ⭐️ **Star this repo** to support the project and make it discoverable for others.
- 🔀 **Fork & Contribute** to keep SaaS pricing, limits, and open-source options updated.
- 📢 **Share with colleagues** across risk management, payments, and security communities.

<a href="https://github.com/sponsors/ishandutta2007"><img src="https://img.shields.io/badge/Sponsor-Buy%20Me%20A%20Coffee-ffdd00?style=for-the-badge&logo=buy-me-a-coffee&logoColor=black" alt="Sponsor / Buy Me A Coffee" /></a>

---

## ⚠️ Disclaimer

- This list is **community-curated** for educational and architectural reference purposes only.
- High-stakes risk and fraud decisions impact user privacy, legal compliance, and monetary liabilities.
- Open-source and SaaS implementations require rigorous testing, bias evaluation, and compliance with regional regulations (GDPR, PCI-DSS, SOC2, AML laws). This repository does not provide legal or financial advice.
