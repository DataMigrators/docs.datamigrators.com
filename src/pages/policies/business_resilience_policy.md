---
title: Business Resilience Policy
description: Our business resilience policy
keywords: 'policy,business resilience,security,markdown'
---

<PageDescription>

This page describes Data Migrators' business resilience policy.

</PageDescription>

<AnchorLinks>
    <AnchorLink>Purpose and Scope</AnchorLink>
    <AnchorLink>Resilience Objectives</AnchorLink>
    <AnchorLink>Governance and Roles</AnchorLink>
    <AnchorLink>Critical Business Functions (CBF)</AnchorLink>
    <AnchorLink>Resilience Strategy</AnchorLink>
    <AnchorLink>Testing and Maintenance</AnchorLink>
    <AnchorLink>Communication Plan</AnchorLink>
</AnchorLinks>

# Business Resilience Policy

## 1. Purpose and Scope
The purpose of this policy is to ensure that Data Migrators can anticipate, prepare for, respond to, and adapt to incremental change and sudden disruptions. This policy ensures the continuity of our software services and the protection of customer data.

**Scope:** This policy applies to all employees, contractors, and third-party vendors. It covers all physical operations and cloud-hosted environments (e.g., AWS, Azure, GCP).

## 2. Resilience Objectives
Our goal is to protect our people, our reputation, and our customers' data. We aim to achieve the following metrics:

* **Recovery Time Objective (RTO):** Critical customer-facing services must be restored within **4 business hours** of a declared disaster.
* **Recovery Point Objective (RPO):** Maximum allowable data loss is **1 hour** of transactions.
* **Availability:** Maintain a service level agreement (SLA) of **99.9%** uptime.

## 3. Governance and Roles

| Role | Responsibility |
| :--- | :--- |
| **Resilience Committee** | Executive oversight, policy approval, and budget allocation. |
| **Incident Response Team (IRT)** | Immediate technical and operational response to a live threat. |
| **Product/DevOps Lead** | Ensuring software architecture supports high availability and DR. |
| **Customer Success** | Managing communication with clients during service disruptions. |

## 4. Critical Business Functions (CBF)
The following functions are prioritized for recovery in the event of a disruption:

1.  **SaaS Platform Availability:** The primary software product used by customers.
2.  **Customer Support Systems:** Ticketing and communication channels.
3.  **Software Development Pipeline:** CI/CD tools required for security patching.
4.  **Financial Operations:** Payroll and accounts receivable/payable.

## 5. Resilience Strategy

### 5.1 Infrastructure & Data Resilience (DR)
* **Redundancy:** Utilize multi-availability zone (Multi-AZ) or multi-region deployments for production databases.
* **Backups:** Automated, encrypted backups performed daily, with point-in-time recovery (PITR) enabled.
* **Off-site Storage:** Backups must be stored in a separate logical account or region from production.

### 5.2 Operational Resilience (BC)
* **Remote Work Capability:** All staff must be equipped to work 100% remotely with secure VPN/SSO access.
* **Key Personnel Risk:** Document "Runbooks" for critical tasks to ensure operations can continue if a key engineer is unavailable.
* **Third-Party Risk:** Maintain a registry of "Critical Sub-processors" (e.g., Cloud Provider, Auth0, Stripe) and review their SOC2/Resilience reports annually.

### 5.3 Cyber Resilience
* **Immutable Logs:** Maintain tamper-proof audit logs to detect and recover from ransomware.
* **Security Patches:** Critical security vulnerabilities in the software must be patched within **[e.g., 24-48]** hours.

## 6. Testing and Maintenance
A plan is only as good as its last test. Data Migrators commits to:

* **Tabletop Exercises:** Annual walkthroughs of "What-if" scenarios (e.g., AWS Region outage, Ransomware).
* **DR Drills:** Semi-annual technical failover tests to confirm RTO/RPO targets are met.
* **Policy Review:** This policy is reviewed annually or after any major architectural change.

## 7. Communication Plan
In the event of a disruption affecting customers:

* **Internal:** Alert the IRT via **Slack**.
* **External:** Update the public Status Page within **15 minutes**.
* **Direct:** Email affected customers if the outage exceeds **1 hour**.