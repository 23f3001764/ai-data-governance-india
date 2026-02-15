# Regulation → Risk Mapping Across the AI Data Lifecycle (India)

## Purpose of the Mapping

One way to begin: understanding India's laws helps pinpoint vulnerabilities tied to data in public generative AI. Where rules apply often matches moments when misuse could occur. Legal requirements emerge not just at launch, but throughout operation. Risks appear during design, training, deployment, even after updates. Each phase carries distinct exposure - some linked to privacy, others to misinformation or bias. Oversight becomes necessary because automated systems can amplify harm silently. Attention shifts depending on whether data enters, moves through, or exits the model. Prevention hinges on recognizing weak points before incidents happen. Governance gaps may allow breaches that regulations aim to close. Moments matter more than intentions here.

A connection emerges here, linking legal mandates with how artificial intelligence is managed in practice. While rules set boundaries, daily operations shape their real-world effect.

---

## Regulation–Lifecycle Risk Mapping Table

| Lifecycle Stage | Applicable Regulation | Legal Obligation / Principle | Primary Risk Introduced | Why This Risk Matters |
|-----------------|----------------------|------------------------------|-------------------------|-----------------------|
| **Data Collection** | DPDP Act 2023 | Lawful purpose, consent or legitimate use, notice to data principals | Over-collection of personal data | Excessive or unclear data intake violates purpose limitation and erodes user trust |
| Data Collection | DPDP Act 2023 | Data minimization | Incidental capture of sensitive personal data | Users may unknowingly disclose sensitive information in prompts |
| Data Collection | IT Act 2000 & IT Rules | Reasonable security practices | Unauthorized access or data leakage | Breaches expose personal and confidential user data |
| Data Collection | Copyright Act 1957 | No explicit exception for unrestricted data ingestion | Collection of copyrighted content | User prompts may contain copyrighted text or proprietary material |
| **Labeling & Preprocessing** | DPDP Act 2023 | Purpose limitation and processing safeguards | Secondary use beyond original purpose | Repurposing data without legal basis creates compliance gaps |
| Labeling & Preprocessing | DPDP Act 2023 | Accuracy and fairness | Bias introduction during annotation | Human labeling choices may embed cultural or social bias |
| Labeling & Preprocessing | IT Act 2000 | Processor accountability | Weak vendor controls | Third-party processors increase exposure to misuse or leaks |
| **Model Training & Fine-Tuning** | DPDP Act 2023 | Protection against re-identification | Memorization of personal data | Models may unintentionally reproduce personal information |
| Model Training & Fine-Tuning | Copyright Act 1957 | Reproduction and adaptation rights | Training on copyrighted works | Lack of clarity on fair use for AI training increases legal uncertainty |
| Model Training & Fine-Tuning | IT Act 2000 | Due diligence obligations | Lack of auditability | Inability to explain training sources weakens accountability |
| **Deployment & User Interaction** | DPDP Act 2023 | Transparency and grievance redressal | Opaque AI behavior | Users cannot challenge harmful or incorrect outputs |
| Deployment & Interaction | IT Act 2000 | Intermediary responsibility | Harmful or illegal content generation | Generative AI may amplify misinformation or unlawful speech |
| Deployment & Interaction | Emerging AI & Deepfake Guidelines | Content safety and misuse prevention | Synthetic misinformation | AI outputs may mislead, impersonate, or manipulate |
| **Decommissioning & Retention** | DPDP Act 2023 | Storage limitation and right to erasure | Excessive data retention | Retained logs create long-term compliance and breach risks |
| Decommissioning & Retention | IT Act 2000 | Security of stored data | Legacy system vulnerabilities | Old systems often lack updated safeguards |
| Decommissioning & Retention | Copyright Act 1957 | Continued possession of protected works | Unlawful retention of copyrighted data | Retained training data may violate ownership rights |

---

## Observations from the Mapping

1. From design onward, Indian rules on AI apply - extending well beyond just launch stages.

2. When data flows begin, the DPDP Act takes center stage - its influence fades once models deploy. Security threats, however, fall largely under the IT Act's reach. Training phases stir DPDP scrutiny; live systems face different legal shadows. Retention periods keep the DPDP relevant, yet breaches awaken older rules.

3. Still unclear by design, copyright issues around AI learning lack fixed solutions. Legal uncertainty sticks around because rules have not caught up.

4. Because users constantly create new data, generative AI systems face growing exposure to potential harms.
---

## Why This Mapping Is Foundational

This mapping enables:
- Systematic identification of data-related risks  
- Lifecycle-specific governance control design  
- Translation of abstract legal duties into functional AI requirements  

All subsequent control frameworks and policy recommendations in this project derive directly from this mapping.
