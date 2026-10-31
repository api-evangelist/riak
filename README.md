# Riak KV

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

Riak KV is a distributed NoSQL key-value database originally developed by Basho Technologies, designed for high availability, fault tolerance, and horizontal scalability across commodity hardware. Riak exposes two client-facing APIs: a RESTful HTTP API for basic GET, PUT, POST, and DELETE operations, and a higher-performance Protocol Buffers (PBC) API spoken over TCP. Both APIs support buckets, objects, secondary indexes, search, MapReduce, and CRDT data types.

**Areas:** Database · NoSQL · Key-Value Store · Distributed Systems · Open Source · Basho · CRDT

## Riak KV on APIs.io

Everything profiled for Riak KV is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/riak/](https://apis.io/providers/riak/)** — or go straight to one of the APIs or properties below.

### APIs (8)

- [Riak KV HTTP API](https://apis.io/apis/riak/http-api/) — RESTful HTTP API for Riak KV providing GET, PUT, POST, and DELETE access to buckets, objects, secondary indexes, search, MapReduce, and CRDT data types.…
- [Riak Protocol Buffers Client API](https://apis.io/apis/riak/protocol-buffers/) — Higher-performance binary client API for Riak KV using Protocol Buffers messages encoded over a long-lived TCP connection. Default port is 8087. Each…
- [Riak KV Mapred API](https://apis.io/apis/riak/riak-mapred-api/) — The Mapred API from Riak KV — 1 operation(s) for mapred.
- [Riak KV Ping API](https://apis.io/apis/riak/riak-ping-api/) — The Ping API from Riak KV — 1 operation(s) for ping.
- [Riak KV Riak KV HTTP API](https://apis.io/apis/riak/riak-riak-kv-http-api-api/) — The Riak KV HTTP API API from Riak KV — 1 operation(s) for riak kv http api.
- [Riak KV Search API](https://apis.io/apis/riak/riak-search-api/) — The Search API from Riak KV — 4 operation(s) for search.
- [Riak KV Stats API](https://apis.io/apis/riak/riak-stats-api/) — The Stats API from Riak KV — 1 operation(s) for stats.
- [Riak KV Types API](https://apis.io/apis/riak/riak-types-api/) — The Types API from Riak KV — 7 operation(s) for types.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Riak Agentic Access](https://apis.io/agentic-access/riak/riak-agentic-access/)

#### Collections (7)

Postman and Open Collection request collections.

- [Riak KV HTTP API](https://apis.io/collections/riak/open-riak/)
- [Riak KV HTTP Mapred API](https://apis.io/collections/riak/open-riak-mapred-api/)
- [Riak KV HTTP Mapred Ping API](https://apis.io/collections/riak/open-riak-ping-api/)
- [Riak KV HTTP Mapred Riak KV HTTP API API](https://apis.io/collections/riak/open-riak-riak-kv-http-api-api/)
- [Riak KV HTTP Mapred Search API](https://apis.io/collections/riak/open-riak-search-api/)
- [Riak KV HTTP Mapred Stats API](https://apis.io/collections/riak/open-riak-stats-api/)
- [Riak KV HTTP Mapred Types API](https://apis.io/collections/riak/open-riak-types-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Riak Authentication](https://apis.io/security/riak/riak-authentication/)
- [Riak Domain Security](https://apis.io/security/riak/riak-domain-security/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://riak.com)
- [Documentation](https://docs.riak.com/riak/kv/latest/)
- [Blog](https://riak.com/blog/)
- [GitHub](https://github.com/basho)

## API Evangelist rating

**Kin Score 25.0** — emerging · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 40.4 |
| Contract governance | 0.0 |
| Operational transparency | 2.6 |
| Developer ergonomics | 31.0 |
| Access clarity | 0.0 |

**Agent readiness 17.3** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | — |
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

**Regulatory alignment 11.8** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/riak/](https://apis.io/providers/riak/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Riak KV: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/riak/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
