# Vendr

Vendr is a SaaS procurement intelligence platform that helps businesses manage software spending through data-driven pricing insights and negotiation guidance. The Vendr OpenPrice API provides access to real contract pricing data from 200,000+ verified software agreements across 20,000+ products.

**URL:** [https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/vendr/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Pricing, Procurement, SaaS, Software Spend Management, Negotiation

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## APIs

### Vendr OpenPrice API

The Vendr OpenPrice API provides access to real SaaS pricing intelligence derived from 200,000+ verified software contracts across 20,000+ products. Enables catalog search, fair price estimation, scope definition, and webhook event subscriptions. Authentication uses API key via `X-API-Key` header. Rate limits: 250 req/min, 150,000 req/day.

**Human URL:** [https://developers.vendr.com/docs/introduction](https://developers.vendr.com/docs/introduction)

**Base URL:** `https://api.vendr.com`

**Tags:** Pricing, Procurement, SaaS, Catalog, Webhooks

**Endpoints:**
- `GET /v1/catalog` — Search Catalog
- `POST /v1/scope` — Submit Scope
- `POST /v1/pricing` — Get Pricing Estimate
- `GET /v1/webhooks` — List Webhooks
- `POST /v1/webhooks` — Create Webhook
- `DELETE /v1/webhooks/{webhookId}` — Delete Webhook

#### Properties

- [Documentation](https://developers.vendr.com/docs/introduction)
- [OpenAPI](openapi/vendr-openapi.yml)
- [JSON Schema - Pricing Response](json-schema/vendr-pricing-response-schema.json)
- [JSON Schema - Catalog Product](json-schema/vendr-catalog-product-schema.json)
- [Spectral Rules](rules/vendr-rules.yml)
- [Vocabulary](vocabulary/vendr-vocabulary.yml)

### Vendr MCP Server

The Vendr Model Context Protocol server exposes pricing intelligence to AI agents, providing tools for catalog search, price estimation, and negotiation insights.

**Human URL:** [https://github.com/vendrinc/vendr-mcp](https://github.com/vendrinc/vendr-mcp)

**Tags:** MCP, AI Agents, Pricing, Procurement

#### Properties

- [Documentation](https://github.com/vendrinc/vendr-mcp)
- [GitHubRepository](https://github.com/vendrinc/vendr-mcp)

## Capabilities

### Shared Definitions

| File | Description |
|---|---|
| [capabilities/shared/vendr-openapi.yaml](capabilities/shared/vendr-openapi.yaml) | Vendr OpenPrice API — catalog, pricing, scope, webhooks (6 operations) |

### Workflow Capabilities

| Capability | APIs | Tools |
|---|---|---|
| [saas-procurement-intelligence](capabilities/saas-procurement-intelligence.yaml) | Vendr OpenPrice | 6 MCP tools |

## Artifacts

| Type | Files |
|---|---|
| OpenAPI | [openapi/vendr-openapi.yml](openapi/vendr-openapi.yml) |
| JSON Schema | [json-schema/vendr-pricing-response-schema.json](json-schema/vendr-pricing-response-schema.json), [json-schema/vendr-catalog-product-schema.json](json-schema/vendr-catalog-product-schema.json) |
| JSON Structure | [json-structure/vendr-pricing-response-structure.json](json-structure/vendr-pricing-response-structure.json) |
| JSON-LD | [json-ld/vendr-context.jsonld](json-ld/vendr-context.jsonld) |
| Examples | [examples/](examples/) (4 examples) |
| Spectral Rules | [rules/vendr-rules.yml](rules/vendr-rules.yml) |
| Vocabulary | [vocabulary/vendr-vocabulary.yml](vocabulary/vendr-vocabulary.yml) |

## Common Properties

- [Website](https://www.vendr.com/)
- [Documentation](https://developers.vendr.com/docs/introduction)
- [Pricing API](https://www.vendr.com/pricing-api)
- [GitHub Organization](https://github.com/vendrinc)
- [Support](mailto:developers@vendr.com)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
