# Windstream Holdings

Windstream Holdings is a leading provider of advanced network communications and technology solutions including managed services, cloud computing, and broadband to consumers and businesses across the United States. The company operates the Kinetic broadband brand for consumer and small business customers and Windstream Enterprise (Uniti Solutions) for enterprise customers, offering SD-WAN, UCaaS, OfficeSuite UC, contact center services, and high-capacity network transport across 18 states.

**URL:** [https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/windstream-holdings/refs/heads/main/apis.yml)

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
- **Modified:** 2026-05-03

## APIs

### Windstream Enterprise Voice API
The Voice API (silhouette) is a REST/WebSocket API for call control, extension management, auto-attendant configuration, and OfficeSuite UC management. Uses HAL hypermedia format.

**Human URL:** [https://api.solutions.uniti.com/voice.html](https://api.solutions.uniti.com/voice.html)

| Type | URL |
|------|-----|
| Documentation | https://api.solutions.uniti.com/voice.html |
| OpenAPI | [windstream-voice-openapi.yml](openapi/windstream-voice-openapi.yml) |

### Windstream Enterprise Contact Center Services API
The CCS API enables contact center operations — call routing, agent state management, tenant configuration, ACD queue monitoring, and multi-channel messaging (voice, chat, SMS).

**Human URL:** [https://api.solutions.uniti.com/ccs.html](https://api.solutions.uniti.com/ccs.html)

| Type | URL |
|------|-----|
| Documentation | https://api.solutions.uniti.com/ccs.html |
| OpenAPI | [windstream-contact-center-openapi.yml](openapi/windstream-contact-center-openapi.yml) |

## Common Properties

| Type | URL |
|------|-----|
| Website | https://www.windstreamenterprise.com/ |
| API Marketplace | https://api.solutions.uniti.com/ |
| Developer Hub | https://solutions.uniti.com/developer-hub |

## Artifacts

### OpenAPI Specifications
- [windstream-voice-openapi.yml](openapi/windstream-voice-openapi.yml) — Voice API with call control, extensions, auto-attendants
- [windstream-contact-center-openapi.yml](openapi/windstream-contact-center-openapi.yml) — CCS API with call management, agent state, tenant admin

### Spectral Rules
- [windstream-holdings-rules.yml](rules/windstream-holdings-rules.yml)

### Naftiko Capabilities

#### Shared Definitions
- [capabilities/shared/windstream-voice.yaml](capabilities/shared/windstream-voice.yaml)
- [capabilities/shared/windstream-contact-center.yaml](capabilities/shared/windstream-contact-center.yaml)

#### Workflow Capabilities
- [capabilities/unified-communications.yaml](capabilities/unified-communications.yaml) — Voice + CCS unified workflow (17 tools)

### JSON Schema
- [windstream-call-schema.json](json-schema/windstream-call-schema.json)
- [windstream-extension-schema.json](json-schema/windstream-extension-schema.json)

### JSON-LD Context
- [windstream-holdings-context.jsonld](json-ld/windstream-holdings-context.jsonld)

### Examples
- [windstream-make-call-example.json](examples/windstream-make-call-example.json)
- [windstream-list-calls-example.json](examples/windstream-list-calls-example.json)

### Vocabulary
- [windstream-holdings-vocabulary.yml](vocabulary/windstream-holdings-vocabulary.yml)

## Maintainers

**Kin Lane** — kin@apievangelist.com
