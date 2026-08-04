# Vendr (vendr)

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

Vendr is a SaaS procurement intelligence platform that helps businesses manage software spending through data-driven pricing insights and negotiation guidance. The Vendr API (OpenPrice API) provides access to real contract pricing data from 200,000+ verified software agreements across 20,000+ products, enabling developers to embed fair pricing estimates, negotiation insights, product catalog data, and purchase scope management into their applications.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Pricing
- Procurement
- SaaS
- Software Spend Management
- Negotiation

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Vendr OpenPrice API

The Vendr OpenPrice API provides access to real SaaS pricing intelligence derived from 200,000+ verified software contracts across 20,000+ products. It enables applications to retrieve structured catalog data, generate fair price estimates with confidence scoring, define purchase scope requirements, and subscribe to webhook events. Authentication uses API key via the X-API-Key header. Rate limits are 250 requests per minute and 150,000 requests per day.

- **Human URL:** [https://developers.vendr.com/docs/introduction](https://developers.vendr.com/docs/introduction)
- **Base URL:** `https://api.vendr.com`

#### Tags

- Pricing
- Procurement
- SaaS
- Catalog
- Webhooks

#### Properties

- [Documentation](https://developers.vendr.com/docs/introduction)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/openapi/vendr-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-schema/vendr-pricing-response-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/json-schema/vendr-catalog-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/rules/vendr-rules.yml)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/vocabulary/vendr-vocabulary.yml)
- [Postman Collection](collections/vendr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vendr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Vendr MCP Server

The Vendr Model Context Protocol (MCP) server exposes Vendr pricing intelligence to AI agents via the MCP standard. It provides tools for searching the product catalog, retrieving custom price estimates, and obtaining negotiation insights. Requires a Vendr API key.

- **Human URL:** [https://github.com/vendrinc/vendr-mcp](https://github.com/vendrinc/vendr-mcp)
- **Base URL:** `https://api.vendr.com`

#### Tags

- MCP
- AI Agents
- Pricing
- Procurement

#### Properties

- [Documentation](https://github.com/vendrinc/vendr-mcp)
- [GitHub Repository](https://github.com/vendrinc/vendr-mcp)
- [Postman Collection](collections/vendr.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/vendr.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/vendr-co)
- [Website](https://www.vendr.com/)
- [Documentation](https://developers.vendr.com/docs/introduction)
- [Pricing Page](https://www.vendr.com/pricing-api)
- [GitHub Organization](https://github.com/vendrinc)
- [Support](mailto:developers@vendr.com)
- [Rate Limits](https://developers.vendr.com/docs/introduction)
- [Authentication](https://developers.vendr.com/docs/introduction)
- [Integrations](https://www.vendr.com/integrations)
- [M C P Server](https://github.com/vendrinc/vendr-mcp)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
