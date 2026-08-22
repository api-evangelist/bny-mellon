# BNY Mellon (bny-mellon)

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

BNY Mellon (legal parent The Bank of New York Mellon Corporation, rebranded to "BNY" in 2024) is a US money-center bank and the world's largest custodian, overseeing roughly $50 trillion in assets under custody and/or administration. Its principal banking subsidiary, The Bank of New York Mellon, is a nationally chartered, OCC-supervised bank headquartered in New York City, operating across Securities Services, Market & Wealth Services, and Investment & Wealth Management.

BNY runs a genuine first-party developer program — the **BNY Developer Marketplace** at [developer.bny.com](https://developer.bny.com) (formerly marketplace.bnymellon.com) — publishing Treasury Services, Asset Servicing, Markets, and Pershing API families to corporate, fintech, and financial-institution clients. Registration and the full API reference are gated behind Nexen single sign-on, and no OpenAPI/Swagger is publicly downloadable. BNY also ships a public, smart-contract-only **Data On-Chain** product that broadcasts fund accounting data to Ethereum.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/bny-mellon/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/bny-mellon/refs/heads/main/apis.yml)

## Open-Finance Posture

- **First-party developer portal:** Yes — [developer.bny.com](https://developer.bny.com) (HTTP 200 confirmed), the BNY Developer Marketplace.
- **Downloadable OpenAPI/Swagger:** No — API reference and specs sit behind Nexen SSO.
- **FDX participation / CFPB 1033 posture:** None publicly documented.
- **Aggregator access:** Consumer / business-banking account data is reached primarily through aggregators such as Plaid, not a first-party consumer data API.
- **On-chain data:** Public smart-contract product (Data On-Chain) on Ethereum Mainnet + Sepolia.

## Tags

- Financial Services
- Banking
- United States
- Custody Bank
- Treasury Services
- Payments
- Digital Assets
- Open Finance

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### BNY Treasury Services API

Payments (USD clearing, global ACH, RTP, wires, Pay by Bank), liquidity, cash management, trade finance, and FX for corporate and financial-institution clients. Full reference and sandbox gated behind Nexen SSO.

- **Human URL:** [https://marketplace.bnymellon.com/treasury/api-library/treasury-services-apis](https://marketplace.bnymellon.com/treasury/api-library/treasury-services-apis)

#### Properties

- [Documentation](https://marketplace.bnymellon.com/treasury/api-library/treasury-services-apis)
- [API Reference](https://developer.bny.com/app/open/apis)

### BNY Asset Servicing API

Custody, fund accounting, middle-office, and transfer-agency operations, published through the BNY Developer Marketplace. Reference gated behind Nexen SSO.

- **Human URL:** [https://developer.bny.com/app/open/apis](https://developer.bny.com/app/open/apis)

#### Properties

- [Documentation](https://developer.bny.com/app/open/apis)

### BNY Markets API

FX, securities finance, fixed income, and equities surface. Reference gated behind Nexen SSO.

- **Human URL:** [https://developer.bny.com/app/open/apis](https://developer.bny.com/app/open/apis)

#### Properties

- [Documentation](https://developer.bny.com/app/open/apis)

### BNY Pershing API

Clearing, custody, and the NetX360+ / Wove wealth platforms serving broker-dealers and RIAs. Reference gated behind Nexen SSO.

- **Human URL:** [https://developer.bny.com/app/open/apis](https://developer.bny.com/app/open/apis)

#### Properties

- [Documentation](https://developer.bny.com/app/open/apis)

### BNY Data On-Chain

Public, smart-contract-only product broadcasting BNY-attested fund accounting data to public blockchains (first implementation: BlackRock USD Digital Liquidity BUIDL Fund). Consumers read via a Solidity interface (`IBNYDataConsumerV2`) with a proxy-upgrade pattern — no OpenAPI/HTTP surface. Deployed on Ethereum Mainnet (`0x7B0eC8D1D1254358A77f107118e96885EdDCEb16`) and Sepolia (`0xCC75D07cBC86f306A033af29508a1b98E2178264`).

- **Human URL:** [https://github.com/bnymellon/bny-data-on-chain](https://github.com/bnymellon/bny-data-on-chain)

#### Properties

- [Documentation](https://github.com/bnymellon/bny-data-on-chain)
- [Source Code](https://github.com/bnymellon/bny-data-on-chain)

## Common Properties

- [Website](https://www.bny.com)
- [Developer Portal](https://developer.bny.com)
- [Documentation](https://developer.bny.com/app/open/apis)
- [GitHub Organization](https://github.com/bnymellon)
- [LinkedIn](https://www.linkedin.com/company/the-bank-of-new-york-mellon-corporation)
- [Support](https://developer.bny.com/app/open/support)
- [Terms of Service](https://www.bny.com/corporate/global/en/terms-of-use.html)
- [Privacy Policy](https://www.bny.com/corporate/global/en/data-privacy.html)
- [About](https://www.bny.com/corporate/global/en/about-us.html)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
