# IDrive

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

IDrive Inc. provides cloud backup and IDrive e2, an S3-compatible object storage service. For developers it publishes the IDrive e2 Reseller API (a REST/JSON API at api.idrivee2.com for managing users, regions, access keys, CNAME whitelabeling and subusers, authenticated with an API key sent in a token header), the S3-compatible storage endpoints themselves, and IDrive e2 MCP, an OAuth-protected hosted Model Context Protocol server at mcp.idrivee2.com/s3 (with a self-hosted option) exposing 65 bucket and object tools to AI clients.

**Areas:** Company · Object Storage · S3 Compatible · Cloud Storage · Backup · Reseller · MCP

## IDrive on APIs.io

Everything profiled for IDrive is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/idrive/](https://apis.io/providers/idrive/)** — or go straight to one of the APIs or properties below.

### APIs (2)

- [IDrive Reseller API](https://apis.io/apis/idrive/idrive-reseller-api/) — The Reseller API from IDrive — 24 operation(s) for reseller.
- [IDrive Subusers API](https://apis.io/apis/idrive/idrive-subusers-api/) — The Subusers API from IDrive — 9 operation(s) for subusers.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [idrive-e2](https://apis.io/servers/idrive/idrive-e2/)

#### JSON Schema (6)

The data models the API reads and writes.

- [PostApiResellerV1EditUserResponse](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-edit-user-response/)
- [PostApiResellerV1RemoveAccessKeyResponse](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-remove-access-key-response/)
- [PostApiResellerV1StorageBucketStatsResponse](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-storage-bucket-stats-response/)
- [PostApiResellerV1StorageCnameAddRequest](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-storage-cname-add-request/)
- [PostApiResellerV1StorageCnameResponse](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-storage-cname-response/)
- [PostApiResellerV1StorageCnameUpdateResponse](https://apis.io/schemas/idrive/idrive-post-api-reseller-v1-storage-cname-update-response/)

#### JSON-LD (1)

Linked-data contexts for the provider's vocabulary.

- [Idrive Context](https://apis.io/jsonld/idrive/idrive-context/)

#### Governance rules (1)

Spectral rulesets for the provider's contracts.

- [IDrive API Rules](https://apis.io/rules/idrive/idrive-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Idrive Authentication](https://apis.io/security/idrive/idrive-authentication/)
- [Idrive Domain Security](https://apis.io/security/idrive/idrive-domain-security/)
- [Idrive Trust Center](https://apis.io/security/idrive/idrive-trust-center/)

#### OAuth scopes (1)

The permissions the API asks for.

- [Idrive Scopes](https://apis.io/scopes/idrive/idrive-scopes/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Idrive Plans](https://apis.io/plans/idrive/idrive-plans/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.idrive.com)
- [Documentation](https://www.idrive.com/s3-storage-e2/developer-guide)
- [API reference](https://www.idrive.com/s3-storage-e2/reseller-api)
- [Pricing](https://www.idrive.com/s3-storage-e2/pricing)
- [Sign up](https://console.idrivee2.com/signup)
- [Support](https://www.idrive.com/s3-storage-e2/support)
- [Blog](https://blog.idrive.com/)
- [Security](https://www.idrive.com/endpoint-backup/security)
- [Compliance](https://security.idrive.com/)
- [Terms of service](https://www.idrive.com/s3-storage-e2/terms)
- [Privacy policy](https://www.idrive.com/privacy)

## API Evangelist rating

**Kin Score 48.0** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 70.0 |
| Contract quality | 26.5 |
| Contract governance | 22.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 45.2 |
| Access clarity | 92.1 |

**Agent readiness 43.1** — agent-ready (gated down from agent-native)

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | — |
| Reversibility Documented | documented (partial credit) |
| MCP Server | documented (partial credit) |
| Auth Clarity | served (partial credit) |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | — |
| Delegated Identity | served (partial credit) |
| Protected Resource Metadata | verified |
| Dynamic Client Registration | yes |
| Agentic Commerce | — |
| Pagination Ratio | na |
| Operation Distinctiveness | distinct |

**Regulatory alignment 39.2** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/idrive/](https://apis.io/providers/idrive/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for IDrive: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/idrive/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
