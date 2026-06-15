# McAfee (Trellix) (mcafee)

APIs for McAfee Enterprise security products and services. McAfee Enterprise rebranded as Trellix in 2022, but its on-premises and SaaS platforms (ePO, MVISION, ESM, Web Gateway, TIE, DXL) continue to expose REST APIs documented here for centralized security management, threat intelligence, EDR, messaging, and SIEM integration.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Antivirus
- Cybersecurity
- Endpoint Protection
- Security
- Threat Intelligence

## Timestamps

- **Created:** 2024-01-20
- **Modified:** 2026-05-19

## APIs

### McAfee ePO API

McAfee ePolicy Orchestrator (ePO) REST API for centralized security management, including system management, policy assignment, task scheduling, query execution, and threat event retrieval across managed endpoints.

- **Human URL:** [https://www.trellix.com/products/epo/](https://www.trellix.com/products/epo/)
- **Base URL:** `https://your-epo-server:8443/remote`

#### Tags

- Endpoint Management
- Policy Orchestrator
- Security Management

#### Properties

- [Documentation](https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide)
- [Authentication](https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide)
- [OpenAPI](openapi/mcafee-epo-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mcafee-epo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-epo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### McAfee MVISION API

Cloud-native security platform API for endpoint detection and response (EDR), threat prevention, device management, and incident investigation.

- **Human URL:** [https://www.trellix.com/](https://www.trellix.com/)
- **Base URL:** `https://api.mvision.mcafee.com`

#### Tags

- Cloud Security
- EDR
- MVISION
- Threat Detection

#### Properties

- [Documentation](https://developer.mcafee.com/)
- [OpenAPI](openapi/mcafee-mvision-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mcafee-mvision.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-mvision.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### McAfee Threat Intelligence Exchange (TIE) API

Real-time threat intelligence sharing and reputation services API.

- **Human URL:** [https://www.trellix.com/](https://www.trellix.com/)
- **Base URL:** `https://your-tie-server/api`

#### Tags

- Malware Analysis
- Reputation
- Threat Intelligence

#### Properties

- [Documentation](https://opendxl.github.io/opendxl-tie-client-python/)
- [SDK](https://github.com/opendxl/opendxl-tie-client-python)
- [Postman Collection](collections/mcafee-epo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-epo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-esm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-esm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-mvision.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-mvision.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-web-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-web-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### McAfee Data Exchange Layer (DXL) API

Messaging fabric for real-time security data exchange and integration.

- **Human URL:** [https://www.trellix.com/](https://www.trellix.com/)
- **Base URL:** `https://your-dxl-broker`

#### Tags

- Data Exchange
- Fabric
- Integration
- Messaging

#### Properties

- [Documentation](https://opendxl.github.io/opendxl-client-python/)
- [Git Hub](https://github.com/opendxl)
- [S D K -  Python](https://github.com/opendxl/opendxl-client-python)
- [S D K -  Java Script](https://github.com/opendxl/opendxl-client-javascript)
- [Postman Collection](collections/mcafee-epo.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-epo.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-esm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-esm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-mvision.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-mvision.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/mcafee-web-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-web-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### McAfee Web Gateway API

Web security gateway REST API for managing rule sets, URL filtering lists, SSL inspection settings, and monitoring proxy traffic and appliance health.

- **Human URL:** [https://www.trellix.com/](https://www.trellix.com/)
- **Base URL:** `https://your-mwg-server/Konfigurator/REST`

#### Tags

- Proxy
- Web Gateway
- Web Security

#### Properties

- [Documentation](https://docs.trellix.com/bundle/web-gateway-product-guide)
- [OpenAPI](openapi/mcafee-web-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mcafee-web-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-web-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### McAfee ESM API

Enterprise Security Manager SIEM REST API for managing security events, alarms, watchlists, data sources, cases, and executing queries against the event database.

- **Human URL:** [https://www.trellix.com/](https://www.trellix.com/)
- **Base URL:** `https://your-esm-server/rs/esm`

#### Tags

- Log Management
- Security Events
- SIEM

#### Properties

- [Documentation](https://docs.trellix.com/bundle/enterprise-security-manager-api-reference-guide)
- [OpenAPI](openapi/mcafee-esm-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mcafee-esm.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mcafee-esm.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/mcafee)
- [Developer  Portal](https://developer.mcafee.com)
- [Website](https://www.trellix.com/)
- [Support](https://www.trellix.com/support/)
- [Terms of Service](https://www.trellix.com/about/legal/)
- [Privacy Policy](https://www.trellix.com/about/legal/privacy/)
- [JSON-LD](json-ld/mcafee-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/mcafee-threat-event-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/mcafee-endpoint-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
