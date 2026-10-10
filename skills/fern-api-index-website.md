---
name: fern-api-index-website
description: Index a documentation website and then check its indexing status.
api: openapi/fern-api-website-sources-api-openapi.yml
operations:
- indexWebsite
- getWebsiteStatus
generated: '2026-10-04'
method: generated
generator: extract-docs-artifacts.py skills (local)
source: openapi/fern-api-website-sources-api-openapi.yml ; every operationId checked against the contract
---

# fern-api-index-website

Index a documentation website and then check its indexing status.

## Steps

1. 1. Call `indexWebsite` with the path parameter `domain` and any required request body fields.
2. 2. Call `getWebsiteStatus` with the same `domain` path parameter to retrieve the indexing status.

## Rules

- Auth: Include a Bearer token in the `Authorization` header as defined by the `bearerAuth` scheme.
- Rate limiting: No rate limit is documented; on exhaustion the API returns no specific HTTP status.
