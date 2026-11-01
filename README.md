# Warp

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

Warp is an open-source, Rust-based, GPU-accelerated agentic development environment built on top of a modern terminal. It combines a high-performance terminal with AI-powered cloud agents (the Oz platform) to help developers build, test, deploy, and debug code autonomously. The Oz API lets external systems trigger and monitor cloud agent runs over HTTP, making it suitable for CI pipelines, backend services, and internal tooling. Warp also provides Warp Drive for team collaboration and workflow sharing, and supports MCP servers for extending agent capabilities with custom tools and data sources.

**Areas:** Developer Tools · Terminal · AI Agents · Cloud Agents · Agentic Development

## Warp on APIs.io

Everything profiled for Warp is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/warp/](https://apis.io/providers/warp/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Warp Enterprise Analytics API](https://apis.io/apis/warp/enterprise-analytics-api/) — The Enterprise Analytics API provides team usage metrics and administrative insights for Enterprise plan customers. It enables organizations to track agent…
- [Warp Oz CLI](https://apis.io/apis/warp/oz-cli/) — The Oz CLI is a command-line interface for interacting with the Warp Oz agent platform. It allows developers to trigger cloud agent runs, manage…
- [Warp Agent API](https://apis.io/apis/warp/warp-agent-api/) — Operations for running and managing cloud agents
- [Warp Harness Support API](https://apis.io/apis/warp/warp-harness-support-api/) — The harness-support API from Warp — 1 operation(s) for harness-support.
- [Warp Schedules API](https://apis.io/apis/warp/warp-schedules-api/) — Operations for creating and managing scheduled agents

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Warp Agentic Access](https://apis.io/agentic-access/warp/warp-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [RunItem](https://apis.io/schemas/warp/warp-run/)
- [RunAgentRequest](https://apis.io/schemas/warp/warp-run-agent-request/)
- [ScheduledAgentItem](https://apis.io/schemas/warp/warp-scheduled-agent/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Warp Context](https://apis.io/jsonld/warp/warp-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Warp Oz Agent API Vocabulary](https://apis.io/vocabularies/warp/warp-vocabulary/)

#### Examples (3)

Example requests and responses.

- [Warp Create Schedule Example](https://apis.io/examples/warp/warp-create-schedule-example/)
- [Warp List Runs Example](https://apis.io/examples/warp/warp-list-runs-example/)
- [Warp Run Agent Example](https://apis.io/examples/warp/warp-run-agent-example/)

#### Collections (6)

Postman and Open Collection request collections.

- [Oz agent API](https://apis.io/collections/warp/open-warp-agent-api/)
- [Oz agent harness-support API](https://apis.io/collections/warp/open-warp-harness-support-api/)
- [Oz agent schedules API](https://apis.io/collections/warp/open-warp-schedules-api/)
- [Oz agent API](https://apis.io/collections/warp/postman-warp-agent-api/)
- [Oz agent harness-support API](https://apis.io/collections/warp/postman-warp-harness-support-api/)
- [Oz agent schedules API](https://apis.io/collections/warp/postman-warp-schedules-api/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [Warp — jsonschema rules](https://apis.io/rules/warp/warp-jsonschema-spectral-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Warp Authentication](https://apis.io/security/warp/warp-authentication/)
- [Warp Domain Security](https://apis.io/security/warp/warp-domain-security/)
- [Warp Trust Center](https://apis.io/security/warp/warp-trust-center/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Warp Plans Pricing](https://apis.io/plans/warp/warp-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Warp Rate Limits](https://apis.io/rate-limits/warp/warp-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Warp Finops](https://apis.io/finops/warp/warp-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.warp.dev/)
- [Documentation](https://docs.warp.dev/)
- [Pricing](https://www.warp.dev/pricing)
- [Changelog](https://docs.warp.dev/changelog/)
- [Blog](https://www.warp.dev/blog)
- [GitHub](https://github.com/warpdotdev)
- [Status](https://status.warp.dev/)

## API Evangelist rating

**Kin Score 43.8** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 57.1 |
| Contract quality | 67.7 |
| Contract governance | 23.5 |
| Operational transparency | 42.1 |
| Developer ergonomics | 36.9 |
| Access clarity | 26.3 |

**Agent readiness 29.4** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | documented (partial credit) |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | partial |
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
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 21.6** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/warp/](https://apis.io/providers/warp/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Warp: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/warp/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
