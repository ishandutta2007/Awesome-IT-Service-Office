# Awesome-IT-Service-Office

# Top IT Service Office Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on IT Service Management, Help Desk Operations & Self-Service Portals*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **IT Service Office**. These tools enable IT teams to manage incidents, fulfill service requests, track assets, and provide employees with a unified self-service experience—reducing downtime and improving service delivery across the organization.

**Examples** include ServiceNow IT Service Office, ManageEngine ServiceDesk Plus, BMC Helix, Jira Service Management, Freshservice, Cherwell, SysAid, TOPdesk, SolarWinds Service Desk, Ivanti Neurons, and HaloITSM (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted IT service management platforms—ideal for organizations seeking ITIL-aligned alternatives without per-agent licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow IT Service Office](https://www.servicenow.com/)**  
  Enterprise ITSM platform on the Now Platform; April 2026 licensing restructured into Foundation (Incident, Request, Asset, Virtual Agent), Advanced (adds Problem, Change, Major Incident, Process Mining), and Prime (adds custom AI agent building and DevOps Change Velocity) tiers, with AI bundled into every tier .

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  
  ITIL-aligned service desk with Zia AI Agents, Model Context Protocol support, and CMDB Baselines; the new cloud UI (beta) introduces Ask Zia always-on contextual assistant, Custom Pages for vibe-coded interfaces, Peek Views for faster ticket navigation, and personalized technician workspaces .

- **[BMC Helix ITSM](https://www.bmc.com/)**  
  ITIL-compliant service desk with 26.2 release adding Problem Solver for recurring incident detection, Ticket Resolver for autonomous incident management, Post Incident Reviews (PIR), and HelixGPT-powered CMDB data quality insights .

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  Atlassian's ITSM solution now part of Service Collections; provides AI agents for instant employee inquiry resolution, knowledge gap detection, incident grouping and escalation, and post-incident review automation, with 1,000+ marketplace integrations .

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  Enterprise-grade ITSM with built-in Freddy AI for ticket deflection (65.7%) and faster resolution (76.6%); includes service catalog, SLA management, problem/change/release management, project portfolio management, and 1,400+ integrations across IT, HR, and business teams .

- **[Cherwell Service Management](https://www.cherwell.com/)**  
  Highly customizable ITSM platform with One-Step automation workflows; users report strong workflow management for IT change controls but note customization requires significant effort and upgrades can break functionality, with browser client bugginess cited as a concern .

- **[SysAid](https://www.sysaid.com/)**  
  AI-driven ITSM help desk with agentic AI woven into ITIL processes; claims 89% first-time fix rate, 60% touchless resolution, and 65% queue elimination through AI Copilot and 100+ prebuilt/custom AI Agents; March 2026 adds Splashtop remote support integration and License Manager Advanced user-level utilization insights .

- **[TOPdesk](https://www.topdesk.com/)**  
  Service management toolkit with AI-suggested ticket categories and priorities, knowledge suggestions while typing, self-service portal with request tracking, and unlimited asset storage without extra cost; strong for organizations wanting an intuitive, customizable service experience .

- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  
  IT service management with incident and request management, SLA tracking, and integration with SolarWinds monitoring tools for infrastructure-aware service delivery.

- **[Ivanti Neurons](https://www.ivanti.com/)**  
  AI-powered ITSM and endpoint management platform with self-healing automation, service catalog, and cross-department workflow orchestration.

- **[HaloITSM](https://www.haloitsm.com/)**  
  ITIL-aligned service management with request types, approval workflows, SLAs, and multi-department support for service desks and MSPs.

## Open-Source GitHub Projects

- **[iTop](https://github.com/Combodo/iTop)**  
  Complete open-source, web-based IT service management platform (ITIL-compliant); features fully configurable CMDB, helpdesk and incident management, service and contract management, change management, configurable SLA management, graphical impact analysis, CSV import tools, and data synchronization; AGPL-3.0 licensed with add-ons and web services for integration .

- **[GLPI](https://github.com/glpi-project/glpi)**  
  Free asset and IT management software package with ITIL service desk, data center management, licenses tracking, and software auditing; PHP-based with active development as of September 2026 .

- **[Znuny](https://github.com/znuny/Znuny)**  
  Free, open-source, versatile web-based ticketing system for customer service, help desk, and IT service management; built for transparency and long-term sustainability, highly tailorable to organizational needs; Perl-based with active updates .

- **[FreeITSM](https://github.com/edmozley/freeitsm)**  
  Open-source ITSM tool focused on data ownership and simplicity; features ticket management with optional AI summaries and briefings (using your own AI provider), command palette (⌘K/Ctrl-K), multi-person task involvement, Microsoft 365 calendar sync for scheduled tickets, and iCalendar subscription links for personal work calendars .

- **[NeatLogic](https://github.com/topics/itsm)**  
  Progressive ITOM platform with ITSM, CMDB, continuous integration, knowledge base, automation, reporting, and inspection capabilities; actively developed with Shell-based deployment .

### Additional Strong Open-Source Options

- **Felicity** — Open-source integrated platform converging service management, operations management, and asset management with internal workflow engine covering Request, Incident, Problem, and Change Management .
- **osTicket** — Widely used open-source support ticket system with help topics, email piping, and a customer portal for smaller teams.
- **Helpy** — Open-source customer support platform with knowledge base and community forums for self-service support.

**Frameworks for building custom systems**: Combine **iTop** for ITIL-aligned ITSM with CMDB and SLA management, **FreeITSM** for a modern lightweight service desk with AI-assisted workflows and calendar integration, **GLPI** for asset-centric IT management, and **Znuny** for ticket-based service delivery in a fully self-hosted IT service office stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- IT service office platforms handling employee and infrastructure data must comply with applicable privacy regulations and organizational security policies.
- Self-hosted open-source solutions vary in ITIL process depth—iTop and GLPI provide mature CMDB and service management foundations, while FreeITSM offers a modern lightweight alternative with active development.
- Verify license terms for commercial use; iTop uses AGPL-3.0, GLPI uses GPL-3.0, Znuny uses GPL-3.0, and FreeITSM is an independent open-source project.

---

**Made for IT service managers, help desk administrators, and IT operations teams.**  
Let's make IT service offices more open, efficient, and employee-centric.
