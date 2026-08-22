# Windstream Holdings (windstream-holdings)

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

Windstream Holdings is a leading provider of advanced network communications and technology solutions including managed services, cloud computing, and broadband to consumers and businesses across the United States. The company operates the Kinetic broadband brand for consumer and small business customers and Windstream Enterprise (now Uniti Solutions) for business customers, offering SD-WAN, UCaaS, OfficeSuite UC, contact center services, and high-capacity network transport. Windstream delivers voice, data, and managed networking solutions to more than 18 states with over 2.1 million fiber-to-the-premise passings.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Producer
- **Access:** 3rd-Party

## Tags

- Broadband
- Contact Center
- Managed Services
- Network Communications
- SD-WAN
- Telecom
- UCaaS
- Unified Communications

## Timestamps

- **Created:** 2026-05-03
- **Modified:** 2026-05-19

## APIs

### Windstream Enterprise Voice API

The Windstream Enterprise Voice API (silhouette) is a REST-based web service with WebSocket support for real-time events. It enables developers to make and receive calls, manage auto-attendants, control call routing, and configure Unified Communications settings for OfficeSuite UC deployments. The API accepts and delivers content in JSON format following HAL specifications.

- **Human URL:** [https://api.solutions.uniti.com/voice.html](https://api.solutions.uniti.com/voice.html)
- **Base URL:** `https://webadmin.windstreamenterprise.com/api`

#### Tags

- Voice
- UC
- Calls
- Auto-attendants
- OfficeSuite

#### Properties

- [Documentation](https://api.solutions.uniti.com/voice.html)
- [Portal](https://api.solutions.uniti.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-voice-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/windstream-contact-center.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windstream-contact-center.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/windstream-voice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windstream-voice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Windstream Enterprise Contact Center Services API

The Windstream Enterprise Contact Center Services (CCS) API provides programmatic access to contact center operations, enabling developers to route calls, web chats, and text messages, manage agent states, configure tenants, and monitor queue activity. The REST API is complemented by a WebSocket interface for real-time event streaming.

- **Human URL:** [https://api.solutions.uniti.com/ccs.html](https://api.solutions.uniti.com/ccs.html)
- **Base URL:** `https://ccs.windstreamenterprise.com/6/v2/api`

#### Tags

- Contact Center
- Calls
- Agents
- Queues
- UCaaS

#### Properties

- [Documentation](https://api.solutions.uniti.com/ccs.html)
- [Portal](https://api.solutions.uniti.com/)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/openapi/windstream-contact-center-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/windstream-contact-center.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windstream-contact-center.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/windstream-voice.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/windstream-voice.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://www.windstreamenterprise.com/)
- [Portal](https://api.solutions.uniti.com/)
- [Developer Hub](https://solutions.uniti.com/developer-hub)
- [A P I Marketplace](https://api.solutions.uniti.com/)
- [Documentation](https://api.solutions.uniti.com/)
- [Salesforc Integration](https://solutions.uniti.com/developer-hub/app-gallery/salesforce-api)
- [LinkedIn](https://www.linkedin.com/company/windstream-enterprise)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/json-ld/windstream-holdings-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/vocabulary/windstream-holdings-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
