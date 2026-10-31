# Push Protocol

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

Push Protocol (formerly EPNS) is a Web3 communication and Layer 1 blockchain protocol that enables universal
applications deployable once and accessible from any chain. Push Chain is the first true Universal Layer 1
blockchain offering 100% EVM compatibility, 4.2k TPS, 1-second native block time, and instant finality.
The platform provides a JavaScript/TypeScript SDK (@pushchain/core) that wraps universal signing, cross-chain
transaction routing, multichain execution, message signing, smart contract helpers, and utility functions.
Developers can send universal transactions from Ethereum, Solana, BNB Chain, Base, and Arbitrum to Push Chain
via a single SDK call, with fee abstraction allowing gas payment in any supported token (ETH, SOL, USDC, USDT).
Push Chain also offers a testnet faucet (faucet.push.org) delivering 1 PC per address per 6 hours, and a
UI Kit for React-based wallet and signer abstraction.

**Areas:** Web3 · Blockchain · Layer 1 · Universal Apps · Cross-Chain · EVM · Solana · Notification · Messaging · Wallet Abstraction · Fee Abstraction · DeFi

## Push Protocol on APIs.io

Everything profiled for Push Protocol is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/push-protocol/](https://apis.io/providers/push-protocol/)** — or go straight to one of the APIs or properties below.

### APIs (5)

- [Push Chain Core SDK](https://apis.io/apis/push-protocol/push-chain-sdk/) — JavaScript/TypeScript SDK (@pushchain/core) for the Push Chain Universal Layer 1 blockchain. Exposes PushChain.initialize(signer, {network}) for client…
- [Push Chain EVM Client](https://apis.io/apis/push-protocol/push-chain-evm-client/) — Push Chain is 100% EVM-compatible; developers can initialize standard Ethers v6 or Viem clients against Push Chain RPC endpoints without modifying existing…
- [Push Chain Contract Helpers (UEAFactory)](https://apis.io/apis/push-protocol/push-chain-contract-helpers/) — On-chain contract helpers deployed at 0x00000000000000000000000000000000000000eA (UEAFactory). getOriginForUEA(address) returns the UniversalAccountId and…
- [Push Chain Testnet Faucet](https://apis.io/apis/push-protocol/push-chain-faucet/) — Public testnet faucet at faucet.push.org for the Push Chain Donut Testnet. Delivers 1 PC (native gas token) per wallet address per 6 hours. Rate-limited and…
- [Push Chain UI Kit](https://apis.io/apis/push-protocol/push-chain-ui-kit/) — React UI component library providing PushUniversalWalletProvider and PushUniversalAccountButton for abstracting wallet connection and universal signer…

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [push-protocol](https://apis.io/servers/push-protocol/push-protocol/)

#### Security (1)

Authentication, trust centre, and vulnerability disclosure.

- [Push Protocol Domain Security](https://apis.io/security/push-protocol/push-protocol-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Push Protocol Plans](https://apis.io/plans/push-protocol/push-protocol-plans/)

#### Rate limits (1)

Published request limits.

- [Push Protocol Rate Limits](https://apis.io/rate-limits/push-protocol/push-protocol-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Push Protocol Finops](https://apis.io/finops/push-protocol/push-protocol-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://push.org)
- [Documentation](https://push.org/docs/chain)
- [Getting started](https://push.org/docs/chain/quickstart)
- [Pricing](https://push.org)
- [Blog](https://push.org/blog)
- [Terms of service](https://push.org/tos)
- [Privacy policy](https://push.org/privacy)

## API Evangelist rating

**Kin Score 23.0** — emerging · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 65.0 |
| Contract quality | 0.0 |
| Contract governance | 0.0 |
| Operational transparency | 7.9 |
| Developer ergonomics | 38.1 |
| Access clarity | 44.7 |

**Agent readiness 11.2** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | — |
| Agentic Access | — |
| Reversibility Documented | — |
| MCP Server | verified |
| Auth Clarity | — |
| Idempotency | — |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | documented (partial credit) |
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
| Operation Distinctiveness | na |

**Regulatory alignment 12.5** — Payments

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/push-protocol/](https://apis.io/providers/push-protocol/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Push Protocol: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/push-protocol/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
