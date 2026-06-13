# Free Currency API

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
