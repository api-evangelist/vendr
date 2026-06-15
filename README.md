# Vendr (vendr)

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
