# Risk → Governance Control Mapping for Generative AI Systems (India)

## Purpose of the Control Mapping

This part turns known legal and data concerns into clear governance steps suitable for those building or using AI systems in India. To make safety a built-in feature, rules adherence, threat reduction, and responsibility are woven into every stage of an AI’s development and use.



A single control ties to one phase of the cycle, responding to threats found within India's data privacy, information technology, and intellectual property laws. While focused on timing, it also counters legal exposure shaped by national regulations. The structure ensures relevance through alignment - not overlap - with evolving compliance demands across sectors where digital activity meets statutory oversight.

---


## Risk–Control Mapping Table

| Lifecycle Stage | Identified Risk | Governance Control | Control Type | Implementation Responsibility |
|-----------------|----------------|--------------------|--------------|-------------------------------|
| **Data Collection** | Collection of more personal data than necessary | Limiting input fields and adding clear warnings at the prompt level | Technical + Policy | AI Developer / AI Deployer |
| Data Collection | Accidental capture of sensitive personal information | Clear user notices discouraging sharing of sensitive details | Policy | AI Deployer |
| Data Collection | Risk of unauthorized access or data leaks | Encrypted storage of logs and role-based access controls | Technical | AI Deployer |
| Data Collection | Inclusion of copyrighted material in user inputs | Terms of use restricting unlawful or copyrighted uploads | Legal + Policy | AI Deployer |
| **Labeling & Preprocessing** | Reuse of data beyond the original stated purpose | Purpose binding documentation and dataset usage notes | Governance | AI Developer |
| Labeling & Preprocessing | Bias introduced during annotation or tagging | Review checks and basic annotation guidelines | Process | AI Developer |
| Labeling & Preprocessing | Weak controls when using third-party vendors | Data processing agreements with audit and compliance clauses | Legal + Governance | AI Deployer |
| **Model Training & Fine-Tuning** | Memorization or reproduction of personal data | Use of privacy-aware training methods and basic testing | Technical | AI Developer |
| Model Training & Fine-Tuning | Use of copyrighted works in training data | Tracking data sources and providing exclusion mechanisms | Governance | AI Developer |
| Model Training & Fine-Tuning | Limited auditability of training processes | Maintaining training records and model documentation | Documentation | AI Developer |
| **Deployment & User Interaction** | Lack of transparency in AI behavior | High-level disclosures explaining system capabilities and limits | Policy | AI Deployer |
| Deployment & Interaction | Generation of harmful or unlawful content | Content moderation tools and response workflows | Technical + Process | AI Deployer |
| Deployment & Interaction | Risk of synthetic misinformation | Output labels or watermarking where technically feasible | Technical | AI Developer |
| **Decommissioning & Retention** | Retention of data beyond required duration | Defined retention timelines and deletion procedures | Governance | AI Deployer |
| Decommissioning & Retention | Security risks from legacy or outdated systems | Secure archiving or controlled system shutdown | Technical | AI Deployer |
| Decommissioning & Retention | Continued holding of copyrighted training data | Periodic dataset reviews and data purge steps | Governance | AI Developer |
---

## Key Design Principles Emerging from the Mapping

1. At each phase of the lifecycle, **safeguards are necessary** - deployment alone is insufficient.

2. One cannot escape the fact that those who build AI systems must **share duty** with those putting them into practice.

3. Getting things managed well means using tools from tech setups alongside **rules written in law** plus step-by-step methods.

4. Documentation and traceability are as important as model-level safeguards.


---

## Why This Mapping Enables Safety-by-Design

Through built-in oversight woven into how systems are shaped and run

Staying within legal boundaries shifts toward anticipation instead of response. Rules are followed before issues arise, not after. This approach prevents problems by acting early. Attention moves to what might happen, guiding decisions ahead of time. Outcomes improve when actions align with regulations in advance

- Risks are mitigated before harm occurs

- Accountability is clearly assigned across actors



Starting differently, this method shifts from theoretical moral debates to practical frameworks that fit how institutions in India operate. Instead of staying conceptual, it builds tools real organizations can apply within their existing structures.


---

## How This Feeds the Final Outputs

This control mapping directly supports:
- Functional governance checklists for developers  
- Policy-grade recommendations  
- Compliance readiness assessments for AI systems  
