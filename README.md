# Mendable (mendable)

Mendable is an AI answers and enterprise search platform that lets teams ingest their documentation, websites, and knowledge sources and serve grounded, cited AI chat answers over them. Built by the Firecrawl / Mendable team, it exposes a REST API at https://api.mendable.ai/v1 for creating conversations, asking questions over ingested content with streaming, ingesting and managing data sources, and rating answers.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/mendable/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/mendable/refs/heads/main/apis.yml)

## Tags

- AI
- Answers
- Enterprise Search
- RAG
- Support

## Timestamps

- **Created:** 2026-06-20
- **Modified:** 2026-06-20

## APIs

### Mendable Chat & Answers API

Ask natural-language questions over ingested documentation and knowledge sources via the mendableChat endpoint, returning grounded answers with citations. Supports Server-Sent Events streaming, conversation history, retriever options, metadata filtering, and tool calls.

- **Human URL:** [https://docs.mendable.ai/mendable-api/chat](https://docs.mendable.ai/mendable-api/chat)
- **Base URL:** `https://api.mendable.ai/v1`

#### Tags

- Chat
- Answers
- RAG
- Streaming

#### Properties

- [Documentation](https://docs.mendable.ai/mendable-api/chat)
- [API Reference](https://docs.mendable.ai/mendable-api/overview)
- [OpenAPI](openapi/mendable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mendable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mendable Conversations API

Create a new conversation to obtain a conversation_id used to group a series of chat interactions into a single grounded session.

- **Human URL:** [https://docs.mendable.ai/mendable-api/conversation](https://docs.mendable.ai/mendable-api/conversation)
- **Base URL:** `https://api.mendable.ai/v1`

#### Tags

- Conversations
- Sessions

#### Properties

- [Documentation](https://docs.mendable.ai/mendable-api/conversation)
- [API Reference](https://docs.mendable.ai/mendable-api/overview)
- [OpenAPI](openapi/mendable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mendable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mendable Data Ingestion & Sources API

Ingest websites, sitemaps, GitHub repos, Docusaurus sites, YouTube transcripts, single URLs, and raw documents into a Mendable project, and poll ingestion task status. Returns a task_id used to track indexing progress.

- **Human URL:** [https://docs.mendable.ai/mendable-api/ingestion](https://docs.mendable.ai/mendable-api/ingestion)
- **Base URL:** `https://api.mendable.ai/v1`

#### Tags

- Data Ingestion
- Sources
- Indexing

#### Properties

- [Documentation](https://docs.mendable.ai/mendable-api/ingestion)
- [API Reference](https://docs.mendable.ai/mendable-api/overview)
- [OpenAPI](openapi/mendable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mendable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Mendable Ratings API

Submit positive or negative ratings on individual answer messages via rateMessage to feed answer-quality analytics and improvement loops.

- **Human URL:** [https://docs.mendable.ai/mendable-api/rating](https://docs.mendable.ai/mendable-api/rating)
- **Base URL:** `https://api.mendable.ai/v1`

#### Tags

- Ratings
- Feedback

#### Properties

- [Documentation](https://docs.mendable.ai/mendable-api/rating)
- [API Reference](https://docs.mendable.ai/mendable-api/overview)
- [OpenAPI](openapi/mendable-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/mendable.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/mendable.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/mendableai)
- [LinkedIn](https://www.linkedin.com/company/mendable)
- [Website](https://www.mendable.ai)
- [Documentation](https://docs.mendable.ai)
- [Plans](plans/mendable-plans-pricing.yml)
- [Rate Limits](rate-limits/mendable-rate-limits.yml)
- [Fin Ops](finops/mendable-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
