# Awesome-Cloud-Infrastructure-Entitlement-Management-CIEM

# Awesome-Cloud-Infrastructure-Entitlement-Management-CIEM



**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Cloud Permissions Analysis, Least-Privilege Automation & Identity Risk*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Cloud Infrastructure Entitlement Management (CIEM)**. These tools help security teams gain visibility into permissions assigned to human and non-human identities, detect excessive access, and automate least-privilege enforcement across AWS, Azure, and GCP.



**Examples** include Microsoft Entra Permissions Management, Wiz, CyberArk Cloud Entitlements Manager, Ermetic (Tenable), Palo Alto Prisma Cloud CIEM, Britive, Sonrai Security, Zilla Security, Authomize, and Orca Security (the category leaders).



**Open-source emphasis**: CIEM has a **mature open-source ecosystem at the discovery and analysis layers**. **Prowler** provides the broadest multi-cloud assessment with **65% coverage across 57 documented AWS IAM privilege escalation paths** . **Cloudsplaining** (Salesforce) and **PMapper** (NCC Group) offer complementary AWS IAM analysis at **35%** and **33%** coverage respectively . **policy_sentry** enables preventative least-privilege policy generation from YAML templates . **Cartography** and **CloudQuery** provide the underlying graph and SQL data structures for advanced analysis . This section documents these production-grade solutions.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## 📖 Table of Contents



