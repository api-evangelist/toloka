# Toloka (toloka)

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
