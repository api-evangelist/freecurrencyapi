# Free Currency API

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Free Currency API provides real-time and historical currency exchange rate data for 150+ currencies via a simple REST API. No registration is required for basic usage, making it accessible for hobby and development projects. The API is operated by Everapi and offers daily-updated current exchange rates, historical rates dating back to 1999, and official SDKs for JavaScript, Python, PHP, Go, Ruby, Rust, C#, and R.

**Human URL:** https://freecurrencyapi.com/

**Base URL:** https://api.freecurrencyapi.com/v1

## Properties

| Type | URL |
|------|-----|
| Website | https://freecurrencyapi.com/ |
| Documentation | https://freecurrencyapi.com/docs |
| GitHub Org | https://github.com/everapihq |
| Status Endpoint | https://api.freecurrencyapi.com/v1/status |
| Plans & Pricing | plans/freecurrencyapi-plans-pricing.yml |
| Rate Limits | rate-limits/freecurrencyapi-rate-limits.yml |
| FinOps | finops/freecurrencyapi-finops.yml |

## Endpoints

| Endpoint | URL |
|----------|-----|
| Status | GET /status |
| Currencies | GET /currencies |
| Latest Rates | GET /latest |
| Historical Rates | GET /historical |

## Authentication

API key required via `apikey` query parameter or `apikey` HTTP request header.

## Plans

- **Free**: 1,000 monthly requests, 32+ currencies, daily updates, non-commercial use only
- **Commercial**: See [currencyapi.com](https://currencyapi.com/) for paid plans with higher limits and commercial rights

## Maintainers

**Kin Lane** — kin@apievangelist.com
