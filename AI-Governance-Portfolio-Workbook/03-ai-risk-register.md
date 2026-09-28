[← Previous: AI Inventory](./02-ai-inventory.md) · Page 3 of 6 · [Next: Gap Assessment →](./04-gap-assessment.md)

---

# AI Risk Register

Eight risks identified across the six inventoried systems. Scoring uses a 1–5 Likelihood × Impact scale for both inherent and residual risk, with residual risk calculated after existing controls.

## Register Summary

| Risk ID | System | Category | Inherent Score | Residual Score | Residual Rating | Status |
|---|---|---|---:|---:|---|---|
| R-001 | Recruitment Screening Tool | Fairness | 20 | 8 | Medium | Open |
| R-002 | Microsoft 365 Copilot | Privacy / Security | 15 | 8 | Medium | In Progress |
| R-003 | Customer Support Chatbot | Reliability | 12 | 6 | Medium | In Progress |
| R-004 | Security Log Triage Agent | Agentic / Security | 15 | 8 | Medium | Open |
| R-005 | Invoice Anomaly Detector | Performance | 9 | 4 | Low | Open |
| R-006 | Meeting Transcription Assistant | Privacy | 12 | 6 | Medium | Open |
| R-007 | Customer Support Chatbot | Security | 16 | 12 | High | Open |
| R-008 | Microsoft 365 Copilot | Human Factors | 12 | 9 | Medium | Open |

## R-001 — Biased Recruitment Ranking

| Field | Detail |
|---|---|
| System | AI-003, Recruitment Screening Tool |
| Risk Statement | Biased ranking could disadvantage qualified candidates. |
| Category | Fairness |
| Affected Stakeholders | Applicants, recruiters |
| Inherent Likelihood / Impact / Score | 4 / 5 / **20** |
| Current Controls | Human review; periodic outcome testing; vendor documentation |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 4 / **8** |
| Residual Rating | Medium |
| Risk Owner | Head of Talent Acquisition |
| Treatment | Mitigate |
| Action | Complete independent bias test and define appeal route |
| Target Date | 2026-09-15 |
| Status | Open |
| Evidence | Bias test report; review records |
| Framework Link | EU AI Act; NIST MAP/MEASURE; ISO 42001 impact assessment |

## R-002 — Copilot Sensitive Content Exposure

| Field | Detail |
|---|---|
| System | AI-001, Microsoft 365 Copilot |
| Risk Statement | Sensitive content could be exposed through poor permissions or sharing. |
| Category | Privacy / Security |
| Affected Stakeholders | Employees, clients |
| Inherent Likelihood / Impact / Score | 3 / 5 / **15** |
| Current Controls | Tenant controls; sensitivity labels; access reviews |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 4 / **8** |
| Residual Rating | Medium |
| Risk Owner | Digital Workplace Lead |
| Treatment | Mitigate |
| Action | Review oversharing and high-risk repositories |
| Target Date | 2026-10-01 |
| Status | In Progress |
| Evidence | Access review; label policy; monitoring logs |
| Framework Link | NIST GOVERN/MANAGE; ISO 42001 controls |

## R-003 — Chatbot Incorrect Answers

| Field | Detail |
|---|---|
| System | AI-002, Customer Support Chatbot |
| Risk Statement | Incorrect answers could mislead customers or create service harm. |
| Category | Reliability |
| Affected Stakeholders | Customers |
| Inherent Likelihood / Impact / Score | 4 / 3 / **12** |
| Current Controls | Approved knowledge base; escalation; response monitoring |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 3 / **6** |
| Residual Rating | Medium |
| Risk Owner | Customer Service Manager |
| Treatment | Mitigate |
| Action | Add high-risk topic blocklist and quality sampling |
| Target Date | 2026-09-30 |
| Status | In Progress |
| Evidence | Sample results; escalation logs |
| Framework Link | EU AI Act transparency; NIST MEASURE/MANAGE |

## R-004 — Security Agent Excessive Permissions

