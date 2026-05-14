# AI Vendor Risk & Governance Assessment

## Project Overview
This project demonstrates an AI governance and vendor risk assessment aligned with the **NIST AI Risk Management Framework (AI RMF)**. The assessment evaluates risks associated with a third-party AI healthcare diagnostic system used for patient triage and healthcare support.

The project focuses on:
* AI Governance & Policy
* Third-Party/Vendor Risk Management (TPRM)
* Algorithmic Bias & Fairness Evaluation
* Privacy and Security Risk Mitigation

## Assessment Scope
### Target System
**HealthAI Diagnostics** — A third-party AI-powered healthcare diagnostic assistant used to support patient triage decisions.

### Assessment Objectives
* Identify potential AI-related risks (Bias, Hallucinations, Privacy)
* Evaluate vendor governance and transparency practices
* Recommend technical and administrative security controls
* Document mitigation strategies for high-risk findings

## Potential Risks & Harms
| Risk Area | Potential Harm |
| :--- | :--- |
| **Incorrect Diagnosis** | Patient harm due to inaccurate medical recommendations |
| **Algorithmic Bias** | Unequal treatment across demographic groups (Race, Age, Gender) |
| **Data Privacy** | Exposure of protected health information (PHI) |
| **Hallucinations** | AI-generated false or misleading medical information |
| **Security Risks** | Unauthorized access to sensitive patient datasets |

## Key Findings & Risk Rating
**Final Vendor Risk Rating: HIGH RISK**

### Justification
The AI system influences patient care decisions and processes sensitive healthcare data. The lack of transparency regarding training datasets and the potential for algorithmic bias create elevated compliance concerns that require strict human-in-the-loop oversight.

## Recommended Governance Controls
* **Human-in-the-loop (HITL):** Clinical review required for all AI-generated triage decisions.
* **Bias Monitoring:** Quarterly audits of diagnostic outcomes across demographics.
* **Access Control:** Multi-factor authentication (MFA) and RBAC for all system users.
* **Continuous Monitoring:** Periodic vendor reassessments to track model drift.

## Files Included
| File | Description |
| :--- | :--- |
| [Vendor-Risk-Questionnaire.md](./Vendor-Risk-Questionnaire.md) | AI-specific audit questions for third-party vendors |
| [Bias-Impact-Assessment.md](./Bias-Impact-Assessment.md) | Simulated analysis of fairness and algorithmic bias |
| [Risk_Register_Dashboard.xlsx](../Risk-Assessment-Project/Cybersecurity_Risk_Register.xlsx) | Master Risk Register and mitigation tracking |
| [GRC_Workflow_Diagram.png](../Risk-Assessment-Project/GRC_Risk_Workflow_Diagram.png) | Visualization of the risk management lifecycle |

## Framework Alignment
* **NIST AI Risk Management Framework (AI RMF)**
* **NIST Cybersecurity Framework (CSF)**
* **HIPAA Security Rule** (Technical Safeguards)

## Skills Demonstrated
* Vendor Risk Management (TPRM)
* AI Policy & Governance
* Risk Quantification & Mitigation
* Compliance Reporting
