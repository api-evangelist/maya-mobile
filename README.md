# Maya Mobile (maya-mobile)

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
