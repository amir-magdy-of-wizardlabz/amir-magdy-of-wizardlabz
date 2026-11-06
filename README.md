# Amir Magdy

**Fractional CTO · .NET architect · e-commerce, ERP integration, cloud infrastructure, AI agents**

[![Website](https://img.shields.io/badge/wizardlabz.com-1F5FBF?style=flat&logo=googlechrome&logoColor=white)](https://wizardlabz.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/amirmagdy/)
[![Upwork](https://img.shields.io/badge/Upwork-6FDA44?style=flat&logo=upwork&logoColor=white)](https://www.upwork.com/freelancers/amirm)

20+ years in C#/.NET, from Classic ASP in 1999 to .NET 10 today. I run [Wizard Labz](https://wizardlabz.com), a UAE-based consultancy, and currently own the complete technology stack of a North American multi-brand e-commerce group as their fractional CTO: storefronts, ERP, CI/CD, infrastructure, monitoring, analytics and security.

The systems behind your business, built to keep running.

## What I do

- **Connect your systems** — online stores, ERP (ERPNext), warehouses and marketplaces linked through a message bus (RabbitMQ) so prices, stock and orders update automatically
- **Fix and scale what you have** — performance audits, root-cause fixes applied in place, systems prepared for peak traffic without a rewrite
- **Build on solid foundations** — new products with the architecture designed first, built in visible phases, handed over as code another team can maintain
- **Automate and instrument** — n8n business-process automation, Airflow/PostgreSQL analytics pipelines, LLM agents (Claude, MCP tool servers) for internal tooling

## Selected work

| Project | What happened |
|---|---|
| [E-commerce search on Elasticsearch](https://wizardlabz.com/case-studies/elasticsearch-ecommerce-search) | Search moved off the transactional database into a dedicated index with queue-driven updates and a database fallback. 97% faster responses, 60% less database load, a Black Friday at 10× traffic with zero incidents. |
| [Real-time ERPNext ↔ store integration](https://wizardlabz.com/case-studies/erpnext-message-bus) | RabbitMQ topic exchange between ERPNext and every online store; price, stock and catalogue events reach stores in seconds, orders flow back, every payload logged and replayable. |
| Multi-site storefront engine, .NET Framework 4 → .NET 10 | One codebase serving several brand storefronts migrated as an upgrade, not a rewrite, with site-by-site cutover and rollback at every step. |
| Checkout fraud defense and CMS malware remediation | Cloudflare WAF rules against an active card-testing attack, origin locked to the edge, injected templates cleaned, credentials rotated, back office IP-restricted. |
| Analytics pipeline and demand forecasting | Docker-hosted Airflow into a PostgreSQL warehouse; a replenishment forecasting model that replaced a hand-tuned reorder formula. |
| [Waitwize](https://waitwize.com) | Virtual-queue SaaS I designed and built end to end: ASP.NET Core, SignalR, PostgreSQL, Flutter, AWS. |

## Open source

- [**Kiahk**](https://github.com/amir-magdy-of-wizardlabz/kiahk) — exact Coptic Orthodox calendar arithmetic: Gregorian ↔ Coptic conversion, Coptic Easter via the Julian computus, fixed and moveable feasts. One canonical spec and shared test vectors, ported to 9 languages and published on npm, PyPI, NuGet, Maven Central, pub.dev, Packagist, Go, CocoaPods and SwiftPM, each with its own CI.
- [**EventDrivenApp**](https://github.com/amir-magdy-of-wizardlabz/EventDrivenApp) — a .NET 8 microservices template: three independently deployable services, isolated PostgreSQL databases, RabbitMQ messaging, one `docker compose up`. Used as a training tool for teams moving from a monolith to multi-team delivery.

## Stack

`C#` `ASP.NET Core` `.NET Framework` `SQL Server` `PostgreSQL` `Elasticsearch` `RabbitMQ` `ERPNext` `Umbraco` `Docker` `Airflow` `Cloudflare` `AWS` `Azure` `TeamCity` `Authentik` `Zabbix` `n8n` `React` `Flutter`

## Contact

- Email: [amir@wizardlabz.com](mailto:amir@wizardlabz.com)
- Site: [wizardlabz.com](https://wizardlabz.com)
- LinkedIn: [linkedin.com/in/amirmagdy](https://www.linkedin.com/in/amirmagdy/)
- Upwork: [upwork.com/freelancers/amirm](https://www.upwork.com/freelancers/amirm)

Native Arabic, fluent English. Hours overlap with Europe, the Gulf and US-East mornings.
