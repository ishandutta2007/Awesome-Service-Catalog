# Awesome-Service-Catalog

# Top Service Catalog Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Requestable Service Menus, Self-Service Portals & Fulfillment Automation*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Service Catalog**. These tools provide a structured, searchable menu of services—from laptop requests and software access to HR onboarding and facilities support—enabling employees to self-serve while standardizing fulfillment workflows, approvals, and SLAs.

**Examples** include ServiceNow Service Catalog, Jira Service Management, Freshservice, BMC Helix Digital Workplace, Ivanti Neurons for ITSM, Cherwell Service Management, ManageEngine ServiceDesk Plus, SysAid, SolarWinds Service Desk, and HaloITSM (the category leaders).

**Open-source emphasis**: This section is expanded with active projects for self-hosted ITSM with service catalog capabilities—ideal for organizations building sovereign request management infrastructure without per-agent licensing lock-in.

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[ServiceNow Service Catalog](https://www.servicenow.com/)**  
  Enterprise service catalog with Catalog Builder for low-code item creation, template-based workflows enabling business users to define catalog items, multi-domain support (IT, HR, Finance), taxonomy-driven categorization, and the `CatalogItem` API for programmatic item definitions with flow/workflow/executionPlan fulfillment wiring .

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  Service catalog implemented through customizable **request types** that appear in the customer help center; IT Service Management template ships with common requests (password reset, new account, VPN setup), each request type maps to an underlying issue type and workflow for automated routing and fulfillment .

- **[Freshservice](https://www.freshworks.com/freshservice/)**  
  Service catalog with multi-level categories (up to three levels), root categories and subcategories, service items with custom fields, cost and delivery time fields, lookup fields for hierarchical relationships, additional items for bundled requests, and child request creation for multi-department fulfillment .

- **[BMC Helix Digital Workplace](https://www.bmc.com/)**  
  Enterprise app store with out-of-the-box **content packs** for IT (order new PC, request application access), HR (education reimbursement, employment verification), and Workplace services (facilities requests); Catalog administrators create services, bundles, banners, and workflows with Service Catalog Curator (AI-assisted) in Advanced edition .

- **[Ivanti Neurons for ITSM](https://www.ivanti.com/)**  
  Service Catalog page with **Preset Filters** for audience-specific views, Generic Request fallback when users can't find a service, save-for-later drafts, favorites, and share-as-link/email options; Page Designer supports desktop, mobile, and tablet views .

- **[Cherwell Service Management](https://www.cherwell.com/)**  
  Service Catalog Templates and Work Units model: templates group related Work Units (generic fulfillment tasks) that convert to individual tasks when a Service Request is invoked; Light mApp available for simpler deployments without dashboards and complex relationships .

- **[ManageEngine ServiceDesk Plus](https://www.manageengine.com/products/service-desk/)**  
  Service Catalog with IT and Business top-level categories, drag-and-drop service templates, SLA and multi-stage approval association, role-based visibility so users see only relevant services, and pre-built request templates for rapid catalog population .

- **[SysAid](https://www.sysaid.com/)**  
  Tree-structured Service Catalog with Folders, Links, **Category Pointers** (auto-generates visual navigation from existing categories including FAQs, templates, and ticket forms), and Category Pointer References for shortcuts; best practices recommend populating Knowledge Base and Templates before building the catalog .

- **[SolarWinds Service Desk](https://www.solarwinds.com/service-desk)**  
  Service Catalog items with Details tab (site, department, price, duration), Process tab for workflow definition (tasks, groups, approvals, condition sets), and GenAI-powered workflow generation from PDF/Word files or free text prompts .

- **[HaloITSM](https://www.haloitsm.com/)**  
  Service Catalog built from ticket types/templates, service categories with user access restrictions, **Optional Services** (child tickets for related requests), dynamic visibility conditions for optional services, and per-service access overrides .

## Open-Source GitHub Projects

- **[iTop](https://github.com/Combodo/iTop)**  
  Complete open-source ITIL-aligned ITSM platform with a **service catalog** module for defining requestable services, service families, and subcategories; integrates with CMDB for impact-aware fulfillment and SLA tracking; AGPL-3.0 licensed with REST API for automation.

- **[heidsoft ITSM](https://github.com/heidsoft/itsm)**  
  AI-native open-source enterprise ITSM platform (Apache-2.0) covering tickets, incidents, problems, changes, **service catalog**, knowledge, SLA, CMDB, and BPMN orchestration; AI embedded into triage, summarization, RAG, and workflow recommendations; Docker-deployable with SSO and RBAC .

- **[Znuny](https://github.com/znuny/Znuny)**  
  Open-source ITSM and helpdesk platform (OTRS fork) with service catalog and service-level tracking; customer portal exposes requestable services, with SLA and escalation handling for fulfillment; GPL-3.0 licensed and actively maintained.

- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**  
  100% open-source ticket management with **service catalog** capabilities through customizable ticket types and forms; knowledge base integration for deflection, SLA rules, and auto-assignment; built on Frappe Framework (Python/Vue) and Docker-deployable.

### Additional Strong Open-Source Options

- **osTicket** — Widely used open-source support ticket system with help topics and custom forms that function as a lightweight service catalog for smaller teams.
- **Helpy** — Open-source customer support platform with knowledge base and community forums that can serve as self-service request entry points.
- **Faveo Helpdesk** — Open-source helpdesk with service catalog and SLA management for multi-channel request handling.

**Frameworks for building custom systems**: Combine **iTop** for ITIL-aligned service catalog with CMDB integration, **heidsoft ITSM** for AI-assisted request triage and BPMN fulfillment workflows, **Znuny** for ticket-based service fulfillment with SLA tracking, and **Frappe Helpdesk** for a modern, Docker-deployable catalog foundation in a self-hosted service catalog stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Service catalog platforms handling employee and service data must comply with applicable privacy regulations and organizational access policies.
- Self-hosted open-source solutions require proper security hardening, CMDB data quality, and workflow customization for approval and fulfillment automation.
- Verify license terms for commercial use; iTop uses AGPL-3.0, heidsoft ITSM uses Apache-2.0, Znuny uses GPL-3.0, and Frappe Helpdesk is open-source.

---

**Made for IT service managers, self-service portal administrators, and employee experience teams.**  
Let's make service catalogs more open, navigable, and fulfillment-ready.
