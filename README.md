# Parasail

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

**Areas:** Artificial Intelligence · GPU · Inference · LLM · Open Source Models · Hugging Face · Batch · Embeddings · Tokenmaxxing · Supercloud

## Parasail on APIs.io

Everything profiled for Parasail is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/parasail-ai/](https://apis.io/providers/parasail-ai/)** — or go straight to one of the APIs or properties below.

### APIs (7)

- [Parasail Batch API](https://apis.io/apis/parasail-ai/parasail-ai-batch-api/) — Create, list, retrieve, and cancel batch inference jobs.
- [Parasail Completions API](https://apis.io/apis/parasail-ai/parasail-ai-completions-api/) — Legacy text completions for prompt-only LLM workloads.
- [Parasail Deployments API](https://apis.io/apis/parasail-ai/parasail-ai-deployments-api/) — Manage dedicated GPU deployments for custom and reserved-capacity inference.
- [Parasail Embeddings API](https://apis.io/apis/parasail-ai/parasail-ai-embeddings-api/) — Vector embeddings for RAG, semantic search, and similarity workloads.
- [Parasail Files API](https://apis.io/apis/parasail-ai/parasail-ai-files-api/) — Upload and manage input/output JSONL files used by Batch jobs.
- [Parasail Models API](https://apis.io/apis/parasail-ai/parasail-ai-models-api/) — Discover the models currently exposed on the serverless tier.
- [Parasail Chat Completions API](https://apis.io/apis/parasail-ai/parasail-ai-chat-completions-api/) — Chat completions for conversational LLM workloads.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Parasail Ai Agentic Access](https://apis.io/agentic-access/parasail-ai/parasail-ai-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [Parasail Batch](https://apis.io/schemas/parasail-ai/parasail-batch/)
- [Parasail Chat Completion](https://apis.io/schemas/parasail-ai/parasail-chat-completion/)
- [Parasail Dedicated Deployment](https://apis.io/schemas/parasail-ai/parasail-deployment/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Parasail Context](https://apis.io/jsonld/parasail-ai/parasail-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Parasail Vocabulary](https://apis.io/vocabularies/parasail-ai/parasail-ai-vocabulary/)

#### Examples (4)

Example requests and responses.

- [Parasail Chat Completion Example](https://apis.io/examples/parasail-ai/parasail-chat-completion-example/)
- [Parasail Create Batch Example](https://apis.io/examples/parasail-ai/parasail-create-batch-example/)
- [Parasail Create Deployment Example](https://apis.io/examples/parasail-ai/parasail-create-deployment-example/)
- [Parasail Embedding Example](https://apis.io/examples/parasail-ai/parasail-embedding-example/)

#### Collections (10)

Postman and Open Collection request collections.

- [Parasail Batch API](https://apis.io/collections/parasail-ai/open-parasail-ai-batch-api/)
- [Parasail Batch Chat API](https://apis.io/collections/parasail-ai/open-parasail-ai-chat-api/)
- [Parasail Batch Completions API](https://apis.io/collections/parasail-ai/open-parasail-ai-completions-api/)
- [Parasail Batch Deployments API](https://apis.io/collections/parasail-ai/open-parasail-ai-deployments-api/)
- [Parasail Batch Embeddings API](https://apis.io/collections/parasail-ai/open-parasail-ai-embeddings-api/)
- [Parasail Batch Files API](https://apis.io/collections/parasail-ai/open-parasail-ai-files-api/)
- [Parasail Batch Models API](https://apis.io/collections/parasail-ai/open-parasail-ai-models-api/)
- [Parasail Batch API](https://apis.io/collections/parasail-ai/open-parasail-batch-api/)
- [Parasail Dedicated Deployments API](https://apis.io/collections/parasail-ai/open-parasail-dedicated-api/)
- [Parasail Inference API](https://apis.io/collections/parasail-ai/open-parasail-inference-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [Parasail — jsonschema rules](https://apis.io/rules/parasail-ai/parasail-ai-jsonschema-spectral-rules/)
- [Parasail — parasail rules](https://apis.io/rules/parasail-ai/parasail-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Parasail Ai Authentication](https://apis.io/security/parasail-ai/parasail-ai-authentication/)
- [Parasail Ai Domain Security](https://apis.io/security/parasail-ai/parasail-ai-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Parasail Plans Pricing](https://apis.io/plans/parasail-ai/parasail-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Parasail Rate Limits](https://apis.io/rate-limits/parasail-ai/parasail-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Parasail Finops](https://apis.io/finops/parasail-ai/parasail-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.parasail.io/)
- [Documentation](https://docs.parasail.io/parasail-docs/)
- [Pricing](https://www.saas.parasail.io/pricing)
- [Blog](https://parasail.io/blogs)
- [Terms of service](https://parasail.io/legal/terms-of-service)
- [Privacy policy](https://parasail.io/legal/privacy-policy)
- [GitHub](https://github.com/parasail-ai)

## API Evangelist rating

**Kin Score 43.9** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 71.4 |
| Contract quality | 67.6 |
| Contract governance | 13.6 |
| Operational transparency | 2.6 |
| Developer ergonomics | 45.2 |
| Access clarity | 42.1 |

**Agent readiness 21.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | documented (partial credit) |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |

**Regulatory alignment 22.7** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/parasail-ai/](https://apis.io/providers/parasail-ai/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Parasail: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/parasail-ai/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
