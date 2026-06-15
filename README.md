# TrueFoundry (truefoundry)

TrueFoundry is a Kubernetes-native enterprise AI platform for deploying and managing agentic AI workloads. It provides an AI Gateway, MCP Gateway, model serving, fine-tuning, and a full MLOps platform that works across on-premises, VPC, hybrid, or public cloud environments.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- AI Platform
- Enterprise AI
- Kubernetes
- LLM Gateway
- MLOps

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### TrueFoundry AI Gateway API

The TrueFoundry AI Gateway API is a proxy layer that sits between applications and LLM providers, enabling unified access to 1000+ language models through a single OpenAI-compatible endpoint. It supports chat completions, embeddings, image generation, audio processing, batch operations, file management, content moderation, and model management with centralized authentication, rate limiting, budget controls, and observability.

- **Human URL:** [https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway](https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway)
- **Base URL:** `https://gateway.truefoundry.ai/api/llm`

#### Tags

- AI Gateway
- Chat Completions
- Embeddings
- LLM

#### Properties

- [Documentation](https://www.truefoundry.com/docs/ai-gateway/intro-to-llm-gateway)
- [Getting Started](https://www.truefoundry.com/docs/ai-gateway/quick-start)
- [Authentication](https://www.truefoundry.com/docs/ai-gateway/authentication)
- [Reference](https://www.truefoundry.com/docs/api-reference)
- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/openapi/truefoundry-ai-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Spectral Rules](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/rules/truefoundry-rules.yml)
- [JSON Schema](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/json-schema/truefoundry-chat-completion-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N L D Context](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/json-ld/truefoundry-context.jsonld)
- [Vocabulary](https://raw.githubusercontent.com/api-evangelist/truefoundry/refs/heads/main/vocabulary/truefoundry-vocabulary.yml)
- [Postman Collection](collections/truefoundry-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truefoundry-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TrueFoundry MCP Gateway API

The TrueFoundry MCP (Model Context Protocol) Gateway provides a centralized registry and proxy for managing MCP servers accessible to AI agents. It handles authentication, access control, schema validation, and tool orchestration across multiple MCP servers, supporting header auth, OAuth2, and token passthrough authentication modes.

- **Human URL:** [https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started](https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started)
- **Base URL:** `https://gateway.truefoundry.ai`

#### Tags

- Agent Tools
- AI Agents
- MCP
- Tool Registry

#### Properties

- [Documentation](https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-server-getting-started)
- [Authentication](https://www.truefoundry.com/docs/ai-gateway/mcp/mcp-gateway-auth-security)
- [Postman Collection](collections/truefoundry-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truefoundry-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TrueFoundry Platform API

The TrueFoundry Platform API provides programmatic access to the TrueFoundry MLOps platform for managing applications, deployments, users, and infrastructure resources. It enables automation of service deployments, training jobs, model registry operations, and workflow orchestration across Kubernetes-based compute environments.

- **Human URL:** [https://www.truefoundry.com/docs](https://www.truefoundry.com/docs)
- **Base URL:** `https://app.truefoundry.com/api`

#### Tags

- Deployments
- Management
- MLOps
- Platform

#### Properties

- [Documentation](https://www.truefoundry.com/docs)
- [Client  Libraries](https://github.com/truefoundry/truefoundry-python-sdk)
- [Postman Collection](collections/truefoundry-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truefoundry-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TrueFoundry Model Serving API

TrueFoundry's Model Serving capability enables deployment and management of LLM and embedding models using backends like vLLM and Triton on Kubernetes infrastructure. It provides APIs for deploying models from a community registry of 1000+ configurations, managing inference endpoints, and controlling autoscaling behavior including scale-to-zero.

- **Human URL:** [https://www.truefoundry.com/docs/introduction-to-a-service](https://www.truefoundry.com/docs/introduction-to-a-service)
- **Base URL:** `https://app.truefoundry.com`

#### Tags

- Kubernetes
- LLM Inference
- MLOps
- Model Serving

#### Properties

- [Documentation](https://www.truefoundry.com/docs/introduction-to-a-service)
- [Postman Collection](collections/truefoundry-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truefoundry-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### TrueFoundry Model Registry API

The TrueFoundry Model Registry provides a versioned repository for storing and managing machine learning models backed by cloud storage such as S3, GCS, Azure Blob, or Minio. It supports programmatic model logging via the truefoundry.ml Python client, multi-framework model formats, and automatic versioning with metadata management.

- **Human URL:** [https://www.truefoundry.com/docs/model-registry](https://www.truefoundry.com/docs/model-registry)
- **Base URL:** `https://app.truefoundry.com`

#### Tags

- Machine Learning
- MLOps
- Model Registry
- Versioning

#### Properties

- [Documentation](https://www.truefoundry.com/docs/model-registry)
- [Postman Collection](collections/truefoundry-ai-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/truefoundry-ai-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/truefoundry)
- [Website](https://www.truefoundry.com/)
- [Documentation](https://www.truefoundry.com/docs)
- [Getting Started](https://www.truefoundry.com/docs/ai-gateway/quick-start)
- [Authentication](https://www.truefoundry.com/docs/ai-gateway/authentication)
- [Pricing](https://www.truefoundry.com/pricing)
- [Blog](https://www.truefoundry.com/blog)
- [Changelog](https://www.truefoundry.com/docs/changelog)
- [GitHub Organization](https://github.com/truefoundry)
- [GitHub Repository](https://github.com/truefoundry/truefoundry-python-sdk)
- [S D Ks](https://github.com/truefoundry/truefoundry-python-sdk)
- [Sign Up](https://app.truefoundry.com/signup)
- [M C P Server](https://github.com/truefoundry/mcp-servers)
- [Agent Skill](https://github.com/truefoundry/skills)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
