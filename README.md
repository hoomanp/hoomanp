# Hooman Parta
**Principal Engineering Leader (MSFT L67) & Principal Architect | Cloud Platforms, SRE & AI Systems**  
*Former Senior Director of Engineering (Nuance) • Principal Engineering Manager (Microsoft) • CISSP*

[LinkedIn](https://www.linkedin.com/in/hooman-parta) • Los Angeles, CA / Remote

---

### Executive Overview
Engineering leader and Principal Architect with 25+ years of experience building and operating large-scale cloud platforms, SRE organizations, and regulated enterprise voice/AI infrastructure. Proven track record managing $40M+ infrastructure budgets and leading global organizations of 50+ engineers across NA, EMEA, and APAC through 5 engineering managers.

### Verified Production Scale & Organizational Impact
* **Global Organization & Talent Retention:** Led a 50+ engineer global platform and SRE organization across NA, EMEA, and APAC through 5 engineering managers; maintained 90% key talent retention through the Microsoft acquisition, kept voluntary attrition under 5%, and promoted 5 ICs into engineering management.
* **High-Availability Platform Scale (~1B Sessions/Month):** Owned platform reliability, cloud infrastructure, and production operations supporting ~1 billion monthly enterprise voice AI sessions at 99.9%+ availability.
* **Infrastructure Economics & Fleet Modernization ($40M+ Budget / 10,000+ Nodes):** Directed Architecture Review Board (ARB) decisions, build-vs-buy trade-offs, and data center consolidation across a $40M+ infrastructure budget, overseeing the migration of 10,000+ compute nodes to cloud-native Kubernetes with automated OpenSLO error budgets.

---

### Open-Source Reference Prototypes
*Hands-on architectural prototypes built to evaluate deterministic agent guardrails, inference routing unit economics, and closed-loop Kubernetes remediation on synthetic benchmarks.*

1. **[autonomy-boundary](https://github.com/hoomanp/autonomy-boundary) — Deterministic Policy Enforcement for AI Agents**
   * **Focus:** Enforcing an *"approved equals authorized"* runtime invariant across Model Context Protocol (MCP) servers and agent tool loops.
   * **Mechanism:** Canonicalizes tool payloads (`SHA-256`), validates state admissibility and Ed25519 approval tokens deterministically in <1 ms (zero LLM latency overhead), and fails closed on parameter drift. Verified against 72 automated invariant tests.

2. **[dispatch](https://github.com/hoomanp/dispatch) — Capability-Aware LLM Inference Router & FinOps Gateway**
   * **Focus:** Evaluating multi-tier model routing, prefix-aware caching, and latency circuit-breaking to control multi-step workflow inference costs.
   * **Mechanism:** Routes low-entropy intents to compact models while reserving frontier models for high-ambiguity reasoning, cutting synthetic benchmark workflow costs by ~68–80% while preserving quality tolerances.

3. **[kube-sre-vantage](https://github.com/hoomanp/kube-sre-vantage) — Closed-Loop Kubernetes SRE & Zero-Trust Remediation**
   * **Focus:** Combining OpenTelemetry anomaly correlation with short-lived, Just-In-Time (JIT) scoped tokens so automated remediation workflows never hold standing cluster-admin privileges.

---

### Core Competencies
* **Engineering Leadership:** Global Multi-Site Org Management (50+ engineers, 5 EMs), $40M+ Cloud & CapEx Budget Ownership, M&A Integration & Retention, Architecture Review Board (ARB) Governance.
* **Cloud & SRE:** Hyperscale Kubernetes (EKS, AKS, GKE), 10,000+ Node Migrations, OpenTelemetry, OpenSLO Error Budgets, Data Center Consolidation.
* **Security & Compliance:** CISSP Certified, Zero-Trust IAM/JIT Brokering, Regulated Enterprise Systems (HIPAA, SOC 2 Type II, PCI-DSS).
* **Technical Stack:** Python, Rust, Go, C++, Azure/AWS/GCP, Terraform, PyTorch.