- [☁️ SaaS/Hosted Platforms](#-saas-hosted-platforms)

- [🔓 Open-Source GitHub Projects](#-open-source-github-projects)

- [🤝 How to Contribute](#-how-to-contribute)

- [⚠️ Disclaimer](#-disclaimer)



## ☁️ SaaS/Hosted Platforms



> **📊 Market Context**: The global CIEM market is estimated at **~$2.5B in 2026**, growing toward **~$7B by 2030** at a **~28% CAGR**. The sector is **moderately concentrated** — **Wiz** was acquired by Google for **$32B** after crossing **$1B ARR in 2025** , while **Ermetic** was acquired by Tenable , **Zilla Security** by CyberArk for **$175M** (with **$5M ARR** and **125+ enterprise customers** as of December 2024) , and **Authomize** by Delinea . **Orca Security** is a **unicorn valued at $1–2.5B** with **$100–500M revenue** . **Sonrai Security** generates **$18.4M revenue** with **$38.5M funding** . **Britive** generates **$2.8M revenue** with **$35.9M funding** . No single vendor holds a winner-take-all position; enterprises typically run multi-vendor CIEM stacks alongside CNAPP platforms.



| Platform | Description | Pricing (Starting Tier) | Free Tier Limits | Company Size |

|----------|-------------|------------------------|------------------|--------------|

| **[Wiz](https://www.wiz.io/)** | **The fastest-growing CNAPP with CIEM capabilities.** Agentless-first architecture correlating permissions across compute, identity, network, and data. **Wiz Defend** provides cloud detection and response. **Acquired by Google for $32B**. | **Enterprise pricing** — quote required. Typical contracts exceed **$100K/year** for mid-size deployments. | **None** — enterprise demo required. | **$32B acquisition, $1B ARR (2025)**  |

| **[Microsoft Entra Permissions Management](https://www.microsoft.com/en-us/security/business/identity-access/microsoft-entra-permissions-management)** | Microsoft's CIEM solution providing comprehensive visibility into permissions assigned to all identities (users and workloads) across Azure, AWS, and GCP. Detects, right-sizes, and monitors unused and excessive permissions for Zero Trust least-privilege access. | **$125 per resource per year** (based on Forrester TEI study: 700 resources = $87,500/year; 1,600 resources = $200,000/year) . | **None** — trial available via Azure. | **~$281B revenue (Microsoft FY2025)** |

| **[CyberArk Cloud Entitlements Manager](https://www.cyberark.com/)** | AI-powered cloud permissions management enforcing least privilege across multi-cloud. **No VM footprint required.** Detects and remediates risky, unused, and misconfigured IAM permissions for human and machine identities. **Acquired Zilla Security for $175M** (February 2025). | **Custom pricing** — quote required. Enterprise add-on to CyberArk Identity Security Platform . | **None** — enterprise demo required. | **~$700M revenue (CyberArk FY2025 est.)** |

| **[Ermetic (Tenable Cloud Security)](https://www.tenable.com/)** | **Best-in-class dedicated CIEM** with granular identity analysis, automated least-privilege recommendations, and cross-cloud identity correlation. **Acquired by Tenable**. | **Custom enterprise pricing** — quote required. | **None** — enterprise demo required. | **Part of Tenable (~$900M revenue est.)**  |

| **[Palo Alto Prisma Cloud CIEM](https://www.paloaltonetworks.com/prisma/cloud)** | CIEM module within Prisma Cloud CNAPP. Named a **Leader and Outperformer in CIEM by GigaOm**. Multi-cloud permissions management with graph visualization. | **Custom enterprise pricing** — bundled with Prisma Cloud. Typical Prisma Cloud contracts exceed **$100K/year**. | **None** — enterprise demo required. | **~$9.2B revenue (Palo Alto FY2025)** |

| **[Orca Security](https://orca.security/)** | **Agentless-first CNAPP with CIEM capabilities.** SideScanning technology reads cloud workload block storage out-of-band to detect vulnerabilities, malware, and misconfigurations without agents. **Unicorn valued at $1–2.5B**. | **Custom enterprise pricing** — quote required. Typical contracts in **$50K–$200K/year** range. | **None** — enterprise demo required. | **$1–2.5B valuation, $100–500M revenue**  |

| **[Sonrai Security](https://sonraisecurity.com/)** | **Cloud Permissions Firewall and CIEM platform.** Provides visibility into unused permissions, identities, services, and regions across AWS Organizations. Automates least-privilege enforcement with ChatOps on-demand permissions. | **Custom enterprise pricing** — quote required. Entry contracts typically start at **~$50K/year**. | **None** — enterprise demo required. | **$18.4M revenue, $38.5M funding, $183.8M valuation**  |

| **[Britive](https://www.britive.com/)** | **Cloud-native privileged access management with JIT access.** Multi-cloud PAM for AWS, Azure, GCP, and SaaS. Eliminates standing privileges via dynamic, on-demand access. | **Custom enterprise pricing** — quote required. Entry contracts typically start at **~$25K/year**. | **None** — enterprise demo required. | **$2.8M revenue, $35.9M funding**  |

| **[Zilla Security](https://www.zillasecurity.com/)** | **AI-powered identity governance and CIEM platform.** Automates access reviews, entitlement discovery, and least-privilege enforcement. **Acquired by CyberArk for $175M** (February 2025). | **Custom enterprise pricing** — quote required. | **None** — acquired, now part of CyberArk. | **$5M ARR, 125+ enterprise customers, $175M acquisition**  |

| **[Authomize](https://www.authomize.com/)** | **Cloud identity and access management platform with CIEM capabilities.** **Acquired by Delinea** (2024) to accelerate CIEM and ITDR capabilities. | **Custom enterprise pricing** — quote required. | **None** — acquired, now part of Delinea. | **Private (acquired by Delinea)**  |



## 🔓 Open-Source GitHub Projects



Sorted by star count (descending). Star badge links to each repo's stargazers page.



| Repo | Description | Stars |

|---|---|---|

| **[Prowler](https://github.com/prowler-cloud/prowler)** — **The most widely used open-source CIEM and cloud security assessment platform.** Covers AWS, Azure, GCP, Kubernetes, M365, GitHub, Okta, and more with **800+ checks** mapped to CIS benchmarks and NCSC Cyber Essentials 3.3 . **65% coverage** across 57 documented AWS IAM privilege escalation paths . **Prowler Cloud** offers 15-day free trial with pay-per-account pricing . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/prowler-cloud/prowler?style=social&color=white)](https://github.com/prowler-cloud/prowler/stargazers) | ~13,000 |

| **[Cartography (Lyft)](https://github.com/lyft/cartography)** — **Infrastructure graphing and querying platform.** Ingests cloud assets into a **Neo4j graph database** to enable cross-boundary queries. Provides the underlying data structure for advanced entitlement analysis—map identities, resources, and their relationships for "who can reach what" analysis . Apache-2.0. | [![Stars](https://img.shields.io/github/stars/lyft/cartography?style=social&color=white)](https://github.com/lyft/cartography/stargazers) | ~5,500 |

| **[CloudQuery](https://github.com/cloudquery/cloudquery)** — **Open-source data movement framework** syncing cloud configurations into SQL databases (PostgreSQL, etc.) for complex relational analysis . First-class support for AWS, GCP, and Azure. Enables entitlement analysis through SQL queries on synchronized configuration data. Apache-2.0. | [![Stars](https://img.shields.io/github/stars/cloudquery/cloudquery?style=social&color=white)](https://github.com/cloudquery/cloudquery/stargazers) | ~6,000 |

| **[Cloudsplaining (Salesforce)](https://github.com/salesforce/cloudsplaining)** — **AWS IAM policy analysis tool** identifying least-privilege violations by parsing IAM policies to flag resource exposure and privilege escalation potential . Delivers findings via **risk-prioritized HTML report**. **35% coverage** across AWS IAM privilege escalation paths . | [![Stars](https://img.shields.io/github/stars/salesforce/cloudsplaining?style=social&color=white)](https://github.com/salesforce/cloudsplaining/stargazers) | ~2,300 |

| **[PMapper (Principal Mapper)](https://github.com/nccgroup/PMapper)** — **Privilege escalation pathfinding tool** using a **graph model** to analyze trust policies and resource-based policies . Answers "who can reach what" by simulating authorization decisions to find actual escalation routes. **33% coverage** across AWS IAM privilege escalation paths . | [![Stars](https://img.shields.io/github/stars/nccgroup/PMapper?style=social&color=white)](https://github.com/nccgroup/PMapper/stargazers) | ~1,800 |

| **[policy_sentry (Salesforce)](https://github.com/salesforce/policy_sentry)** — **Preventative policy generation tool.** Allows engineers to declare required access levels via **YAML templates** to automatically generate least-privilege IAM policies, reducing reliance on dangerous wildcards . Implement in CI/CD pipelines to move from manual editing to automated, least-privilege policy creation . | [![Stars](https://img.shields.io/github/stars/salesforce/policy_sentry?style=social&color=white)](https://github.com/salesforce/policy_sentry/stargazers) | ~1,500 |



**Additional open-source options worth exploring:**



| Repo | Description |

|---|---|

| **[Mantissa Stance](https://explore.market.dev/ecosystems/aws/projects/mantissa-stance)** — Agentless cloud security platform with CIEM engine. **37 collectors** across AWS, GCP, Azure. **300+ YAML policies**, effective permissions, overprivilege detection, attack paths, blast radius, toxic combos, cross-account privilege escalation . Deterministic core with optional AI for natural language querying . | [![Mantissa](https://img.shields.io/badge/Mantissa-Stance-blue)](https://explore.market.dev/ecosystems/aws/projects/mantissa-stance) |



## 🤝 How to Contribute



1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## ⚠️ Disclaimer



- This is a **community-curated** list — not exhaustive and not an endorsement.

- CIEM platforms handle sensitive cloud identity and permission data; ensure proper access controls and compliance with organizational security policies.

- **Open-source reality**: The open-source ecosystem for CIEM is **mature at the discovery and analysis layers** but **lacks unified platform capabilities**. **Prowler** provides the broadest multi-cloud assessment with **65% coverage** across AWS IAM privilege escalation paths . **PMapper** and **Cloudsplaining** offer complementary AWS IAM analysis (33% and 35% coverage respectively) . **policy_sentry** enables preventative least-privilege policy generation . **Cartography** and **CloudQuery** provide the underlying graph and SQL analysis infrastructure . However, **commercial platforms** (Wiz, Microsoft Entra Permissions Management, CyberArk, Tenable, Orca, Sonrai, Britive) provide **automated remediation, just-in-time access, approval workflows, and unified multi-cloud governance** that open-source alternatives require significant integration and engineering investment to match. The open-source path is **genuinely viable** for organizations with strong cloud security engineering capacity or for specific discovery/analysis use cases.

- **Pricing caveat**: All pricing figures above are **verified against cited search results** but may change without notice. Enterprise contracts typically involve volume discounts, multi-year commitments, and bundled pricing. Always request a formal quote for accurate budgeting.



---



**Made for cloud security architects, IAM engineers, SOC analysts, and identity governance teams.**

Let's make cloud entitlement management more open, transparent, and least-privileged.
