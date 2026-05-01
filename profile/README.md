# Cadmos

> Cadmos fosters financial inclusion by disintermediating capital markets and cross-border payments globally.

For most of the past decade, the way money moves and the way money is invested have lived in different worlds — gated by stacks of intermediaries that price out the people who need them most. Self-custody and institutional compliance were treated as incompatible. None of this had to be true.

Cadmos was founded in 2021 to rebuild the stack as one product the user actually owns. Operated by **Cadmos LTD** (Cyprus, registration ΗΕ 457316), the group ships three coordinated products:

| Product | What it disintermediates |
|---|---|
| [**Cadmos Pay**](https://www.cadmospay.com) | Cross-border payments. Self-custodial money app — stablecoin wallet on Arbitrum, Visa card with Apple/Google Pay, virtual IBAN, DeFi access, tokenized equities, multi-chain deposits, eSIM.|
| [**Cadmos Finance**](https://cadmos.finance) | Capital markets. End-to-end tokenization infrastructure for funds and private-market issuances — investor onboarding, programmable compliance, NAV and settlement, investor and admin portals. On-chain corporate actions|
| [**Cadmos IO**](https://cadmos.io) | The seam between the two. Partnership and ecosystem layer — white-label deployments, institutional integrations, group narrative. |

All three are live in production with real customers.

## The integrated loop

bank wire  →  IBAN  →  stablecoin wallet (Pay)  →  tokenized fund subscription (Finance)
                                                            ↓
                                                      hold / redeem
                                                            ↓
                                                Visa card spend  /  off-ramp (Pay)

Same user. Same stack. Cadmos Pay users subscribe to Cadmos Finance issuances inside the Pay app today — that's shipping, not roadmap.

## Recognition

In 2023, Cadmos Finance won the **CAST Challenge** organised by **Société Générale-FORGE** — with Crédit Agricole CIB, ABN-AMRO, AXA IM, Banco Santander, ICMA, Swift, and Visa as supporting sponsors — for its on-chain Delivery-vs-Payment architecture for security tokens. That same DvP engine settles every Cadmos Finance subscription today.

→ Press: [Finyear — *Le CAST Challenge annonce les vainqueurs de sa 2nde édition*](https://finyear.com/Le-CAST-Challenge-annonce-les-vainqueurs-de-sa-2nde-edition_a49734.html)


## Public repositories

Selected open-source code from the Cadmos group:

- **[sc-bonds-dvp-cadmos](https://github.com/Cadmos-finance/sc-bonds-dvp-cadmos)** — On-chain **Delivery-vs-Payment for security tokens**. The reference implementation that won the [2023 CAST   Challenge](https://finyear.com/Le-CAST-Challenge-annonce-les-vainqueurs-de-sa-2nde-edition_a49734.html) organised by Société Générale-FORGE: atomic DvP, DvP with forex, broker-intermediated transactions with no broker capital, programmable compliance, multi-party trade. The same DvP engine settles every Cadmos Finance subscription in production today.

- **[Cadmos-Pay-Recovery](https://github.com/Cadmos-finance/Cadmos-Pay-Recovery)** — Self-custody emergency recovery kit for Cadmos Pay. The proof that Cadmos Pay is genuinely self-custodial: even if the Cadmos app or infrastructure is unavailable, users can recover their assets independently from this open-source contract and front-end.

- **[Stake2Care-sc](https://github.com/Cadmos-finance/Stake2Care-sc)** — ERC-4626 vault smart contracts powering **[Stake2Care](https://stake2care.msf.ch/)**, the donation-yield platform Cadmos built with **Doctors Without Borders (MSF Switzerland)**. Donate the staking and DeFi yield of value-accruing assets — Lido stETH, Morpho Steakhouse USDC, Morpho Steakhouse USDT — to MSF, keep the principal. Audited by BlackPaper and HHK. Deployed on Ethereum Mainnet.


## Contact

- info@cadmos.finance
- [LinkedIn](https://www.linkedin.com/company/cadmosam) · [X](https://x.com/CadmosIO) ·
[Crunchbase](https://www.crunchbase.com/organization/cadmos-00fe)
- [Documentation](https://docs.cadmos.finance)
