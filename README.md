# Parasail

Parasail is an AI Supercloud — a pay-per-token GPU inference platform aimed at AI startups and developers. Parasail orchestrates rented GPU capacity across 40+ data centers in 15+ countries to serve open-weight LLMs, vision/multimodal models, embedding models, and TTS/STT models on a serverless, dedicated, or batch basis.

The platform exposes OpenAI-compatible `/v1` endpoints for chat completions, completions, embeddings, batch, and models, plus a control-plane `/api/v1` for managing dedicated GPU deployments of any Hugging Face or custom model. Parasail serves 500B+ tokens per day and is positioned as up to 30x cheaper than legacy cloud providers, with no quotas, no rate-limit penalties, and no long-term contracts.

Co-founded by Mike Henry (ex-Mythic) and Tim Harris (ex-Swift Navigation); raised a $32M Series A in April 2026 (Touring Capital and Kindred Ventures) bringing total funding to $42M.

## APIs

| API | Base URL | Description |
| --- | --- | --- |
| [Parasail Inference API](openapi/parasail-inference-api-openapi.yml) | `https://api.parasail.io/v1` | OpenAI-compatible chat completions, completions, embeddings, and models. |
| [Parasail Batch API](openapi/parasail-batch-api-openapi.yml) | `https://api.parasail.io/v1` | Asynchronous batch inference at 50% off serverless (plus 30% off cached tokens). |
| [Parasail Dedicated Deployments API](openapi/parasail-dedicated-api-openapi.yml) | `https://api.parasail.io/api/v1` | Control-plane for reserved GPU deployments of any Hugging Face model. |

## Commercial surfaces

- **Serverless** — pay-per-token, OpenAI-compatible endpoints, 500 RPM standard.
- **Dedicated Serverless / Pro** — isolated capacity behind the same endpoints, 1,000 / 4,000 RPM.
- **Dedicated** — reserved GPU-hour billing on H100 / A100 / H200, bring-your-own model.
- **Batch** — JSONL batch jobs at 50% off serverless with a 24-hour completion window.

See [plans/parasail-plans-pricing.yml](plans/parasail-plans-pricing.yml), [rate-limits/parasail-rate-limits.yml](rate-limits/parasail-rate-limits.yml), and [finops/parasail-finops.yml](finops/parasail-finops.yml).

## Artifacts

- OpenAPI: [openapi/](openapi/)
- Naftiko capabilities: [capabilities/](capabilities/)
- JSON Schema: [json-schema/](json-schema/)
- JSON-LD context: [json-ld/parasail-context.jsonld](json-ld/parasail-context.jsonld)
- Examples: [examples/](examples/)
- Spectral rules: [rules/parasail-rules.yml](rules/parasail-rules.yml)
- Vocabulary: [vocabulary/parasail-ai-vocabulary.yml](vocabulary/parasail-ai-vocabulary.yml)

## Links

- Homepage: <https://parasail.io>
- Docs: <https://docs.parasail.io/parasail-docs/>
- Pricing: <https://www.saas.parasail.io/pricing>
- Sign up: <https://www.saas.parasail.io/>
- Blog: <https://parasail.io/blogs>
- GitHub: <https://github.com/parasail-ai>

## Maintainer

API Evangelist — [apievangelist.com](https://apievangelist.com)
