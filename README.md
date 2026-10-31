# Awesome-Support-Ticket-Tracking-Routing

# Top Support Ticket Tracking & Routing Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Shared Inboxes, SLA-Driven Routing & Self-Hosted Help Desks*  
**Last updated: October 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Support Ticket Tracking & Routing**. These tools enable support teams to capture requests from email, chat, and web forms, route them to the right agents based on skills or workload, enforce SLAs, and maintain a complete history of every customer interaction.

**Examples** include HubSpot Ticket Management, Zendesk, Freshdesk, Jira Service Management, Zoho Desk, HappyFox, Help Scout, Gorgias, TeamSupport, and Mojo Helpdesk (the category leaders).

**Open-source emphasis**: Support Ticket Tracking & Routing is a domain where open-source tooling is **mature and production-proven across distinct philosophies**. **FreeScout** is the strongest shared-inbox alternative to Zendesk and Help Scout—a lightweight PHP/MySQL application with omnichannel support (email, WhatsApp, Telegram, Facebook, Slack, Live Chat), unlimited agents, and a web installer that runs even on shared hosting . **Zammad** provides the most capable mid-sized help desk with omnichannel ticket handling, SLAs, automation, and a modern interface . **Znuny** (the OTRS fork) offers enterprise-grade queue and process configuration for organizations needing structured service operations . **osTicket** remains the accessible entry point for small teams wanting traditional ticket queues and forms . The critical caveat: **self-hosting means owning upgrades, email deliverability, backups, and security patches**—the license is free, but operational responsibility is not .

Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

