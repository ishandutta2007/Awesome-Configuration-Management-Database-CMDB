# Awesome-Configuration-Management-Database-CMDB

# Top Configuration Management Database (CMDB) Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on IT Configuration Items, Relationship Mapping & Service Impact Analysis*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Configuration Management Database (CMDB)**. These tools enable IT teams to maintain a centralized, accurate repository of Configuration Items (CIs)—servers, applications, network devices, cloud resources—and their relationships, providing the foundation for incident diagnosis, change impact analysis, asset management, and compliance.

**Examples** include ServiceNow Configuration Management Database, BMC Helix CMDB, Device42, Freshservice CMDB, Insight Discovery, Virima, SolarWinds Service Desk, Lansweeper, ManageEngine ServiceDesk Plus, and Alloy Navigator (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted CMDB and relationship graphing—ideal for organizations building sovereign configuration management infrastructure without per-node or per-seat licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Configuration Management Database](https://www.servicenow.com/)**  
  Centralized cloud-based CMDB storing CIs with relationship data; features CMDB Health benchmarking, Identification and Reconciliation Engine (IRE) to deduplicate multi-source data, CMDB Data Manager for policy-driven lifecycle operations, Service Graph Connectors for external system integration, and a unified workspace for data accuracy and insights . Discovery uses MID Server architecture with probes, classifiers, and sensors over SSH, SNMP, and WMI to automatically populate and continuously update the CMDB .

- **[BMC Helix CMDB](https://www.bmc.com/)**  
  Central source of truth for CIs with impact simulation for change assessment, data federation to external repositories, normalization and reconciliation for single-source accuracy, dataset partitioning for real-world infrastructure alignment, and CMDB Governor with HelixGPT insights for data quality monitoring .

- **[Device42](https://www.device42.com/)**  
  Hybrid-cloud CMDB with agentless automated discovery and Application Dependency Mapping (ADM); provides a pre-configured CMDB eliminating lengthy CI design, EnrichAI for automatic data normalization with EOL/EOS and vulnerability context, and DCIM/IPAM capabilities alongside configuration management .

- **[Freshservice CMDB](https://www.freshworks.com/freshservice/)**  
  Continuously updated CMDB with automatic discovery and service mapping showing real-time relationships between assets, applications, and business services ; includes a visual canvas for CI relationship tracking, audit-ready activity logs, and a Discovery Probe for agentless network device discovery .

- **[Insight Discovery](https://www.atlassian.com/)**  
  Agent-free network sweeper tightly integrated with Jira; provides a real CMDB within Jira, dependency mapping and impact analysis, and automation frameworks focused on Jira assets; discovers servers, computers, and devices on enterprise networks and captures configuration, provisioning, and current status into the Insight/Jira CMDB .

- **[Virima](https://virima.com/)**  
  ITAM/ITSM platform with intelligent asset discovery and CMDB automation; v6.1 expands discovery to Cisco, Juniper, standalone ESXi, Oracle databases, Nutanix, NetApp, and additional AWS/Azure services; adds MFA, mTLS, SNMP v3 security enhancements, unauthorized CI dashboard widgets, and ServiceNow reverse sync capability .

- **[SolarWinds Service Desk](https://www.solarwinds.com/)**  
  Service Desk with CMDB Visual Map showing CI relationships and dependencies; helps pinpoint issues, understand risks and impact of planned/unplanned changes, and maintain detailed insight into server setup and dependencies .

- **[Lansweeper](https://www.lansweeper.com/)**  
  IT asset discovery platform that feeds accurate, up-to-date data into CMDBs; provides deep hardware and software inventory including lifecycle and warranty information; integrates with ITSM solutions like 4me to keep CMDB current with device changes and removals .

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/)**  
  Unified CMDB with automated discovery (Windows domain scan, script, agent-based), custom CI and relationship types, visual relationship builder on drag-and-drop canvas, CI baseline for change tracking, business views for service context, and a CMDB Data Doctor AI agent for data quality analysis and service impact flagging .

- **[Alloy Navigator](https://www.alloysoftware.com/)**  
  IT Service & Asset Management solution with ITIL-driven Change & Configuration Management, workflow process automation, and intelligent relationship creation between data entities; covers Help Desk, Inventory, and Knowledge Base for small to enterprise businesses .

## Open-Source GitHub Projects

- **[Atlas CMDB](https://github.com/mojoaar/atlascmdb)**  
  Open-source CMDB built on Next.js for modern IT teams; manages services (business & technical), applications, CIs, assets, teams, locations, and users in one place; features interactive relationship graphs with BFS depth control (1–6 hops) and Dagre auto-layout, visual rack management (42U/48U with front/back columns), geographic maps via Leaflet, CSV import/export with field mapping and conflict resolution, SSO via OpenID Connect (PKCE S256), SCIM 2.0 provisioning, TOTP MFA, and full audit trail with before/after diffs; supports SQLite (dev) and PostgreSQL (prod); MIT-licensed and Docker-deployable .

### Additional Strong Open-Source Options

- **iTop** — Open-source ITIL-aligned ITSM platform with a configurable CMDB covering servers, VMs, storage, network devices, applications, contacts, and contracts; impact analysis rendered graphically through GraphViz; REST API for integration.
- **GLPI** — Free asset and IT management software with CMDB capabilities, inventory agent for automated discovery, and plugin ecosystem for extending configuration management workflows.

**Frameworks for building custom systems**: Deploy **Atlas CMDB** for a modern, self-hosted CMDB with relationship graphing, rack management, and SSO/SCIM integration; extend with **iTop** for ITIL-aligned service management and impact analysis; integrate **GLPI** inventory agent for automated CI discovery in a sovereign CMDB stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- CMDB platforms handling infrastructure and relationship data must comply with applicable security policies; CI data can reveal sensitive system architecture and dependencies.
- Self-hosted open-source solutions vary in scope—Atlas CMDB provides a modern CMDB with relationship graphing and enterprise auth, while full enterprise CMDB capabilities (multi-source reconciliation, service mapping, health benchmarking) typically require commercial platforms like ServiceNow or BMC Helix.
- Verify license terms for commercial use; Atlas CMDB is MIT-licensed .

---

**Made for IT operations teams, CMDB administrators, service mapping engineers, and configuration managers.**  
Let's make configuration management databases more open, accurate, and relationship-aware.
