# Parasail (parasail)

Parasail is an AI Supercloud — a pay-per-token GPU inference platform aimed at AI
startups and developers. Parasail orchestrates rented GPU capacity across 40+
data centers in 15+ countries to serve open-weight LLMs, vision/multimodal models,
embedding models, and TTS/STT models on a serverless, dedicated, or batch basis.
The platform exposes OpenAI-compatible /v1 endpoints for chat completions,
completions, embeddings, batch, and models, plus a control-plane /api/v1 for
managing dedicated GPU deployments of any Hugging Face or custom model. Parasail
serves 500B+ tokens per day and is positioned as up to 30x cheaper than legacy
cloud providers, with no quotas, no rate-limit penalties, and no long-term
contracts. Co-founded by Mike Henry (ex-Mythic) and Tim Harris (ex-Swift
Navigation); raised a $32M Series A in April 2026 (Touring Capital and Kindred
Ventures) bringing total funding to $42M.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/parasail-ai/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/parasail-ai/refs/heads/main/apis.yml)

## Scope

- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

- AI
- Artificial Intelligence
- GPU
- Inference
- Large Language Models
- Open Source Models
- Hugging Face
- Batch
- Embeddings
- Tokenmaxxing
- Supercloud

## Timestamps

- **Created:** 2026-05-25T00:00:00.000Z
- **Modified:** 2026-05-25

## APIs

### Parasail Inference API

OpenAI-compatible real-time and streaming inference API exposing serverless
access to popular open-weight LLMs, embedding models, and the model catalog.
Endpoints: /v1/chat/completions, /v1/completions, /v1/embeddings, /v1/models.
Bearer-token authentication; pay-per-token billing; supports streaming, tool
use, and structured outputs. Compatible with the OpenAI Python and TypeScript
clients by overriding base_url.

- **Human URL:** [https://docs.parasail.io/parasail-docs/](https://docs.parasail.io/parasail-docs/)
- **Base URL:** `https://api.parasail.io/v1`

#### Tags

- AI
- Artificial Intelligence
- Inference
- Chat
- Embeddings
- Models

#### Properties

- [Documentation](https://docs.parasail.io/parasail-docs/)
- [OpenAPI](openapi/parasail-inference-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parasail-inference-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parasail-inference-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/parasail-chat-completion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/parasail-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)

### Parasail Batch API

OpenAI-compatible Batch API for asynchronous inference workloads at 50% off
serverless pricing (with an additional 30% off cached tokens). Supports
/v1/chat/completions and /v1/embeddings in the OpenAI Batch file format
(JSONL) with a 24-hour completion window. Includes a Files surface for
uploading and downloading input/output/error JSONL files. Ideal for offline
enrichment, dataset processing, and large-scale tokenmaxxing.

- **Human URL:** [https://docs.parasail.io/parasail-docs/](https://docs.parasail.io/parasail-docs/)
- **Base URL:** `https://api.parasail.io/v1`

#### Tags

- AI
- Artificial Intelligence
- Batch
- Files

#### Properties

- [Documentation](https://docs.parasail.io/parasail-docs/)
- [OpenAPI](openapi/parasail-batch-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parasail-batch-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parasail-batch-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/parasail-batch-schema.json) — [JSON Schema](https://json-schema.org/specification)

### Parasail Dedicated Deployments API

Control-plane API for managing Parasail Dedicated and Dedicated Serverless
deployments. Provision reserved GPU capacity (H100, A100, H200, etc.) running
any Hugging Face or custom model, then list, retrieve, update, pause, resume,
and delete deployments. Read-only API keys can list and retrieve but cannot
mutate. Endpoint: /api/v1/dedicated/deployments.

- **Human URL:** [https://docs.parasail.io/parasail-docs/](https://docs.parasail.io/parasail-docs/)
- **Base URL:** `https://api.parasail.io/api/v1`

#### Tags

- AI
- Artificial Intelligence
- GPU
- Deployments
- Dedicated

#### Properties

- [Documentation](https://docs.parasail.io/parasail-docs/)
- [OpenAPI](openapi/parasail-dedicated-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/parasail-dedicated-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/parasail-dedicated-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/parasail-deployment-schema.json) — [JSON Schema](https://json-schema.org/specification)

## Common Properties

- [Portal](https://parasail.io)
- [Documentation](https://docs.parasail.io/parasail-docs/)
- [Sign Up](https://www.saas.parasail.io/)
- [Pricing](https://www.saas.parasail.io/pricing)
- [Blog](https://parasail.io/blogs)
- [About Us](https://parasail.io/about-us)
- [Careers](https://job-boards.greenhouse.io/parasail)
- [Privacy Policy](https://parasail.io/legal/privacy-policy)
- [Terms of Service](https://parasail.io/legal/terms-of-service)
- [GitHub Organization](https://github.com/parasail-ai)
- [Forum](https://discord.gg/parasail)
- [LinkedIn](https://www.linkedin.com/company/parasail-ai)
- [X (Twitter)](https://x.com/parasail_io)
- [SDK](https://github.com/parasail-ai/openai-batch)
- [Code Examples](https://github.com/parasail-ai/cookbook)
- [Tool](https://github.com/parasail-ai/kvcached)
- [Tool](https://github.com/parasail-ai/vllm-public)
- [Tool](https://github.com/parasail-ai/curator)
- [Tool](https://github.com/parasail-ai/simple-evals)
- [Tool](https://github.com/parasail-ai/VLMEvalKit)
- [Plans](plans/parasail-plans-pricing.yml)
- [Rate Limits](rate-limits/parasail-rate-limits.yml)
- [Fin Ops](finops/parasail-finops.yml)
- [Features](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
