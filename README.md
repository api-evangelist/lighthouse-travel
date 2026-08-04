# Lighthouse (lighthouse-travel)

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

Lighthouse (formerly OTA Insight) is the commercial platform for the travel and hospitality industry, transforming data complexity into revenue growth for 80,000+ hotels across 185+ countries. Headquartered in London with offices across Europe, the Americas, and Asia-Pacific, Lighthouse combines market intelligence, business intelligence, and revenue management into a single SaaS suite. Core products include Rate Insight and Market Insight for competitive pricing and forward demand, Pricing Manager for automated revenue optimization, Benchmark Insight for Smart Compset competitive analysis, Business Intelligence for portfolio reporting, Parity Insight for distribution parity, Channel Manager for independent hotels, and newer AI products like KITT (AI receptionist) and Connect AI (ChatGPT direct-booking app). The platform processes 1.7 billion hotel rates per day across 300,000+ profiled competitor hotels. Lighthouse exposes a public, subscription-gated Integration API (api.mylighthouse.com, v3.1) for hotel customers and certified technology partners — covering Hotels, Markets, Rates, Demand, Ranking, Reviews, Parity, and Market Insight — and runs a partner program with 20+ named integrations including Mews, Infor, Duetto, Cendyn, Ideas, Atomize, SHR Group, and Cloudbeds. Revenue model is subscription SaaS sold by sales engagement; pricing is not published publicly.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/lighthouse-travel/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/lighthouse-travel/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** 3rd-Party

## Tags

- Hospitality
- Hotels
- Travel
- Revenue Management
- Market Intelligence
- Business Intelligence
- Pricing
- Rate Shopping
- Competitive Intelligence
- Distribution
- Parity
- Channel Manager
- Demand Forecasting
- SaaS
- AI

## Timestamps

- **Created:** 2026-05-25
- **Modified:** 2026-05-25

## APIs

### Lighthouse Integration API

The Lighthouse Integration API (v3.1, previously the OTA Insight API) enables subscribed hotels and certified technology partners to create periodic custom data extracts from Lighthouse's hotel competitive intelligence dataset. Endpoints cover Hotels, Markets, Rates (current and historic, by hotel and by room type), Demand predictions, Ranking positions and summaries, Review summaries, Parity comparisons, Parity Insight market scoring, and Market Insight demand and search-volume forecasts (next 351 days). Authentication uses an account-bound API token passed as the X-Oi-Authorization header. Rate limits are 20 requests per API per subscription per 24 hours and 120 requests per minute globally. Both JSON (default) and CSV output formats are supported, with optional gzip encoding. Access requires an active Lighthouse subscription; advanced endpoints (Live rateshopping, Raw Rates) require additional entitlements.

- **Human URL:** [https://api.mylighthouse.com/](https://api.mylighthouse.com/)
- **Base URL:** `https://api.mylighthouse.com/v3`

#### Tags

- Hotels
- Rates
- Demand
- Ranking
- Reviews
- Parity
- Market Insight
- Competitive Intelligence

#### Properties

- [Documentation](https://api.mylighthouse.com/)
- [OpenAPI](openapi/lighthouse-travel-integration-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/lighthouse-travel-integration-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/lighthouse-travel-integration-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Developer Announcement](https://www.mylighthouse.com/resources/blog/developer-solutions-suite-new-integration-api)
- [Partnerships](https://www.mylighthouse.com/company/partnerships)
- [Authentication](https://api.mylighthouse.com/)
- [Rate Limits](https://api.mylighthouse.com/)

## Common Properties

- [Website](https://www.mylighthouse.com)
- [About](https://www.mylighthouse.com/company/about)
- [Products](https://www.mylighthouse.com/products)
- [Pricing Manager](https://www.mylighthouse.com/products/pricing-manager)
- [Rate Insight](https://www.mylighthouse.com/products/rate-insight)
- [Market Insight](https://www.mylighthouse.com/products/market-insight)
- [Benchmark Insight](https://www.mylighthouse.com/products/benchmark-insight)
- [Business Intelligence](https://www.mylighthouse.com/products/business-intelligence)
- [Parity Insight](https://www.mylighthouse.com/products/parity-insight)
- [Channel Manager](https://www.mylighthouse.com/products/channel-manager)
- [Data Solutions](https://www.mylighthouse.com/data-services/hotel-data-solutions)
- [Developer Solutions](https://www.mylighthouse.com/resources/blog/developer-solutions-suite-new-integration-api)
- [A P I](https://api.mylighthouse.com/)
- [Marketplace](https://marketplace.mylighthouse.com/)
- [Partnerships](https://www.mylighthouse.com/company/partnerships)
- [Customers](https://www.mylighthouse.com/customers)
- [Resources](https://www.mylighthouse.com/resources)
- [Blog](https://www.mylighthouse.com/resources/blog)
- [Insights](https://www.mylighthouse.com/resources/insights)
- [Events](https://www.mylighthouse.com/resources/events)
- [Customer Care](https://www.mylighthouse.com/company/customer-care)
- [Trust](https://trust.mylighthouse.com)
- [Careers](https://www.mylighthouse.com/company/careers)
- [Contact Sales](https://www.mylighthouse.com/contact-sales)
- [Login](https://app.mylighthouse.com/login)
- [Git Hub](https://github.com/OTA-Insight)
- [Dev To](https://dev.to/lighthouse-intelligence)
- [LinkedIn](https://www.linkedin.com/company/lighthouseintelligence/)
- [YouTube](https://www.youtube.com/@HotelRevenueManagement)
- [Facebook](https://www.facebook.com/lighthouse.intel/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
