# Rafat Yazdani

**I design decision systems that translate security risk into business action.**

CPA · CISSP · CISA · CCSK · AWS Certified · 11+ years in security strategy, cyber risk quantification, and audit
Currently: Security Strategy Manager, Accenture Security

---

## The thesis

Most cybersecurity work stops at *"here's the gap."* Leadership then has to guess what to do first. I build the layer between the two — the tools, models, and frameworks that turn technical risk into financial decisions a CFO, board, or audit committee can actually act on.

This portfolio is a five-layer stack: **methodology → quantification math → consulting products → governance & maturity → operations → board output**. Each repo below sits in exactly one layer.

---

## The stack

| Layer | Question it answers | Primary artifacts |
|---|---|---|
| **Methodology** | Why is current CRQ broken in the market? | [CRQ-F Framework](https://github.com/rafatyazdani/crq-f-framework) · [CRQ Gaps Master](https://github.com/rafatyazdani/crq-f-framework) |
| **Quantification math** | What is our cyber risk in dollars, transparently? | [cyber-risk-quantification](https://github.com/rafatyazdani/cyber-risk-quantification) (Python notebooks + Streamlit) · [cyber-roi-calculator](https://github.com/rafatyazdani/cyber-roi-calculator) (control ROI with decay curves) · [excel-cyber-risk-models](https://github.com/rafatyazdani/excel-cyber-risk-models) (teaching + production Monte Carlo) |
| **Consulting products** | What does this look like deployed for a client? | [CRQ-Dashboard](https://github.com/rafatyazdani/CRQ-Dashboard) (multi-client FastAPI + React) · [fintech-security-dashboard](https://github.com/rafatyazdani/fintech-security-dashboard) (segment-specific, DORA-aware) |
| **Governance & maturity** | How do I score, govern, and run the program? | [maturity-scoring-engine](https://github.com/rafatyazdani/maturity-scoring-engine) (NIST CSF 2.0 / CIS v8 / ISO 27001) · [ai-governance-toolkit](https://github.com/rafatyazdani/ai-governance-toolkit) (NIST AI RMF / EU AI Act / ISO 42001) · [cloud-security-governance](https://github.com/rafatyazdani/cloud-security-governance) (Terraform IaC) |
| **Operations** | How does a CISO actually use it Monday morning? | [security-issues-prioritization](https://github.com/rafatyazdani/security-issues-prioritization) (AI-augmented finding → ranked backlog) · [security-risk-register](https://github.com/rafatyazdani/security-risk-register) (operational Excel workflow) · [compliance-copilot](https://github.com/rafatyazdani/compliance-copilot) (regulatory remediation AI) |
| **Board output** | What does the audit committee see in 10 seconds? | [cyber-risk-dashboard](https://github.com/rafatyazdani/cyber-risk-dashboard) (single-page HTML board view) |

---

## Start here

If you're scanning this for ninety seconds, open these three first:

1. **[cyber-risk-dashboard](https://github.com/rafatyazdani/cyber-risk-dashboard)** — the board view. Single HTML file, opens in any browser. This is the output everything else is in service of.
2. **[CRQ-Dashboard](https://github.com/rafatyazdani/CRQ-Dashboard)** — the consulting product. Multi-client, PERT Monte Carlo, PDF export, unit tested.
3. **[CRQ-F Framework](https://github.com/rafatyazdani/crq-f-framework)** — the methodology underneath everything else. Five phases, five structural gaps in current CRQ practice, five LinkedIn essays.

---

## What I'm trying to solve

Every cyber risk practitioner I've met can describe the gaps. Almost none can sit with a CFO, a CISO, and an audit committee in the same week and translate fluently between all three. The CPA + CISSP + CISA combination, plus eleven years of work that spans Big 4 audit (BDO, EY), specialist attestation (Schellman), and digital-native strategy consulting (Accenture), is the moat — and these artifacts are the proof of work, not just claims on a resume.

The five gaps the CRQ-F Framework names:

- **G1 — Input data is fabricated, not measured.** Every FAIR model uses industry averages because no one has built the telemetry-to-FAIR-input mapping layer.
- **G2 — Control ROI is asserted, not demonstrated.** Vendors claim X% effectiveness; almost no one measures actual pre/post risk movement.
- **G3 — Models are static, decisions are dynamic.** A January risk model used for October budget decisions is not risk management — it's historical fiction with charts.
- **G4 — The translation layer between technical and financial is manual.** MITRE → CIS → NIST → FAIR → ALE is a chain no tool can walk; it requires judgment at each step.
- **G5 — Board output is not decision-ready.** Heat maps don't tell a board whether to raise the insurance limit. A risk P&L does.

Each artifact in the stack above implements one or more of these gaps.

---

## Credentials

- **CPA (Texas)** — September 2015
- **CISSP** — July 2021
- **CISA** — May 2020
- **CCSK** — August 2020
- **AWS Certified Cloud Practitioner** — November 2022
- **B.B.A. Accounting + Minor in MIS** — University of Texas at Austin, McCombs School of Business

## Stack

Python · FAIR (Open FAIR / O-RA, O-RT) · Monte Carlo (NumPy, SciPy) · Streamlit · FastAPI · React · Terraform · AWS (Security Hub, Config, GuardDuty, IAM, SCPs) · Anthropic Claude API · Ollama · NIST CSF 2.0 · CIS Controls v8 · ISO/IEC 27001:2022 · NIST AI RMF · EU AI Act · ISO/IEC 42001:2023 · DORA · NYDFS · PCI DSS · GDPR · HIPAA · SOC 2 · ServiceNow GRC · Drata · Vanta · Archer

---

## Get in touch

- LinkedIn: [linkedin.com/in/rafatyazdani](https://www.linkedin.com/in/rafatyazdani)
- Email: rafat.yazdani@utexas.edu
