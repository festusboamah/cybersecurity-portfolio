# Security audit: Botium Toys

**Course project:** Google Cybersecurity Professional Certificate, Course 2 (*Play It Safe: Manage Security Risks*), portfolio activity "Conduct a security audit".
**Organisation:** Botium Toys, a **fictional** small U.S. toy company provided by the course.
**Deliverable:** [Controls and compliance checklist with recommendations (PDF)](controls-and-compliance-checklist.pdf)

## Scenario

Botium Toys has a single physical location (office, storefront and warehouse) and a growing online store with customers in the U.S. and the E.U. The IT manager asked for an internal audit to identify risks to critical assets and to check compliance with regulations for processing online payments and doing business in the E.U. The provided risk assessment rated the overall risk **8 out of 10**, mainly because of missing controls and incomplete compliance.

## What I did

1. Reviewed the audit scope, goals, asset list and risk assessment.
2. Assessed **14 security controls** across three categories (administrative, technical and physical) against the question *"Is this control currently in place?"*
3. Assessed **12 compliance best practices** under **PCI DSS**, **GDPR** and **SOC type 1 and type 2**.
4. Wrote **seven recommendations for the IT manager, ranked by risk**, plus a summary of existing strengths.

## Key findings

- **6 of 14 controls are in place:** firewall, antivirus, (unscheduled) monitoring of legacy systems, locks, CCTV and fire detection and prevention.
- **Missing or inadequate:** least privilege, separation of duties, encryption, backups, disaster recovery plan, intrusion detection, an adequate password policy and a password management system.
- **4 of 12 compliance best practices are met:** a 72-hour breach notification plan for E.U. customers, enforced privacy policies, data integrity and data availability.
- **Highest risk:** every employee can access cardholder data and customers' PII/SPII, and card data is not encrypted, which is a direct PCI DSS and GDPR exposure.

## Top recommendations (in priority order)

1. Restrict access to card data and PII/SPII with role-based access (least privilege, separation of duties).
2. Encrypt card data at rest and in transit.
3. Create and test backups of critical data; write a disaster recovery plan.
4. Add an intrusion detection system alongside the firewall.

The full list of seven recommendations is in the PDF.

## Notes

- This portfolio version was revised after I submitted the graded activity, using feedback, to correct three checklist entries and to rank the recommendations by risk.
- The checklist template and scenario are course materials from Google's Cybersecurity Certificate, included here as the course recommends for portfolio use.
