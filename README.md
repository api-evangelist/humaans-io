# Humaans (humaans-io)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/humaans-io/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/humaans-io/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

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

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Humaans API

REST API for the Humaans HRIS exposing People, Companies, Compensations,
Bank Accounts, Documents, Time Away (entries, allocations, policies, types),
Equipment, Job Roles, Locations, Custom Fields and Values, Performance
(reviews, cycles, templates, ratings), Timesheet entries and submissions,
Webhooks, Audit Events, and Working Patterns. Bearer token authentication
with OAuth-style scopes (public:read, private:read, private:write,
compensations:read/write, documents:read/write, webhooks:manage). JSON in /
JSON out, standard HTTP verbs, $limit/$skip pagination, $in/$nin/$gt/$gte/$lt/$lte/$or
filter operators, and HMAC SHA-256 signed webhook deliveries with retry and
automatic disablement after 5 days of failures.

- **Human URL:** [https://docs.humaans.io/api/](https://docs.humaans.io/api/)
- **Base URL:** `https://app.humaans.io/api`

#### Tags

- HR
- HRIS
- Human Resources
- People Operations
- Employees
- Time Off
- Compensation
- Payroll
- Onboarding
- Performance
- Timesheets
- Webhooks

#### Properties

- [Documentation](https://docs.humaans.io/api/)
- [Documentation](https://docs.humaans.io/api/introduction)
- [OpenAPI](openapi/humaans-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/humaans-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/humaans-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Portal](https://humaans.io)
- [Web Site](https://humaans.io)
- [Documentation](https://docs.humaans.io)
- [Documentation](https://docs.humaans.io/api/)
- [Getting Started](https://docs.humaans.io/api/introduction)
- [Sign In](https://app.humaans.io)
- [Sign Up](https://humaans.io/get-started)
- [Pricing](https://humaans.io/pricing)
- [Integrations](https://humaans.io/integrations)
- [Security](https://humaans.io/security)
- [Privacy Policy](https://humaans.io/legal/privacy-policy)
- [Terms of Service](https://humaans.io/legal/terms-of-service)
- [Documentation](https://humaans.io/legal/dpa)
- [Documentation](https://humaans.io/legal/sub-processors)
- [Blog](https://humaans.io/blog)
- [Case Studies](https://humaans.io/customers)
- [About](https://humaans.io/about)
- [Careers](https://humaans.io/careers)
- [Contact](https://humaans.io/contact)
- [Support](mailto:hi@humaans.io)
- [LinkedIn](https://www.linkedin.com/company/humaans)
- [Twitter](https://twitter.com/humaans_io)
- [GitHub Organization](https://github.com/humaans)
- [SDK](https://github.com/humaans/figbird)
- [SDK](https://github.com/humaans/next-img)
- [SDK](https://github.com/humaans/react-machine)
- [SDK](https://github.com/humaans/react-space-router)
- [Tool](https://github.com/humaans/workalendar)
- [Application](https://apps.apple.com/app/humaans/id1610537316)
- [Application](https://play.google.com/store/apps/details?id=io.humaans)
- [Reviews](https://www.g2.com/products/humaans/reviews)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
