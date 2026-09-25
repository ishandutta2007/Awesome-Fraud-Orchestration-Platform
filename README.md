# Awesome-Fraud-Orchestration-Platform

## Top Fraud Orchestration Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Risk Decisioning, Rules + ML Orchestration, Case Management, Device Intelligence & Real-Time Fraud Workflows*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Fraud Orchestration**. These systems combine signals (device, behavior, identity, transaction), rules, machine learning, and workflows to make real-time accept/review/decline decisions and manage investigations across payments, accounts, and onboarding.



**Examples** include Sardine, Sift, Forter, Riskified, SEON, Fraud.net, Feedzai, Signifyd, Castle, and Unit21 (the category leaders).



**Open-source emphasis**: Full-scale commercial fraud orchestration with global networks and guarantees remains dominant. Practical open options include real-time monitoring platforms (**Jube**), high-performance risk decision engines, rule + ML pipelines, and case-management building blocks. This section lists the strongest available open resources and is realistic about the commercial gap.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Sardine](https://www.sardine.ai/)**  

  Unified risk platform combining device intelligence, behavioral analytics, fraud rules, and compliance signals—strong fit for fintech, crypto, BNPL, and platforms that hold balances or issue cards.



- **[Sift](https://sift.com/)**  

  Machine-learning fraud and abuse platform providing real-time scores, workflows, and decision support for e-commerce, marketplaces, and digital trust use cases.



- **[Forter](https://www.forter.com/)**  

  Identity-network fraud decisioning engine that returns approve/decline decisions and supports liability models for large retailers and digital commerce.



- **[Riskified](https://www.riskified.com/)**  

  E-commerce fraud prevention platform offering chargeback guarantees on approved orders and AI-driven review for merchants seeking to transfer fraud-loss risk.



- **[SEON](https://seon.io/)**  

  Fraud prevention platform popular with fintech and iGaming, combining device, email, phone, and behavioral signals with transparent pricing and fast integration.



- **[Fraud.net](https://www.fraud.net/)**  

  AI-powered fraud detection and orchestration platform focused on financial services and complex fraud patterns.



- **[Feedzai](https://www.feedzai.com/)**  

  Enterprise AI platform for fraud and financial crime prevention used by banks and payment processors at large scale, with strong RiskOps and model governance.



- **[Signifyd](https://www.signifyd.com/)**  

  Commerce protection platform offering fraud guarantees and decisioning for online merchants.



- **[Castle](https://castle.io/)**  

  Account security and fraud platform specializing in account takeover prevention, device intelligence, and risk scoring for digital products.



- **[Unit21](https://www.unit21.ai/)**  

  Risk operations and orchestration platform focused on no-code rules, transaction monitoring, case management, and AI-assisted investigation workflows.



## Open-Source GitHub Projects

- **[Jube (AML & Fraud Transaction Monitoring)](https://github.com/jube-home/aml-fraud-transaction-monitoring)**  

  Fully open-source (AGPLv3) platform for real-time transaction monitoring, hybrid rule + ML detection, workflow-driven case management, and audit trails—designed for fraud and AML teams.



- **[RiskEngine](https://github.com/zhucl121/risk-engine)**  

  High-performance open-source risk decision engine in Go—RiskDSL, DAG pipelines, canary/champion-challenger/shadow modes, list lookups, and ONNX model scoring for real-time fraud decisioning.



- **[Databricks fraud-orchestration examples](https://github.com/databricks-industry-solutions/fraud-orchestration)**  

  Open notebooks demonstrating rule-based patterns combined with ML algorithms, anomaly detection, and unified analytics for fraud response.



- **[Rule engines open libraries](https://github.com/)**  

  Open business-rule engines used to encode velocity, blacklists, allowlists, and policy checks alongside ML scores in orchestration pipelines.



- **[Feature-store and event-streaming open stacks](https://github.com/)**  

  Kafka, Flink, Redis velocity counters, and feature-store patterns commonly used to feed real-time fraud orchestration.



- **[Graph databases and network analysis open tools](https://github.com/)**  

  Neo4j, NetworkX, and related tools for detecting linked accounts, devices, and collusive rings within orchestration workflows.



- **[Case management open workflows](https://github.com/)**  

  Lightweight open tools for queueing, investigating, escalating, and auditing suspected fraud cases.



- **[ONNX and model-serving open runtimes](https://github.com/)**  

  Open model servers used to score fraud models with low latency inside decision pipelines.



- **[Device and behavioral signal open collectors](https://github.com/)**  

  Community libraries for fingerprinting, bot detection, and behavioral telemetry that can feed open or commercial orchestrators.



- **[Documentation and research open repositories](https://github.com/)**  

  Papers, notebooks, and playbooks for building transparent, auditable fraud orchestration pipelines.



### Additional Strong Open-Source Options

- Deploying **Jube** for end-to-end monitoring, detection, and case management with full data ownership.

- Using **RiskEngine** or similar DSL-based engines for low-latency, declarative decision orchestration.

- Combining open rules + ML scoring with commercial identity or guarantee layers in hybrid architectures.

- Accepting that global identity networks, chargeback guarantees, consortium data, production SLAs, and polished no-code ops still favor commercial platforms (Sardine, Sift, Forter, Riskified, Feedzai, Unit21, SEON, Castle, etc.).

- Focusing open-source efforts on transparency, auditability, and control of decision logic for regulated environments.



**Frameworks for building custom systems**: Stream events and signals → enrich with device/velocity/graph features → evaluate via open rules + ML (RiskEngine / Jube) → route to accept / review / decline → manage cases in open or commercial workflows → continuously retrain and shadow-test. Suitable for organizations with strong engineering and risk-ops capacity. Most merchants and financial institutions rely on commercial fraud orchestration platforms for network effects, guarantees, and operational scale.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Fraud orchestration systems make high-stakes decisions affecting customers and financial risk. Incorrect models, rules, or workflows can cause losses, false declines, or discrimination. Open-source tools require careful validation, monitoring, bias assessment, and compliance with applicable laws. This list is not legal, compliance, or risk-management advice.



---

**Made for risk, payments, fintech, and fraud operations teams.**

Let's keep decisioning accurate, explainable, and as open as practical.
