# Fern

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

Fern is a developer-tools platform that turns a single API specification into idiomatic client SDKs, beautiful API documentation, and MCP servers. Given OpenAPI, AsyncAPI, gRPC/Protobuf, or Fern's own Fern Definition as input, Fern generates type-safe SDKs in TypeScript, Python, Go, Java, C#, PHP, Ruby, Swift, and Rust, publishes them to registries like npm, PyPI, and Maven, and builds a hosted docs site with an interactive API reference, API playground, and an AI-powered "Ask Fern" search. The primary interface is the open-source `fern` CLI (Apache-2.0, github.com/fern-api/fern) driving a hosted platform - the fern-api catalog documents Fern's SDK-generation, documentation-generation, and Fern Definition capability surfaces as capability areas, plus the one hosted public REST API Fern exposes to customers, the Ask Fern API. Fern is open-core: the CLI and generators are open source, and Docs and SDKs are sold on Hobby (free), Team, and Enterprise plans.

**Areas:** API Lifecycle · SDK Generation · Client Library · API Documentation · Developer Tools · OpenAPI · CLI · Open Source · Developer Experience · Documentation

## Fern on APIs.io

Everything profiled for Fern is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/fern-api/](https://apis.io/providers/fern-api/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Fern SDK Generation](https://apis.io/apis/fern-api/fern-api-sdk-generation/) — Capability area (CLI/platform, not a hosted REST API) that generates idiomatic, type-safe client SDKs in TypeScript, Python, Go, Java, C#, PHP, Ruby, Swift,…
- [Fern API Documentation](https://apis.io/apis/fern-api/fern-api-documentation/) — Capability area (CLI/platform) that builds a hosted documentation website with a generated API reference, interactive API playground, changelogs,…
- [Fern Definition and CLI](https://apis.io/apis/fern-api/fern-api-definition-cli/) — Capability area covering Fern's open-source (Apache-2.0) command-line interface and the proprietary Fern Definition API-description format. Core commands…
- [Fern Ask API](https://apis.io/apis/fern-api/fern-api-ask-api/) — Query indexed documentation for AI-generated, grounded answers.
- [Fern Website Sources API](https://apis.io/apis/fern-api/fern-api-website-sources-api/) — Index documentation websites and check indexing job status.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [Moved to /providers/fern-api/](https://apis.io/servers/fern-api/fern-api/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Fern Api Agentic Access](https://apis.io/agentic-access/fern-api/fern-api-agentic-access/)

#### JSON Schema (1)

The data models the API reads and writes.

- [WebsiteStatus](https://apis.io/schemas/fern-api/fern-api-website-status/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Fern Api Context](https://apis.io/jsonld/fern-api/fern-api-context/)

#### Collections (3)

Postman and Open Collection request collections.

- [Fern Ask Fern API](https://apis.io/collections/fern-api/open-fern-api/)
- [Fern Fern Ask API](https://apis.io/collections/fern-api/open-fern-api-ask-api/)
- [Fern Fern Ask Website Sources API](https://apis.io/collections/fern-api/open-fern-api-website-sources-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Fern API Rules](https://apis.io/rules/fern-api/fern-api-rules/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Fern Api Authentication](https://apis.io/security/fern-api/fern-api-authentication/)
- [Fern Api Domain Security](https://apis.io/security/fern-api/fern-api-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Fern Api Plans Pricing](https://apis.io/plans/fern-api/fern-api-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Fern Api Rate Limits](https://apis.io/rate-limits/fern-api/fern-api-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Fern Api Finops](https://apis.io/finops/fern-api/fern-api-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://buildwithfern.com)
- [Documentation](https://buildwithfern.com/learn/home)
- [API reference](https://buildwithfern.com/docs)
- [Pricing](https://buildwithfern.com/pricing)
- [Sign up](https://dashboard.buildwithfern.com/sign-up)
- [Support](https://buildwithfern.com/support)
- [Blog](https://buildwithfern.com/blog)
- [Trust centre](https://buildwithfern.com/trust)
- [GitHub](https://github.com/fern-api)
- [Status](https://status.buildwithfern.com/)

## API Evangelist rating

**Kin Score 34.2** — thin · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 60.0 |
| Contract quality | 7.1 |
| Contract governance | 35.6 |
| Operational transparency | 26.3 |
| Developer ergonomics | 55.4 |
| Access clarity | 39.5 |

**Agent readiness 36.0** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Education & Research

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/fern-api/](https://apis.io/providers/fern-api/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Fern: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/fern-api/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
