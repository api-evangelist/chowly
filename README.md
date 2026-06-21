# Chowly (chowly)

Chowly is a restaurant digital-ordering and delivery-integration platform that connects third-party delivery marketplaces (DoorDash, Uber Eats, Grubhub, and 150+ others) and direct online ordering into a restaurant's point-of-sale (POS) system. The Chowly platform injects third-party orders directly into the POS, synchronizes menus across every channel, and manages locations. Its developer surface is a partner-gated POS integration API keyed per location; the most commonly referenced operations are menu retrieval and order creation/retrieval.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/chowly/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/chowly/refs/heads/main/apis.yml)

## Tags

- Restaurants
- Online Ordering
- Delivery
- POS Integration
- Menu Sync

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Chowly Orders API

Receives third-party marketplace and direct online orders and injects them into the restaurant POS. Public client libraries reference order creation and order retrieval operations against the Chowly POS integration API. The full order surface is partner-gated and provisioned per location via an API key.

- **Human URL:** [https://www.chowly.com/solutions/order-integration/](https://www.chowly.com/solutions/order-integration/)
- **Base URL:** `https://api.chowlyinc.com`

#### Tags

- Orders
- Delivery
- POS Integration

#### Properties

- [Documentation](https://www.chowly.com/solutions/order-integration/)
- [OpenAPI](openapi/chowly-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chowly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chowly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chowly Menu Sync API

Publishes and synchronizes a single source-of-truth menu across 150+ third-party and direct ordering channels (marketed as MenuMatch). Public client libraries reference a menu retrieval operation against the Chowly POS integration API; the authoring/publishing surface is partner-gated.

- **Human URL:** [https://www.chowly.com/solutions/order-integration/](https://www.chowly.com/solutions/order-integration/)
- **Base URL:** `https://api.chowlyinc.com`

#### Tags

- Menu Sync
- Menu
- MenuMatch

#### Properties

- [Documentation](https://www.chowly.com/solutions/order-integration/)
- [OpenAPI](openapi/chowly-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/chowly.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/chowly.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Chowly Stores API

Restaurant store/location provisioning and management. Each location is keyed by its own Chowly API key, and the platform exposes a Manage Locations surface for enabling channels per store. No standalone public store/location endpoint is documented; the operation is described here for completeness.

- **Human URL:** [https://www.chowly.com/chowly-platform/](https://www.chowly.com/chowly-platform/)
- **Base URL:** `https://api.chowlyinc.com`

#### Tags

- Stores
- Locations
- Provisioning

#### Properties

- [Documentation](https://www.chowly.com/chowly-platform/)
- [OpenAPI](openapi/chowly-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Chowly Integrations API

Connects third-party delivery marketplaces (DoorDash, Uber Eats, Grubhub, and 150+ channels) and 50+ native POS systems (Toast, Square, SpotOn, Clover, and others). Marketplace and POS partners integrate through Chowly's partner program and webhook delivery rather than a documented public REST surface.

- **Human URL:** [https://partners.olo.com/partners/chowly/](https://partners.olo.com/partners/chowly/)
- **Base URL:** `https://api.chowlyinc.com`

#### Tags

- Integrations
- Marketplaces
- Webhooks

#### Properties

- [Documentation](https://www.chowly.com/solutions/order-integration/)

## Common Properties

- [GitHub Organization](https://github.com/Chowly)
- [LinkedIn](https://www.linkedin.com/company/chowly)
- [Website](https://www.chowly.com)
- [Documentation](https://chowly.help/s/faqs)
- [Plans](plans/chowly-plans-pricing.yml)
- [Rate Limits](rate-limits/chowly-rate-limits.yml)
- [Fin Ops](finops/chowly-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
