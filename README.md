# SRIFT

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

SRIFT provides a decentralized, end‑to‑end encrypted peer‑to‑peer file transfer and chat platform for humans and AI agents. It operates without accounts or databases, using keys generated on devices and WebRTC‑based relays. The service includes a web app, CLI, MCP server, and tools for AI agents, supporting secure large‑file sharing, real‑time audio, and integration with multiple AI models.

**Areas:** File Transfer · Peer-to-Peer · End-to-End Encryption · Decentralized · Open Source · MCP Server

## SRIFT on APIs.io

Everything profiled for SRIFT is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/srift-app/](https://apis.io/providers/srift-app/)** — or go straight to one of the APIs or properties below.

### APIs (9)

- [SRIFT Agent API](https://apis.io/apis/srift-app/srift-app-agent-api/) — Zero-config endpoints designed for AI agents
- [SRIFT Chat API](https://apis.io/apis/srift-app/srift-app-chat-api/) — E2EE chat
- [SRIFT Discovery API](https://apis.io/apis/srift-app/srift-app-discovery-api/) — Discovery / health
- [SRIFT MCP API](https://apis.io/apis/srift-app/srift-app-mcp-api/) — Model Context Protocol transport
- [SRIFT Monitor API](https://apis.io/apis/srift-app/srift-app-monitor-api/) — Progress + state monitoring
- [SRIFT Peerknock API](https://apis.io/apis/srift-app/srift-app-peerknock-api/) — Agent-to-agent relay (https://srift.app or self-hosted). WebSocket transport at /an. RAM only: no message storage, no database.
- [SRIFT Session API](https://apis.io/apis/srift-app/srift-app-session-api/) — Session lifecycle
- [SRIFT Transfer API](https://apis.io/apis/srift-app/srift-app-transfer-api/) — File transfer (P2P with fallback)
- [SRIFT Transport API](https://apis.io/apis/srift-app/srift-app-transport-api/) — TURN credentials and the HTTPS fallback for the session socket

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [SRIFT Agentic Access](https://apis.io/agentic-access/srift-app/srift-app-agentic-access/)

#### JSON Schema (3)

The data models the API reads and writes.

- [DaemonStatus](https://apis.io/schemas/srift-app/srift-app-daemon-status/)
- [QuickShareResult](https://apis.io/schemas/srift-app/srift-app-quick-share-result/)
- [Transfer](https://apis.io/schemas/srift-app/srift-app-transfer/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Srift App Context](https://apis.io/jsonld/srift-app/srift-app-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [SRIFT API Rules](https://apis.io/rules/srift-app/srift-app-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [SRIFT Authentication](https://apis.io/security/srift-app/srift-app-authentication/)
- [SRIFT Domain Security](https://apis.io/security/srift-app/srift-app-domain-security/)
- [SRIFT Vulnerability Disclosure](https://apis.io/security/srift-app/srift-app-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://srift.app/)
- [Documentation](https://srift.app/about)
- [Getting started](https://srift.app/resources/ai-agents/mcp-client-setup)
- [API reference](https://srift.app/openapi.json)
- [Support](https://srift.app/privacy)
- [Security](https://srift.app/privacy)
- [Privacy policy](https://srift.app/privacy)
- [GitHub](https://github.com/srivardhan113/SRIFT-Open_Source)

## API Evangelist rating

**Kin Score 50.9** — developing · rubric 0.27.0 · scored 2026-11-25

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 53.4 |
| Contract governance | 79.1 |
| Operational transparency | 31.6 |
| Developer ergonomics | 68.3 |
| Access clarity | 10.5 |

**Agent readiness 42.4** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | unknown |
| Reversibility Documented | — |
| MCP Server | documented (partial credit) |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | unknown |
| Well Known Catalog | yes |
| Consent Identity | — |
| Agent Card | conformant |
| Dry Run Mode | — |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | distinct |
| MCP Tool Quality | na |

**Regulatory alignment 26.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/srift-app/](https://apis.io/providers/srift-app/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for SRIFT: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/srift-app/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
