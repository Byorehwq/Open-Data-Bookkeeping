# Allocator Bookkeeping Repository for Rouge-Labs

## Allocator JSON Link
[Link to Rouge-Labs Allocator JSON](https://github.com/filecoin-project/Allocator-Registry/tree/main/Allocators/Rouge-Labs)  
*Note: Replace with the actual link to your allocator JSON once available in the Allocator-Registry.*

## Client Diligence
Rouge-Labs employs a robust client diligence process to verify clients and establish trust while mitigating Sybil attacks. Our verification includes:

- **Business Verification**: Clients must submit registration certificates, incorporation details, company documents, government-issued business ID numbers, and verification of authorized signers (e.g., board approval or CFO letters).
- **Personal Verification**: Individuals must provide a government-issued photo ID (e.g., passport) and a facial photo alongside the ID for identity confirmation.
- **Sybil Attack Mitigation**: To prevent Sybil attacks, we enforce rate limits on DataCap requests and cap total allocation at **1 PiB** per client. We cross-reference client information with public records and use tools like [DataCapStats.io](https://datacapstats.io) to monitor allocation patterns for suspicious activity.
- **Enterprise Data Ownership**: For enterprise clients, we verify data ownership through legal documentation, contracts, or attestations from authorized representatives. We maintain auditable records of all verification steps.
- **Audit Evidence**: All KYB/KYC documentation, allocation records, and communication logs are archived and made available to the Filecoin Plus (Fil+) Governance Team for auditing purposes.

## Description of Data Diligence
Rouge-Labs ensures that client data aligns with Filecoin Plus program scope and legal requirements through the following:

- **Data Ownership Verification**: Clients must provide evidence of data ownership, such as legal contracts, IP documentation, or signed attestations. For public datasets, we verify their open-access status via public repositories or trusted sources.
- **Legal Compliance**: We ensure data storage complies with local and regional regulations by requiring clients to confirm compliance with applicable laws. Data is distributed across **3–4 geographic regions** to meet jurisdictional diversity requirements.
- **Data Sampling**: We perform random sampling of stored data using the CID Checker Bot to verify that the data in storage deals matches client claims. We also use [DataCapStats.io](https://datacapstats.io) to monitor deal integrity and compliance.
- **Tools Used**: [DataCapStats.io](https://datacapstats.io) for allocation tracking and CID Checker Bot for content verification.
- **Audit Proof**: We maintain detailed logs of data sampling results, compliance checks, and storage deal metadata, which are available for review by the Fil+ Governance Team during audits.

## Short Description of Pathway for Clients
Choose Rouge-Labs for a transparent, efficient, and client-focused DataCap allocation process. We cater to a wide range of clients, from small-scale developers to enterprise data owners, supporting both public and private datasets with a focus on non-profit and social impact initiatives. Our rigorous KYB/KYC process ensures trust, while our phased allocation (10%–50%) and geographic distribution requirements guarantee secure, compliant data storage. With tools like [DataCapStats.io](https://datacapstats.io) and a responsive dispute resolution process, we prioritize accountability and ease of use for all clients.

## Contact Info
- **Slack**: Join our Slack channel at `#luster` for direct support.
- **Email**: Contact us at [byorehwq@ruilanit.cn](byorehwq@ruilanit.cn).
- **GitHub Issues**: Open an issue on our [GitHub repository](https://github.com/Byorehwq) for inquiries or support.

## Detailed Allocator Policies, Procedures, and Requirements
- **Target Clients**: Small-scale developers, enterprise data clients, individuals learning about Filecoin, and project-specific clients.
- **Supported Data Types**: Public open datasets (research/non-profit), public commercial/enterprise data, private commercial/enterprise data, and private non-profit/social impact data.
- **KYB/KYC Requirements**:
  - Business: Registration certificates, incorporation details, government-issued business IDs, and authorized signer verification.
  - Personal: Government-issued photo ID and facial photo with ID.
- **Storage Requirements**:
  - Minimum of **5 replicas** per dataset.
  - Data stored across **3–4 geographic regions**.
- **DataCap Distribution**:
  - Phase 1: 10%
  - Phase 2: 15%
  - Phase 3: 25%
  - Phase 4: 50%
  - Maximum allocation: **1 PiB** per client.
- **VPN Usage**: Permitted, but clients must ensure actual locations comply with geographic policies.
- **Verification Tools**: [DataCapStats.io](https://datacapstats.io) and CID Checker Bot.

## Risk Mitigation Strategies
To protect our organization, reputation, and pathway from abuse, Rouge-Labs implements the following:

- **Operational Security (OpSec)**: Secure storage of KYB/KYC data with encryption and access controls. Regular audits of internal systems to prevent data breaches.
- **User Agreements**: Clients must sign agreements outlining compliance with Filecoin Plus policies, geographic requirements, and data ownership responsibilities.
- **Rate Limiting**: DataCap allocation is capped at **1 PiB** per client, with phased distribution (10%–50%) to prevent overuse or abuse.
- **Alerts and Monitoring**: We use [DataCapStats.io](https://datacapstats.io) to monitor allocation patterns and flag anomalies. Suspicious activity triggers manual review.
- **Throttling Mechanisms**: Automated checks limit the frequency and volume of DataCap requests to prevent Sybil attacks or spam.

## Dispute Resolution
Rouge-Labs’ dispute resolution process is designed to be fast, transparent, and accountable:

- **Rapid Acknowledgment**: Disputes are acknowledged within **72 hours**.
- **Transparency**: All parties are kept informed throughout the process with clear communication.
- **Comprehensive Review**: We investigate disputes by reviewing DataCap allocation records, KYB/KYC compliance, and storage deal details.
- **Neutral Mediation**: If needed, a neutral third party is engaged to mediate disputes.
- **Accountability & Documentation**: All steps are documented for auditability and used to improve policies.
- **External Engagement**: For disputes involving other Notaries or the Fil+ Governance Team, we provide evidence and collaborate to resolve issues.

## Compliance Audit Check
To ensure compliance with program-wide and pathway-specific requirements:

- **Client Compliance**: We verify client KYB/KYC documentation and data ownership before allocation. Clients must confirm adherence to local and regional legal requirements.
- **Storage Provider Compliance**: We use [DataCapStats.io](https://datacapstats.io) and CID Checker Bot to confirm that storage providers meet the **5-replica** and **3–4 geographic region** requirements.
- **Regular Audits**: We conduct internal audits of allocation records, storage deals, and compliance documentation. These records are available for review by the Fil+ Governance Team.
- **Monitoring Tools**: Continuous monitoring via [DataCapStats.io](https://datacapstats.io) ensures ongoing compliance with program rules.
