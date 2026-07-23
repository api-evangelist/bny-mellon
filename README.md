# BNY Mellon (bny-mellon)

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
