# Enterprise GRC Sandbox: NIST SP 800-53 Compliance & Quantitative Risk Ledger

## 🛠️ Project Architecture & Scope
This repository houses a comprehensive, multi-tiered Governance, Risk, and Compliance (GRC) Sandbox engineered within an isolated Linux workstation. The system addresses two core disciplines of modern enterprise risk oversight: continuous compliance framework alignment and mathematical vulnerability quantification.

## 📊 Visual Workspace Previews

### 1. Compliance Register Framework (Tab 1)
Maps system configurations to formal **NIST SP 800-53 Rev. 5** controls:
- **NIST AC-2 (Access Control):** Documented Active Directory least-privilege security group structures.
- **NIST IA-3 (Identification & Authentication):** Tracked Wazuh SIEM/XDR network log monitoring pipelines.
- **NIST SC-7 (Boundary Protection):** Validated edge Next-Gen Firewall ingress/egress access rules.
- **Automation Layer:** Embedded strict drop-down Data Validation parameters linked to custom multi-condition Conditional Formatting triggers (Soft Green/Red) for real-time audit metric analysis.

![Compliance Register Panel](Screenshot%202026-09-17%20202101.png)

### 2. Quantitative Risk Assessment Matrix Calculator (Tab 2)
Tracks environment vulnerabilities via math formula cell script logic (`Likelihood (1-5) × Impact (1-5) = Calculated Risk Score`):
- **VULN-2026-01 (External Threat):** Outdated public Apache web server vulnerable to exploitation (Score: 20 - Critical).
- **VULN-2026-02 (Pipeline Threat):** Missing MFA boundaries on production engineer VPN portals (Score: 12 - High).
- **VULN-2026-03 (Insider Threat):** Active privilege creeping across core data backup nodes (Score: 10 - Medium).

![Risk Calculator Metrics Panel](Screenshot%202026-09-17%20202026.png)

---

## 📝 Executive Audit Summary Memo

**TO:** Senior Security Leadership & Enterprise Risk Stakeholders  
**FROM:** GRC Sandbox Information Security Assurance Lead  
**SUBJECT:** Internal Security Controls Alignment Audit & Quantitative Risk Assessment Report

### 1. Executive Summary
An internal technical assurance security audit was executed within the enterprise staging sandbox environment to evaluate our current defensive posture against formal regulatory baselines. Core information assets were assessed directly against the NIST SP 800-53 Rev. 5 control framework, while environmental vulnerabilities were quantitatively modeled utilizing a mathematical Likelihood × Impact threat vector metric ledger. 

The investigation successfully validated robust defensive implementations across enterprise perimeter boundaries and identity grouping access mappings. However, critical gaps were discovered involving legacy public infrastructure and critical engineering access pipelines, which demand immediate budget allocation and strategic mitigation remediation paths.

### 2. Strategic Roadmap Recommendations
The baseline control layer shows solid perimeter defense, but the presence of a Critical-tier vulnerability (Score 20) requires immediate mitigation. Security engineering teams must prioritize the patching of the legacy public Apache server within the next 48 hours. Concurrently, IAM teams should begin mapping out the enterprise IDP multi-factor rollout to eliminate the high-risk remote access vulnerabilities by the close of the upcoming operational sprint cycle.
