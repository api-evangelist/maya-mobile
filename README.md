# Maya Mobile (maya-mobile)

Maya Mobile (Mobile Maya Inc) is a US-based global eSIM and connectivity platform aggregating 400+ roaming networks across 200+ destinations. Its Connect+ Connectivity REST API lets resellers and developers provision eSIMs, assign data packages, monitor activation status and data usage, suspend or reactivate lines, process top-ups, and receive lifecycle events via webhooks.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/maya-mobile/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/maya-mobile/refs/heads/main/apis.yml)

> Note: Maya Mobile distributes the full Connect+ Connectivity API reference to onboarded resellers and partners under NDA. The catalog below models the publicly described REST capability surface (eSIM provisioning, data packages/plans, status and usage, top-ups, orders, and webhooks). Exact endpoint paths and schemas are confirmed during onboarding; unreconciled artifacts are marked `reconciled: false`.

## Tags

- eSIM
- Connectivity
- Mobile Data
- Roaming
- Telecom

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Maya Mobile Plans and Products API

Lists pre-made data plans and the catalog of countries, regions, and roaming networks available for building eSIM data packages, plus support for custom package templates (fixed-limit, time-limited, unlimited, or throttled traffic policies).

- **Human URL:** [https://maya.net/business/esim-api](https://maya.net/business/esim-api)
- **Base URL:** `https://api.maya.net/connectivity/v1`

#### Tags

- Plans
- Products
- Data Packages
- Catalog

#### Properties

- [Documentation](https://maya.net/business/esim-api)
- [OpenAPI](openapi/maya-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maya-mobile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maya-mobile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maya Mobile eSIMs and Provisioning API

Requests an eSIM with a selected roaming profile and returns the activation code and QR code ready to install, and lets you suspend or reactivate an eSIM anywhere in the world.

- **Human URL:** [https://maya.net/business/esim-api](https://maya.net/business/esim-api)
- **Base URL:** `https://api.maya.net/connectivity/v1`

#### Tags

- eSIMs
- Provisioning
- Activation
- QR Code

#### Properties

- [Documentation](https://maya.net/business/esim-api)
- [OpenAPI](openapi/maya-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maya-mobile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maya-mobile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maya Mobile Usage and Topup API

Returns real-time eSIM installation status and data-usage reporting, and adds (tops up) more data to an existing eSIM via additional data packages.

- **Human URL:** [https://maya.net/business/esim-api](https://maya.net/business/esim-api)
- **Base URL:** `https://api.maya.net/connectivity/v1`

#### Tags

- Usage
- Status
- Topup
- Reporting

#### Properties

- [Documentation](https://maya.net/business/esim-api)
- [OpenAPI](openapi/maya-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maya-mobile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maya-mobile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maya Mobile Orders API

Places and assigns data-package orders against eSIMs for specific countries, regions, and networks, supporting one or multiple packages per eSIM.

- **Human URL:** [https://maya.net/business/esim-api](https://maya.net/business/esim-api)
- **Base URL:** `https://api.maya.net/connectivity/v1`

#### Tags

- Orders
- Data Packages
- Fulfillment

#### Properties

- [Documentation](https://maya.net/business/esim-api)
- [OpenAPI](openapi/maya-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/maya-mobile.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/maya-mobile.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Maya Mobile Webhooks

Pushes eSIM lifecycle and data-usage events to a partner callback URL (installation, activation, low-balance, and usage updates) and can trigger SMS notifications to user devices for key lifecycle events.

- **Human URL:** [https://maya.net/business/esim-api](https://maya.net/business/esim-api)
- **Base URL:** `https://api.maya.net/connectivity/v1`

#### Tags

- Webhooks
- Callbacks
- Events
- SMS Notifications

#### Properties

- [Documentation](https://maya.net/business/esim-api)
- [OpenAPI](openapi/maya-mobile-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mayamobile-us)
- [Website](https://maya.net/)
- [Documentation](https://maya.net/business/esim-api)
- [Plans](plans/maya-mobile-plans-pricing.yml)
- [Rate Limits](rate-limits/maya-mobile-rate-limits.yml)
- [Fin Ops](finops/maya-mobile-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
