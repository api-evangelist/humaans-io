# Humaans (humaans-io)

Humaans is a London-headquartered modern HRIS (Human Resources Information System) for fast-growing, distributed teams. The platform combines a best-in-class system of record — employee directory, documents, time off, timesheets, compensation, equipment, locations, custom fields and tables, performance reviews, and onboarding/offboarding workflows — with the Athena agentic AI platform and an AI Companion that automate administrative HR work.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/humaans-io/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

- HR, HRIS, Human Resources, People Operations, People Analytics, Onboarding, Offboarding, Performance Management, Time Off, Compensation, Workflow Automation, AI Companion, Agentic AI, UK, London

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Humaans API

REST API for the Humaans HRIS exposing People, Companies, Compensations, Bank Accounts, Documents, Time Away (entries, allocations, policies, types), Equipment, Job Roles, Locations, Custom Fields and Values, Performance (reviews, cycles, templates, ratings), Timesheet entries and submissions, Webhooks, Audit Events, and Working Patterns. Bearer token authentication with OAuth-style scopes; JSON in / JSON out; standard HTTP verbs; `$limit`/`$skip` pagination; rich filter operators; HMAC SHA-256 signed webhooks.

**Human URL:** [https://docs.humaans.io/api/](https://docs.humaans.io/api/)

**Base URL:** `https://app.humaans.io/api`

- [Documentation](https://docs.humaans.io/api/)
- [API Introduction](https://docs.humaans.io/api/introduction)
- [OpenAPI](openapi/humaans-api-openapi.yml)

## Tags

- HR
- HRIS
- Human Resources
- People Operations
- People Analytics
- Onboarding
- Offboarding
- Performance Management
- Time Off
- Compensation
- Workflow Automation
- AI Companion
- Agentic AI
- UK
- London

## Common Properties

- [Portal](https://humaans.io)
- [WebSite — Humaans Website](https://humaans.io)
- [Documentation — Humaans Help Center](https://docs.humaans.io)
- [Documentation — Humaans API Reference](https://docs.humaans.io/api/)
- [GettingStarted — API Introduction](https://docs.humaans.io/api/introduction)
- [SignIn — Humaans App](https://app.humaans.io)
- [SignUp — Get Started](https://humaans.io/get-started)
- [Pricing](https://humaans.io/pricing)
- [Integrations Directory](https://humaans.io/integrations)
- [Security](https://humaans.io/security)
- [PrivacyPolicy](https://humaans.io/legal/privacy-policy)
- [TermsOfService](https://humaans.io/legal/terms-of-service)
- [Documentation — Data Processing Agreement](https://humaans.io/legal/dpa)
- [Documentation — Sub-processors](https://humaans.io/legal/sub-processors)
- [Blog](https://humaans.io/blog)
- [CaseStudies — Customer Stories](https://humaans.io/customers)
- [About](https://humaans.io/about)
- [Careers](https://humaans.io/careers)
- [Contact](https://humaans.io/contact)
- [Support](mailto:hi@humaans.io)
- [LinkedIn](https://www.linkedin.com/company/humaans)
- [Twitter](https://twitter.com/humaans_io)
- [GitHubOrganization](https://github.com/humaans)
- [SDK — figbird](https://github.com/humaans/figbird)
- [SDK — next-img](https://github.com/humaans/next-img)
- [SDK — react-machine](https://github.com/humaans/react-machine)
- [SDK — react-space-router](https://github.com/humaans/react-space-router)
- [Tool — workalendar](https://github.com/humaans/workalendar)
- [Application — iOS](https://apps.apple.com/app/humaans/id1610537316)
- [Application — Android](https://play.google.com/store/apps/details?id=io.humaans)
- [Reviews — G2](https://www.g2.com/products/humaans/reviews)

## Features

- REST HRIS API with consistent resource-oriented URLs, JSON in / JSON out, and standard HTTP verbs and status codes
- Bearer token authentication with OAuth-style scopes (`public:read`, `private:read`, `private:write`, `compensations:read/write`, `documents:read/write`, `webhooks:manage`)
- Role-based access control (Owner, Admin, Finance, Tech, Manager, User) reflected in API access
- Pagination via `$limit` (default 100, max 250) and `$skip`
- Rich filtering operators (`$in`, `$nin`, `$gt`, `$gte`, `$lt`, `$lte`, `$or`) on most collections
- 70+ documented resource categories — People, Companies, Compensations, Bank Accounts, Documents, Document Folders, Document Types, Identity Documents
- Time Away — entries, allocations, types, policies, and accruals
- Equipment, Job Roles, Locations, Custom Fields, Custom Values, Working Patterns
- Performance — reviews, cycles, templates, ratings (mostly read)
- Timesheet entries and submissions with full CRUD
- HMAC SHA-256 signed webhooks with exponential backoff retry and auto-disable after 5 days of failures
- Read-only Audit Events stream for compliance and SIEM integration
- Pre-built integrations across Payroll, Identity, Compliance, Finance, ATS, Performance, Calendar/Comms, eSignature, Benefits, Learning, Automation, and People Analytics
- Native Apideck HRIS unified-API connector for Humaans
- Athena agentic AI platform plus AI Companion add-on for natural-language HR queries
- Workflow automation, onboarding/offboarding sequences, and dynamic databases (custom data tables)
- 300+ global locations supported with country-specific localisation
- iOS and Android mobile apps
- SOC 2, ISO 27001, and GDPR-aligned controls; Vanta / Drata / Secureframe automation integrations
- 99.9% uptime SLA on the Enterprise plan

## Maintainers

| FN | Email |
|---|---|
| Kin Lane | info@apievangelist.com |
