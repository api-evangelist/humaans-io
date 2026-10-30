# Humaans

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Humaans is a London-headquartered modern HRIS (Human Resources Information
System) for fast-growing, distributed teams. The platform combines a
best-in-class system of record — employee directory, documents, time off,
timesheets, compensation, equipment, locations, custom fields and tables,
performance reviews, and onboarding/offboarding workflows — with the Athena
agentic AI platform and an AI Companion that automate administrative HR
work. Humaans exposes a comprehensive REST API at app.humaans.io/api with
Bearer token authentication, OAuth-style scopes, $limit/$skip pagination,
rich filter operators, and HMAC SHA-256 signed webhooks. The API spans
70+ documented resource categories including People, Companies,
Compensations, Bank Accounts, Documents, Time Away (entries, allocations,
policies, types), Equipment, Job Roles, Locations, Custom Fields and
Values, Performance, Timesheet entries and submissions, Webhooks, Audit
Events, and Working Patterns. Humaans ships pre-built integrations across
payroll, identity, compliance, finance, ATS, performance, benefits,
learning, and automation, plus a Zapier connector and an Apideck HRIS
unified-API binding. Trusted by global teams across 300+ locations and
rated 4.8/5 on G2.

**Areas:** Human Resources · HRIS · People Operations · People Analytics · Onboarding · Offboarding · Performance Management · Time Off · Compensation · Workflow Automation · AI Companion · AI Agents

## Humaans on APIs.io

Everything profiled for Humaans is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/humaans-io/](https://apis.io/providers/humaans-io/)** — or go straight to one of the APIs or properties below.

### APIs (15)

- [Humaans Audit Events API](https://apis.io/apis/humaans-io/humaans-io-audit-events-api/) — Read-only audit trail
- [Humaans Bank Accounts API](https://apis.io/apis/humaans-io/humaans-io-bank-accounts-api/) — Employee bank account records
- [Humaans Companies API](https://apis.io/apis/humaans-io/humaans-io-companies-api/) — Tenant company record
- [Humaans Compensations API](https://apis.io/apis/humaans-io/humaans-io-compensations-api/) — Salary, bonus, and compensation history
- [Humaans Custom Fields API](https://apis.io/apis/humaans-io/humaans-io-custom-fields-api/) — Tenant-defined custom field definitions and values
- [Humaans Documents API](https://apis.io/apis/humaans-io/humaans-io-documents-api/) — Personal and company document storage
- [Humaans Equipment API](https://apis.io/apis/humaans-io/humaans-io-equipment-api/) — Equipment assigned to employees
- [Humaans Job Roles API](https://apis.io/apis/humaans-io/humaans-io-job-roles-api/) — Position and role definitions
- [Humaans Locations API](https://apis.io/apis/humaans-io/humaans-io-locations-api/) — Office and remote work locations
- [Humaans People API](https://apis.io/apis/humaans-io/humaans-io-people-api/) — Employee records, the canonical resource of the HRIS
- [Humaans Performance API](https://apis.io/apis/humaans-io/humaans-io-performance-api/) — Performance reviews, cycles, templates, and ratings
- [Humaans Time Away API](https://apis.io/apis/humaans-io/humaans-io-time-away-api/) — Time off, holidays, leave allocations, policies, and types
- [Humaans Timesheet API](https://apis.io/apis/humaans-io/humaans-io-timesheet-api/) — Timesheet entries and submissions
- [Humaans Webhooks API](https://apis.io/apis/humaans-io/humaans-io-webhooks-api/) — Outbound HMAC-signed event subscriptions
- [Humaans Working Patterns API](https://apis.io/apis/humaans-io/humaans-io-working-patterns-api/) — Work schedule patterns

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [humaans-io](https://apis.io/servers/humaans-io/humaans-io/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Humaans Io Agentic Access](https://apis.io/agentic-access/humaans-io/humaans-io-agentic-access/)

#### Collections (16)

Postman and Open Collection request collections.

- [Humaans API](https://apis.io/collections/humaans-io/open-humaans-api/)
- [Humaans Audit Events API](https://apis.io/collections/humaans-io/open-humaans-io-audit-events-api/)
- [Humaans Audit Events Bank Accounts API](https://apis.io/collections/humaans-io/open-humaans-io-bank-accounts-api/)
- [Humaans Audit Events Companies API](https://apis.io/collections/humaans-io/open-humaans-io-companies-api/)
- [Humaans Audit Events Compensations API](https://apis.io/collections/humaans-io/open-humaans-io-compensations-api/)
- [Humaans Audit Events Custom Fields API](https://apis.io/collections/humaans-io/open-humaans-io-custom-fields-api/)
- [Humaans Audit Events Documents API](https://apis.io/collections/humaans-io/open-humaans-io-documents-api/)
- [Humaans Audit Events Equipment API](https://apis.io/collections/humaans-io/open-humaans-io-equipment-api/)
- [Humaans Audit Events Job Roles API](https://apis.io/collections/humaans-io/open-humaans-io-job-roles-api/)
- [Humaans Audit Events Locations API](https://apis.io/collections/humaans-io/open-humaans-io-locations-api/)
- [Humaans Audit Events People API](https://apis.io/collections/humaans-io/open-humaans-io-people-api/)
- [Humaans Audit Events Performance API](https://apis.io/collections/humaans-io/open-humaans-io-performance-api/)
- [Humaans Audit Events Time Away API](https://apis.io/collections/humaans-io/open-humaans-io-time-away-api/)
- [Humaans Audit Events Timesheet API](https://apis.io/collections/humaans-io/open-humaans-io-timesheet-api/)
- [Humaans Audit Events Webhooks API](https://apis.io/collections/humaans-io/open-humaans-io-webhooks-api/)
- [Humaans Audit Events Working Patterns API](https://apis.io/collections/humaans-io/open-humaans-io-working-patterns-api/)

#### Security (4)

Authentication, trust centre, and vulnerability disclosure.

- [Humaans Io Authentication](https://apis.io/security/humaans-io/humaans-io-authentication/)
- [Humaans Io Domain Security](https://apis.io/security/humaans-io/humaans-io-domain-security/)
- [Humaans Io Trust Center](https://apis.io/security/humaans-io/humaans-io-trust-center/)
- [Humaans Io Vulnerability Disclosure](https://apis.io/security/humaans-io/humaans-io-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://humaans.io)
- [Documentation](https://docs.humaans.io)
- [Getting started](https://docs.humaans.io/api/introduction)
- [Pricing](https://humaans.io/pricing)
- [Blog](https://humaans.io/blog)
- [Security](https://humaans.io/security)
- [Terms of service](https://humaans.io/legal/terms-of-service)
- [Privacy policy](https://humaans.io/legal/privacy-policy)
- [GitHub](https://github.com/humaans)

## API Evangelist rating

**Kin Score 46.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 68.3 |
| Contract quality | 48.7 |
| Contract governance | 0.0 |
| Operational transparency | 15.8 |
| Developer ergonomics | 66.7 |
| Access clarity | 52.6 |

**Agent readiness 45.2** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | paginated |
| Operation Distinctiveness | distinct |

**Regulatory alignment 30.4** — Employment & Payroll

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/humaans-io/](https://apis.io/providers/humaans-io/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Humaans: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/humaans-io/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
