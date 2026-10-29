# Elk

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

Elk is a nimble, MIT-licensed Mastodon web client maintained by Anthony Fu, Daniel Roe, Kevin Deng and Patak. It runs as a Nuxt 4 progressive web app at elk.zone and connects to any Mastodon-compatible instance the user chooses, speaking the Mastodon Client API through Masto.js with WebSocket streaming and Web Push notifications. Elk sells no API product and issues no credential of its own: its small server surface at elk.zone/api exists to list sign-in instances and broker the OAuth 2.0 handshake with the user's own server, and every timeline, post and notification call goes to that instance directly.

**Areas:** Fediverse · Mastodon · Open Source · Social Network · Social Media · Web-Client · Progressive Web App · Authentication

## Elk on APIs.io

Everything profiled for Elk is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/elk/](https://apis.io/providers/elk/)** — or go straight to one of the APIs or properties below.

### APIs (1)

- [Elk Client API](https://apis.io/apis/elk/elk-client-api/) — Elk's own server surface, served by its Nuxt runtime at https://elk.zone/api. Four endpoints: list the Mastodon-compatible instances offered in the sign-in…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [elk-mcp.yml](https://apis.io/servers/elk/elk-mcp-yml/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Elk Authentication](https://apis.io/security/elk/elk-authentication/)
- [Elk Domain Security](https://apis.io/security/elk/elk-domain-security/)
- [Elk Vulnerability Disclosure](https://apis.io/security/elk/elk-vulnerability-disclosure/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Elk Scopes](https://apis.io/scopes/elk/elk-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Elk Plans Pricing](https://apis.io/plans/elk/elk-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Elk Rate Limits](https://apis.io/rate-limits/elk/elk-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Elk Finops](https://apis.io/finops/elk/elk-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://elk.zone)
- [Documentation](https://docs.elk.zone)
- [Getting started](https://docs.elk.zone/guide)
- [Support](https://github.com/elk-zone/elk/issues)
- [Changelog](https://github.com/elk-zone/elk/releases)
- [Blog](https://elk.zone/blog/)
- [Privacy policy](https://docs.elk.zone/privacy)
- [GitHub](https://github.com/elk-zone)

## API Evangelist rating

**Kin Score 29.1** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 80.4 |
| Contract quality | 0.0 |
| Contract governance | 4.5 |
| Operational transparency | 18.4 |
| Developer ergonomics | 47.6 |
| Access clarity | 10.5 |

**Agent readiness 9.4** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | derived (partial credit) |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
| Event Surface Described | — |
| Agent Skills | yes |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 30.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/elk/](https://apis.io/providers/elk/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Elk: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/elk/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
