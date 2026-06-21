# Toloka (toloka)

Toloka is a data-labeling and human-data platform that powers human-in-the-loop pipelines for training and evaluating AI. The Toloka API lets requesters programmatically create projects, configure pools of crowdsourced tasks, upload tasks and task suites, collect and review Toloker responses, and track asynchronous operations, with a companion toloka-kit Python SDK.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/toloka/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/toloka/refs/heads/main/apis.yml)

## Tags

- Data Labeling
- Crowdsourcing
- Human-in-the-Loop
- Training Data
- AI

## Timestamps

- **Created:** 2026-06-21
- **Modified:** 2026-06-21

## APIs

### Toloka Projects API

Create, edit, list, and archive projects that define the task input/output schema, Toloker interface, and instructions shared across pools.

- **Human URL:** [https://toloka.ai/docs/api/api-reference/](https://toloka.ai/docs/api/api-reference/)
- **Base URL:** `https://api.toloka.ai/api/v1`

#### Tags

- Projects
- Task Specification
- Configuration

#### Properties

- [Documentation](https://toloka.ai/docs/api/)
- [API Reference](https://toloka.ai/docs/api/api-reference/)
- [OpenAPI](openapi/toloka-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toloka.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/Toloka/toloka-kit)

### Toloka Pools API

Create and configure pools and training pools, set rewards, filters, and quality control, then open, close, and archive them to control when Tolokers see tasks.

- **Human URL:** [https://toloka.ai/docs/api/api-reference/](https://toloka.ai/docs/api/api-reference/)
- **Base URL:** `https://api.toloka.ai/api/v1`

#### Tags

- Pools
- Training
- Quality Control

#### Properties

- [Documentation](https://toloka.ai/docs/api/)
- [API Reference](https://toloka.ai/docs/api/api-reference/)
- [OpenAPI](openapi/toloka-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toloka.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/Toloka/toloka-kit)

### Toloka Tasks & Task Suites API

Upload individual tasks or batches and group them into task suites, with overlap settings, known solutions for quality control, and asynchronous batch creation for large volumes.

- **Human URL:** [https://toloka.ai/docs/api/api-reference/](https://toloka.ai/docs/api/api-reference/)
- **Base URL:** `https://api.toloka.ai/api/v1`

#### Tags

- Tasks
- Task Suites
- Batch Upload

#### Properties

- [Documentation](https://toloka.ai/docs/api/concepts/upload-tasks)
- [API Reference](https://toloka.ai/docs/api/api-reference/)
- [OpenAPI](openapi/toloka-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toloka.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/Toloka/toloka-kit)

### Toloka Assignments API

Retrieve Toloker responses filtered by pool, status, and user, then accept or reject completed assignments and issue bonuses, restrictions, and skills off the results.

- **Human URL:** [https://toloka.ai/docs/api/api-reference/](https://toloka.ai/docs/api/api-reference/)
- **Base URL:** `https://api.toloka.ai/api/v1`

#### Tags

- Assignments
- Responses
- Review

#### Properties

- [Documentation](https://toloka.ai/docs/api/concepts/get-response)
- [API Reference](https://toloka.ai/docs/api/api-reference/)
- [OpenAPI](openapi/toloka-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toloka.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/Toloka/toloka-kit)

### Toloka Operations & Webhooks API

Poll the status of asynchronous operations returned by batch and pool actions, and manage webhook subscriptions that push pool and assignment events to your endpoint with HMAC SHA256 signed notifications.

- **Human URL:** [https://toloka.ai/docs/api/api-reference/](https://toloka.ai/docs/api/api-reference/)
- **Base URL:** `https://api.toloka.ai/api/v1`

#### Tags

- Operations
- Webhooks
- Async

#### Properties

- [Documentation](https://toloka.ai/docs/api/concepts/using-webhook-subscriptions)
- [API Reference](https://toloka.ai/docs/api/api-reference/)
- [OpenAPI](openapi/toloka-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/toloka.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [GitHub](https://github.com/Toloka/toloka-kit)

## Common Properties

- [GitHub Organization](https://github.com/Toloka)
- [LinkedIn](https://www.linkedin.com/company/toloka)
- [Website](https://toloka.ai)
- [Documentation](https://toloka.ai/docs/api/)
- [Plans](plans/toloka-plans-pricing.yml)
- [Rate Limits](rate-limits/toloka-rate-limits.yml)
- [Fin Ops](finops/toloka-finops.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
