# Lighthouse

Lighthouse (formerly OTA Insight) is the commercial platform for the travel
and hospitality industry, serving 80,000+ hotels across 185+ countries with
revenue management, market intelligence, and business intelligence in a
single SaaS suite. The platform processes 1.7 billion hotel rates per day
across 300,000+ profiled competitor hotels.

## Products

- **Rate Insight** — competitive pricing intelligence
- **Market Insight** — forward-looking demand forecasting
- **Pricing Manager** — automated revenue optimization
- **Benchmark Insight** — Smart Compset competitive analysis
- **Business Intelligence** — portfolio reporting and optimization
- **Parity Insight** — distribution parity issue resolution
- **Channel Manager** — AI channel management for independent hotels
- **KITT** — AI receptionist
- **Connect AI** — direct-booking app in ChatGPT

## Integration API

Lighthouse exposes a public, subscription-gated [Integration API](https://api.mylighthouse.com/)
(v3.1, base `https://api.mylighthouse.com/v3`) covering Hotels, Markets,
Rates, Demand, Ranking, Reviews, Parity, and Market Insight. Authentication
uses an account-bound `X-Oi-Authorization` header. Rate limits are 20
requests per API per subscription per 24 hours, with a 120 requests/minute
global ceiling. JSON (default) and CSV outputs are supported.

The API is part of the [Lighthouse Developer Solutions Suite](https://www.mylighthouse.com/resources/blog/developer-solutions-suite-new-integration-api),
which supports certified integrations across Business Intelligence,
Benchmark Insight, Pricing Manager, and Channel Manager — with a
[Partner Program](https://www.mylighthouse.com/company/partnerships) for
Integration, Data, and Referral partners.

## Artifacts

- [`apis.yml`](apis.yml) — APIs.json profile
- [`openapi/lighthouse-travel-integration-api-openapi.yml`](openapi/lighthouse-travel-integration-api-openapi.yml) — Integration API OpenAPI 3.1 spec

## Links

- Website: <https://www.mylighthouse.com>
- API docs: <https://api.mylighthouse.com/>
- Marketplace: <https://marketplace.mylighthouse.com/>
- Trust / security: <https://trust.mylighthouse.com>
- Login: <https://app.mylighthouse.com/login>
- GitHub (legacy): <https://github.com/OTA-Insight>
- LinkedIn: <https://www.linkedin.com/company/lighthouseintelligence/>
