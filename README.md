# McAfee (Trellix) (mcafee)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