- **[HubSpot Ticket Management](https://www.hubspot.com/)**  
  Native ticketing within HubSpot Service Hub; connects tickets to contact and deal records for a unified customer view, with automation, SLAs, and a knowledge base.

- **[Zendesk](https://www.zendesk.com/)**  
  The benchmark for cloud help desks; omnichannel ticketing, triggers and automations for routing, SLA policies, and a vast app marketplace.

- **[Freshdesk](https://www.freshworks.com/freshdesk/)**  
  Cloud help desk with ticket routing, automation, SLA management, and a customer portal; positioned for small to mid-sized support teams.

- **[Jira Service Management](https://www.atlassian.com/software/jira/service-management)**  
  ITSM-focused ticketing with request types, queues, SLAs, and deep Jira integration for development-linked support workflows.

- **[Zoho Desk](https://www.zoho.com/desk/)**  
  Cloud help desk within the Zoho ecosystem; ticketing, automation, SLAs, and a knowledge base with competitive pricing.

- **[HappyFox](https://www.happyfox.com/)**  
  Help desk software with ticket routing, SLAs, automation, and a self-service portal; positioned for mid-market support teams.

- **[Help Scout](https://www.helpscout.com/)**  
  Shared inbox platform with a human-centered approach; email-based ticketing, saved replies, and a knowledge base without the complexity of full ITSM suites.

- **[Gorgias](https://www.gorgias.com/)**  
  Help desk built for ecommerce (Shopify Premier Partner); unifies chat, email, and social into one inbox with deep Shopify integration for order context.

- **[TeamSupport](https://www.teamsupport.com/)**  
  B2B-focused help desk with ticket management, SLAs, and customer/contact management for complex business relationships.

- **[Mojo Helpdesk](https://www.mojohelpdesk.com/)**  
  Simple cloud help desk with ticketing, automation, and a knowledge base; positioned for teams wanting straightforward support without enterprise complexity.

## Open-Source GitHub Projects

### Shared Inbox & Lightweight Help Desks

- **[FreeScout](https://github.com/freescout-help-desk/freescout)**  
  The strongest open-source **shared inbox** and Zendesk/Help Scout alternative (PHP/Laravel) . Features: **omnichannel** centralization (email, WhatsApp, Telegram, Facebook, Slack, Live Chat), **unlimited agents and mailboxes**, AI-powered assistance, mobile-friendly PWA with Web Push, 33 languages, screen reader support, and a web installer/updater that runs on shared hosting . **Best for teams wanting a lightweight, email-centric help desk** without the resource footprint of Zammad—but note that some advanced features (workflows, reporting) may require paid modules .

- **[osTicket](https://github.com/osTicket/osTicket)**  
  The most widely adopted open-source **traditional help desk** (GPL-2.0) . Features email piping, web-based ticket creation, configurable help topics, departments and queues, SLA support, canned responses, customer portal, and knowledge base . **Best for small to mid-sized support teams** wanting straightforward ticket queues and forms with a familiar model—but the interface feels dated and reporting/automation may require plugins .

- **[Libredesk](https://github.com/abhinavxd/libredesk)**  
  Modern open-source customer support desk distributed as a **single Go binary** (AGPL-3.0) . Features multi-inbox management, smart automation, AI-assisted responses, granular permissions, macros, SLAs, and BI tools integration . **Best for teams wanting a modern, lightweight alternative** with minimal infrastructure overhead.

### Mid-Sized & Enterprise Help Desks

- **[Zammad](https://github.com/zammad/zammad)**  
  The most capable open-source **mid-sized help desk** (AGPL-3.0) . Features: **omnichannel ticket handling** (email, web forms, chat, phone, social), customer and organization records, tags, groups, roles, templates, macros, triggers, scheduled actions, SLAs, escalation rules, knowledge base, REST APIs, webhooks, and LDAP . **Best for growing support organizations** wanting a modern interface and broad channel coverage—but self-hosting requires more resources and maintenance than FreeScout or osTicket .

- **[Znuny](https://github.com/znuny/Znuny)**  
  Open-source **enterprise-grade service desk** (AGPL-3.0) forked from OTRS . Features: email-to-ticket conversion, queues, ticket states, priorities, ownership, **service-level agreements**, escalation rules, templates, reporting, role-based permissions, process management, and knowledge/FAQ capabilities . **Best for organizations needing structured service operations** with multiple queues, approval paths, and audit-friendly histories—but the interface and administration model feel dated, and configuration requires specialist knowledge .

- **[OTOBO](https://github.com/RotherOSS/otobo)**  
  Open-source **ITSM-focused ticketing** system forked from OTRS (GPL-3.0) . Continues the OTRS codebase with ITSM packages free to download; supports OpenID Connect, LDAP, and RADIUS sign-in . **Best for IT and service teams wanting an OTRS-style service desk** without license fees—but production servers need at least 8 GB RAM (16 GB recommended), and vendor support starts at €3,900/year .

### Niche & Specialized

- **[Frappe Helpdesk](https://github.com/frappe/helpdesk)**  
  Open-source customer service software built on the Frappe framework (AGPL-3.0) . Features tickets, SLAs, customer portal, and AI capabilities (RAG, agent workflows) without assembling a model stack; shares customer data with ERPNext if already in use . **Best for teams already on ERPNext/Frappe** wanting support tickets in the same system—but lacks live chat and WhatsApp channels, and self-hosting means running the full Frappe stack (MariaDB, Redis, bench) .

- **[Request Tracker (RT)](https://github.com/bestpractical/request-tracker)**  
  Enterprise-grade issue tracking maintained by Best Practical (GPL-2.0) . Built around email and queues with **rights per queue, group, and role**; asset tracking built in; REST 2 API in core; RT 6 allows admins to rearrange ticket page layouts . **Best for IT and operations teams** wanting detailed rights and full change history—but no official Docker image, SSO requires a web server module, and cloud RT needs at least 5 users on an annual plan .

### Additional Strong Open-Source Options

- **UVdesk** — Open-source help desk on PHP/Symfony with unlimited agents, teams, mailboxes, and a customer portal . **Caution**: no new release since September 2025, no SSO for agents, and no published Docker image .
- **Helpdock** — Open-source customer support platform with ticketing, help center, live chat widget, and grounded AI; features SSO (SAML/OIDC), migration importers for Zendesk/Freshdesk/Zoho, and OWASP ASVS Level 2 security . **Newer**—verify production maturity before adoption.
- **ResolveHQ** — Self-hosted helpdesk on Cloudflare Workers (D1, R2, Queues, Email Routing) with shared inbox and AI assist . **Cloudflare-native**—best for teams already on Cloudflare wanting minimal infrastructure management.

**Frameworks for building custom systems**: The choice hinges on team size and complexity. For **lightweight shared inbox**, FreeScout provides the most accessible path with shared hosting support . For **traditional ticket queues**, osTicket . For **mid-sized omnichannel support**, Zammad . For **enterprise service operations with SLAs and complex queues**, Znuny . For **ERPNext users**, Frappe Helpdesk . No open-source help desk matches Zendesk's **app marketplace ecosystem** or Freshdesk's **managed simplicity**—self-hosting means owning the operational responsibility.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Support ticket platforms handling customer data must comply with applicable privacy regulations (GDPR, CCPA) and data retention policies; **self-hosted solutions place full responsibility for email deliverability, security patches, and backups on the operator** .
- **Open-source help desks are mature for core ticketing but vary in scope**—FreeScout and osTicket serve lightweight needs, Zammad provides mid-sized omnichannel capability, and Znuny/OTOBO serve enterprise service operations. However, **no open-source project matches Zendesk's app ecosystem** or the managed simplicity of Freshdesk. Choose based on team size, workflow complexity, and tolerance for operational responsibility.
- Verify license terms for commercial use; FreeScout uses AGPL-3.0 , osTicket uses GPL-2.0 , Zammad uses AGPL-3.0 , and Znuny uses AGPL-3.0 .

---

**Made for support managers, IT administrators, and teams choosing their help desk platform.**  
Let's make support ticket tracking and routing more open, but with clear eyes about the operational burden and ecosystem gaps that self-hosting introduces.
