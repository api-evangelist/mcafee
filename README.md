# McAfee (mcafee)
APIs for McAfee Enterprise security products and services. McAfee Enterprise rebranded as Trellix in 2022, but its on-premises and SaaS platforms (ePO, MVISION, ESM, Web Gateway, TIE, DXL) continue to expose REST APIs documented here for centralized security management, threat intelligence, EDR, messaging, and SIEM integration.

**URL:** [Visit APIs.json URL](https://raw.githubusercontent.com/api-evangelist/mcafee/refs/heads/main/apis.yml)

## Scope

- **Type:** Index 
- **Position:** Consuming 
- **Access:** 3rd-Party 

## Tags:

 - Security, Antivirus, Endpoint Protection, Threat Intelligence, Cybersecurity

## Timestamps

- **Created:** 2024-01-20 
- **Modified:** 2026-04-28 

## APIs

### McAfee ePO API
McAfee ePolicy Orchestrator (ePO) REST API for centralized security management, including system management, policy assignment, task scheduling, query execution, and threat event retrieval across managed endpoints.

**Human URL:** [https://www.trellix.com/products/epo/](https://www.trellix.com/products/epo/)

#### Tags:

 - Endpoint Management, Policy Orchestrator, Security Management

#### Properties

- [Documentation](https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide)
- [Authentication](https://docs.trellix.com/bundle/epolicy-orchestrator-web-api-reference-guide)
- [OpenAPI](openapi/mcafee-epo-openapi.yml)

### McAfee MVISION API
Cloud-native security platform API for endpoint detection and response (EDR), threat prevention, device management, and incident investigation.

**Human URL:** [https://www.trellix.com/](https://www.trellix.com/)

#### Tags:

 - Cloud Security, EDR, MVISION, Threat Detection

#### Properties

- [Documentation](https://developer.mcafee.com/)
- [OpenAPI](openapi/mcafee-mvision-openapi.yml)

### McAfee Threat Intelligence Exchange (TIE) API
Real-time threat intelligence sharing and reputation services API.

**Human URL:** [https://www.trellix.com/](https://www.trellix.com/)

#### Tags:

 - Malware Analysis, Reputation, Threat Intelligence

#### Properties

- [Documentation](https://opendxl.github.io/opendxl-tie-client-python/)
- [SDK](https://github.com/opendxl/opendxl-tie-client-python)

### McAfee Data Exchange Layer (DXL) API
Messaging fabric for real-time security data exchange and integration.

**Human URL:** [https://www.trellix.com/](https://www.trellix.com/)

#### Tags:

 - Data Exchange, Fabric, Integration, Messaging

#### Properties

- [Documentation](https://opendxl.github.io/opendxl-client-python/)
- [GitHub](https://github.com/opendxl)
- [SDK - Python](https://github.com/opendxl/opendxl-client-python)
- [SDK - JavaScript](https://github.com/opendxl/opendxl-client-javascript)

### McAfee Web Gateway API
Web security gateway REST API for managing rule sets, URL filtering lists, SSL inspection settings, and monitoring proxy traffic and appliance health.

**Human URL:** [https://www.trellix.com/](https://www.trellix.com/)

#### Tags:

 - Proxy, Web Gateway, Web Security

#### Properties

- [Documentation](https://docs.trellix.com/bundle/web-gateway-product-guide)
- [OpenAPI](openapi/mcafee-web-gateway-openapi.yml)

### McAfee ESM API
Enterprise Security Manager SIEM REST API for managing security events, alarms, watchlists, data sources, cases, and executing queries against the event database.

**Human URL:** [https://www.trellix.com/](https://www.trellix.com/)

#### Tags:

 - Log Management, Security Events, SIEM

#### Properties

- [Documentation](https://docs.trellix.com/bundle/enterprise-security-manager-api-reference-guide)
- [OpenAPI](openapi/mcafee-esm-openapi.yml)

## Common Properties

- [Developer Portal](https://developer.mcafee.com)
- [Website](https://www.trellix.com/)
- [Support](https://www.trellix.com/support/)
- [Terms of Service](https://www.trellix.com/about/legal/)
- [Privacy Policy](https://www.trellix.com/about/legal/privacy/)
- [JSON-LD](json-ld/mcafee-context.jsonld)
- [JSONSchema](json-schema/mcafee-threat-event-schema.json)
- [JSONSchema](json-schema/mcafee-endpoint-schema.json)

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
