# TrueFoundry

TrueFoundry is a Kubernetes-native enterprise AI platform for deploying and managing agentic AI workloads. It provides an AI Gateway, MCP Gateway, model serving, fine-tuning, and a full MLOps platform that works across on-premises, VPC, hybrid, or public cloud environments.

**URL:** [apis.yml](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml)

## APIs

### TrueFoundry AI Gateway API

OpenAI-compatible proxy layer providing unified access to 1000+ LLMs across 30+ providers through a single endpoint.

- **Base URL:** `https://app.truefoundry.com/api/llm`
- **Authentication:** Bearer token (TrueFoundry API key)
- **Documentation:** [AI Gateway Docs](https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway)

**Endpoints:**
- `POST /chat/completions` — Chat completions (streaming supported)
- `POST /embeddings` — Text embedding generation
- `POST /images/generations` — Image generation
- `POST /audio/speech` — Text-to-speech
- `POST /audio/transcriptions` — Speech-to-text
- `GET/POST /files` — File management
- `POST /batches` — Async batch processing
- `POST /moderations` — Content moderation
- `GET /models` — List available models
- `POST /rerank` — Document reranking

### TrueFoundry MCP Gateway API

Centralized registry and proxy for MCP servers accessible to AI agents.

- **Documentation:** [MCP Gateway Docs](https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started)

### TrueFoundry Platform API

Programmatic access to the MLOps platform for managing deployments, jobs, and infrastructure.

- **Base URL:** `https://app.truefoundry.com/api`
- **SDK:** [truefoundry-python-sdk](https://github.com/truefoundry/truefoundry-python-sdk)

### TrueFoundry Model Registry API

Versioned repository for storing and managing ML models on cloud storage.

- **Documentation:** [Model Registry Docs](https://www.truefoundry.com/docs/model-registry)

## Artifacts

| Type | File |
|---|---|
| OpenAPI Spec (AI Gateway) | [openapi/truefoundry-ai-gateway-openapi.yml](openapi/truefoundry-ai-gateway-openapi.yml) |
| Spectral Rules | [rules/truefoundry-rules.yml](rules/truefoundry-rules.yml) |
| Naftiko Capabilities | [capabilities/llm-operations.yaml](capabilities/llm-operations.yaml) |
| Shared Capability | [capabilities/shared/ai-gateway.yaml](capabilities/shared/ai-gateway.yaml) |
| Chat Completion Schema | [json-schema/truefoundry-chat-completion-schema.json](json-schema/truefoundry-chat-completion-schema.json) |
| Chat Completion Structure | [json-structure/truefoundry-chat-completion-structure.json](json-structure/truefoundry-chat-completion-structure.json) |
| JSON-LD Context | [json-ld/truefoundry-context.jsonld](json-ld/truefoundry-context.jsonld) |
| Examples | [examples/](examples/) |
| Vocabulary | [vocabulary/truefoundry-vocabulary.yml](vocabulary/truefoundry-vocabulary.yml) |

## Capabilities

### LLM Operations (`capabilities/llm-operations.yaml`)

Workflow capability for AI/LLM operations via TrueFoundry's AI Gateway. Combines chat completions, embeddings, image generation, content moderation, and document reranking.

- **REST port:** 8080
- **MCP port:** 9090
- **Tools:** 8 tools covering chat, embeddings, images, moderation, reranking, models, batches, and files

## Tags

- AI Platform
- Enterprise AI
- Kubernetes
- LLM Gateway
- MLOps

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-03

## Maintainers

**FN:** Kin Lane  
**Email:** kin@apievangelist.com