| Field | Detail |
|---|---|
| System | AI-005, Security Log Triage Agent |
| Risk Statement | Excessive permissions could cause unintended system actions. |
| Category | Agentic / Security |
| Affected Stakeholders | IT operations, customers |
| Inherent Likelihood / Impact / Score | 3 / 5 / **15** |
| Current Controls | Least privilege; approval gate; action logging; sandbox |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 4 / **8** |
| Residual Rating | Medium |
| Risk Owner | SOC Manager |
| Treatment | Mitigate |
| Action | Test kill switch and quarterly permission review |
| Target Date | 2026-09-05 |
| Status | Open |
| Evidence | Permission review; test results; audit logs |
| Framework Link | NIST MANAGE; ISO 42001 operational controls |

## R-005 — Invoice Detector Model Drift

| Field | Detail |
|---|---|
| System | AI-004, Invoice Anomaly Detector |
| Risk Statement | Model drift could reduce detection accuracy and delay valid payments. |
| Category | Performance |
| Affected Stakeholders | Finance, suppliers |
| Inherent Likelihood / Impact / Score | 3 / 3 / **9** |
| Current Controls | Monthly performance review; analyst validation |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 2 / **4** |
| Residual Rating | Low |
| Risk Owner | Finance Operations Lead |
| Treatment | Monitor |
| Action | Define drift thresholds and retraining trigger |
| Target Date | 2026-09-30 |
| Status | Open |
| Evidence | Performance dashboard; validation records |
| Framework Link | NIST MEASURE; ISO 42001 monitoring |

## R-006 — Transcript Retention Exposure

| Field | Detail |
|---|---|
| System | AI-006, Meeting Transcription Assistant |
| Risk Statement | Transcripts could be retained or accessed beyond business need. |
| Category | Privacy |
| Affected Stakeholders | Meeting participants |
| Inherent Likelihood / Impact / Score | 3 / 4 / **12** |
| Current Controls | Restricted access; retention setting; user notification |
| Control Effectiveness | 3 |
| Residual Likelihood / Impact / Score | 2 / 3 / **6** |
| Residual Rating | Medium |
| Risk Owner | Collaboration Services Lead |
| Treatment | Mitigate |
| Action | Document consent and retention standard |
| Target Date | 2026-10-15 |
| Status | Open |
| Evidence | Retention policy; access logs |
| Framework Link | UK privacy principle; ISO 42001 data controls |

## R-007 — Chatbot Prompt Injection

| Field | Detail |
|---|---|
| System | AI-002, Customer Support Chatbot |
| Risk Statement | Prompt injection could manipulate retrieval or reveal restricted content. |
| Category | Security |
| Affected Stakeholders | Customers, organisation |
| Inherent Likelihood / Impact / Score | 4 / 4 / **16** |
| Current Controls | Input filtering; scoped retrieval; red-team testing |
| Control Effectiveness | 2 |
| Residual Likelihood / Impact / Score | 3 / 4 / **12** |
| Residual Rating | **High** |
| Risk Owner | Customer Service Manager |
| Treatment | Mitigate |
| Action | Segment knowledge index and strengthen retrieval authorization |
| Target Date | 2026-09-20 |
| Status | Open |
| Evidence | Red-team report; retrieval logs |
| Framework Link | NIST MANAGE; secure-by-design |

> R-007 is the only risk in this register with a **High** residual rating — the lowest control effectiveness score (2) in the register despite a high inherent score (16), making it the top remediation priority.

## R-008 — Copilot Hallucination Reliance

| Field | Detail |
|---|---|
| System | AI-001, Microsoft 365 Copilot |
| Risk Statement | Users may rely on hallucinated or incomplete output without verification. |
| Category | Human Factors |
| Affected Stakeholders | Employees, decision-makers |
| Inherent Likelihood / Impact / Score | 4 / 3 / **12** |
| Current Controls | User guidance; citations; human review |
| Control Effectiveness | 2 |
| Residual Likelihood / Impact / Score | 3 / 3 / **9** |
| Residual Rating | Medium |
| Risk Owner | Digital Workplace Lead |
| Treatment | Mitigate |
| Action | Launch AI literacy module and verification checklist |
| Target Date | 2026-09-30 |
| Status | Open |
| Evidence | Training records; guidance document |
| Framework Link | EU AI Act Article 4; NIST GOVERN |

---

[← Previous: AI Inventory](./02-ai-inventory.md) · Page 3 of 6 · [Next: Gap Assessment →](./04-gap-assessment.md)
