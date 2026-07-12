# Fern (fern-api)

Fern is a developer-tools platform that turns a single API specification into idiomatic client SDKs, beautiful API documentation, and MCP servers. Given OpenAPI, AsyncAPI, gRPC/Protobuf, or Fern's own Fern Definition as input, Fern generates type-safe SDKs in TypeScript, Python, Go, Java, C#, PHP, Ruby, Swift, and Rust, publishes them to registries like npm, PyPI, and Maven, and builds a hosted docs site with an interactive API reference, an API playground, and AI-powered "Ask Fern" search.

**Access model — read this first.** Fern is primarily a **CLI + platform**, not a traditional hosted REST API. The `fern` CLI is open source (Apache-2.0, [github.com/fern-api/fern](https://github.com/fern-api/fern)) and drives a hosted dashboard for publishing. Fern exposes **one documented hosted public REST API** to customers: the **Ask Fern API** (`https://fai.buildwithfern.com`), used to index a documentation website, poll indexing status, and query indexed content for AI-grounded answers. It is authenticated with a Bearer token from `fern token` and is available on the Team and Enterprise plans. Everything else — SDK generation, docs generation, the Fern Definition format — is a **capability area** driven through the CLI/platform and is documented here with `endpointsModeled` rather than as a live REST surface. Fern is **open-core**: the CLI and generators are free and open source; hosted Docs and SDKs are sold on Hobby (free), Team, and Enterprise plans.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fern-api/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fern-api/refs/heads/main/apis.yml)

## Tags

- API Lifecycle
- SDK Generation
- Client Library
- API Documentation
- Developer Tools
- OpenAPI
- CLI
- Open Source
- Developer Experience

## Timestamps

- **Created:** 2026-07-11
- **Modified:** 2026-07-11

## APIs (capability areas)

### Fern SDK Generation

Capability area (CLI/platform, not a hosted REST API) that generates idiomatic, type-safe client SDKs in TypeScript, Python, Go, Java, C#, PHP, Ruby, Swift, and Rust from OpenAPI, AsyncAPI, gRPC, or Fern Definition input. Driven by `fern generate`; SDKs publish to GitHub and registries (npm, PyPI, Maven). Endpoints are modeled from the CLI surface.

- **Human URL:** [https://buildwithfern.com/learn/sdks/overview](https://buildwithfern.com/learn/sdks/overview)

#### Tags

- SDK Generation
- Client Library
- Developer Tools
- API Lifecycle

#### Properties

- [Documentation](https://buildwithfern.com/learn/sdks/overview)
- [API Reference](https://buildwithfern.com/learn/cli-api-reference/cli-reference/commands)
- [Source Code](https://github.com/fern-api/fern)

### Fern API Documentation

Capability area (CLI/platform) that builds a hosted documentation website with a generated API reference, interactive API playground, changelogs, versioning, keyword search, and docs-as-code (Markdown + git) authoring. Driven by `fern generate --docs` and `fern docs dev`. Endpoints are modeled from the CLI and platform surface.

- **Human URL:** [https://buildwithfern.com/learn/docs/getting-started/overview](https://buildwithfern.com/learn/docs/getting-started/overview)

#### Tags

- API Documentation
- Developer Portal
- Docs as Code
- Developer Experience

#### Properties

- [Documentation](https://buildwithfern.com/learn/docs/getting-started/overview)
- [API Reference](https://buildwithfern.com/learn/docs/api-references/generate-api-ref)
- [Source Code](https://github.com/fern-api/fern)

### Fern Definition and CLI

Capability area covering Fern's open-source (Apache-2.0) command-line interface and the proprietary Fern Definition API-description format. Core commands include `fern init`, `fern check`, `fern generate`, `fern login`, `fern token`, `fern export`, and `fern docs dev`. Endpoints are modeled from the CLI surface.

- **Human URL:** [https://buildwithfern.com/learn/cli-api-reference/cli-reference/commands](https://buildwithfern.com/learn/cli-api-reference/cli-reference/commands)

#### Tags

- CLI
- API Design
- API Lifecycle
- Developer Tools

#### Properties

- [Documentation](https://buildwithfern.com/learn/cli-api-reference/cli-reference/commands)
- [API Reference](https://buildwithfern.com/learn/api-definitions/openapi/authentication)
- [Source Code](https://github.com/fern-api/fern)

### Ask Fern API

Fern's hosted public REST API for the AI-powered "Ask Fern" documentation search. Index a documentation website, poll indexing job status, and query the indexed content for grounded answers to build your own support integrations. Authenticated with a Bearer token from `fern token`; available on Team and Enterprise plans. The website index/status endpoints are grounded in the published reference; the `/ask` query shape is modeled.

- **Human URL:** [https://buildwithfern.com/learn/docs/ai-features/ask-fern/api-reference/overview](https://buildwithfern.com/learn/docs/ai-features/ask-fern/api-reference/overview)
- **Base URL:** `https://fai.buildwithfern.com`

#### Tags

- AI
- Search
- REST API
- Developer Tools

#### Properties

- [Documentation](https://buildwithfern.com/learn/docs/ai-features/ask-fern/api-reference/overview)
- [API Reference](https://buildwithfern.com/learn/docs/ai-features/ask-fern/api-reference/website/get-website-status)
- [OpenAPI](openapi/fern-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fern-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fern-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Authentication](authentication/fern-api-authentication.yml)
- [GitHub Organization](https://github.com/fern-api)
- [LinkedIn](https://www.linkedin.com/company/buildwithfern)
- [Website](https://buildwithfern.com)
- [Documentation](https://buildwithfern.com/learn/home)
- [Plans](plans/fern-api-plans-pricing.yml)
- [Rate Limits](rate-limits/fern-api-rate-limits.yml)
- [Fin Ops](finops/fern-api-finops.yml)
- [Blog](https://buildwithfern.com/blog)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
