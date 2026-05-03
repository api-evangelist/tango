# Tango

Tango (formerly Tango Card) is a rewards-as-a-service platform that provides APIs for automating digital reward and incentive delivery. The Tango RaaS API enables companies to integrate a global catalog of 3,100+ digital gift cards, prepaid cards, and charitable donations directly into their products and workflows. Tango serves loyalty programs, research panels, employee recognition platforms, and consumer incentive applications worldwide.

**Website:** https://www.tangocard.com/  
**Developer Portal:** https://developers.tangocard.com/  
**Sandbox:** https://portal.sandbox.tangocard.com

## APIs

### Tango RaaS API

The Tango Rewards-as-a-Service (RaaS) API v2 is a RESTful interface for automating digital reward and incentive delivery. Key capabilities include:

- **Catalog Management** — Browse 3,100+ digital gift cards, prepaid cards, and charitable donations
- **Account Management** — Manage customer accounts, sub-accounts, and funding balances
- **Order Placement** — Send digital rewards to recipients via email
- **Order Tracking** — Monitor order status and retrieve fulfillment credentials
- **Digital Templates** — Customize reward delivery email templates

**Base URL (Production):** `https://api.tangocard.com/raas/v2`  
**Authentication:** HTTP Basic Auth or OAuth 2.0

**Documentation:** https://developers.tangocard.com/docs/user-guide-tango-api-v2

## Artifacts

### OpenAPI Specifications

| File | Description |
|------|-------------|
| [openapi/tango-raas-api-openapi.yml](openapi/tango-raas-api-openapi.yml) | Tango RaaS API v2 — customers, accounts, catalog, orders, line items, templates |

### JSON Schemas

| File | Description |
|------|-------------|
| [json-schema/tango-order-schema.json](json-schema/tango-order-schema.json) | Reward order and line item schema |
| [json-schema/tango-account-schema.json](json-schema/tango-account-schema.json) | Customer account schema |
| [json-schema/tango-catalog-item-schema.json](json-schema/tango-catalog-item-schema.json) | Catalog brand and product schema |

### JSON Structures

| File | Description |
|------|-------------|
| [json-structure/tango-order-structure.json](json-structure/tango-order-structure.json) | Documented structure of a Tango reward order |

### JSON-LD Context

| File | Description |
|------|-------------|
| [json-ld/tango-context.jsonld](json-ld/tango-context.jsonld) | JSON-LD context mapping Tango vocabulary to schema.org |

### Spectral Rules

| File | Description |
|------|-------------|
| [rules/tango-rules.yml](rules/tango-rules.yml) | Spectral ruleset enforcing Tango API conventions |

### Naftiko Capabilities

| File | Description |
|------|-------------|
| [capabilities/reward-automation.yaml](capabilities/reward-automation.yaml) | Workflow capability for automated reward delivery (10 tools) |
| [capabilities/shared/raas-api.yaml](capabilities/shared/raas-api.yaml) | Shared RaaS API consumed definition |

### Examples

| File | Description |
|------|-------------|
| [examples/tango-create-order-example.json](examples/tango-create-order-example.json) | Example: Create a reward order |
| [examples/tango-get-catalog-example.json](examples/tango-get-catalog-example.json) | Example: Browse the reward catalog |
| [examples/tango-list-customers-example.json](examples/tango-list-customers-example.json) | Example: List customers |

### Vocabulary

| File | Description |
|------|-------------|
| [vocabulary/tango-vocabulary.yml](vocabulary/tango-vocabulary.yml) | Tango domain vocabulary and terminology |

## Tags

Catalog Management, Digital Rewards, Gift Cards, Incentives, Loyalty, Rewards As A Service

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
