# SolarCoin Economics

> **SolarCoin Network Capital Theory, Token Supply Dynamics, and the Threshold of Free Solar Energy**
> SolarCoin Foundation · January 2026 Working Papers

[![License: CC0-1.0](https://img.shields.io/badge/License-CC0_1.0-lightgrey.svg)](http://creativecommons.org/publicdomain/zero/1.0/)
[![SolarCoin](https://img.shields.io/badge/SolarCoin-SLR-yellow)](https://solarcoin.org)
[![Energy Web Chain](https://img.shields.io/badge/Chain-Energy%20Web-green)](https://energyweb.org)

This repository contains the SolarCoin Foundation's research papers, data, and analysis on the economics of the SolarCoin (SLR) protocol — including Network Capital theory, token supply dynamics, and the Solarity threshold (the point at which solar energy becomes effectively free).

---

## Repository Structure

```
SolarCoin_economics/
├── papers/
│   ├── solarity-network-capital-theory.md      # Full working paper v2.2
│   └── network-capital-analysis.md             # Cross-asset empirical analysis
├── data/
│   └── appendix-c-currency-data.md             # 90 fiat currencies, 50 cryptos, gold
├── docs/
│   ├── token-economics.md                      # Supply dynamics & equilibrium price
│   └── solarity-threshold.md                   # Solarity achievement conditions
└── README.md
```

---

## Key Findings at a Glance

### Network Capital Empirical Results (84 Fiat Currencies)

| Metric | Value | Interpretation |
|--------|-------|----------------|
| Pearson r (log-transformed) | **0.869** | Very strong positive correlation |
| R-squared | **0.755** | 75.5% variance explained by GDP/capita |
| Elasticity coefficient | **1.047 ≈ 1.0** | Proportional (linear) scaling |
| Normalized Utility Mean | **$125 per $1,000 GDP/capita** | Fundamental constant |
| Sample Coverage | **84 countries / 95% of global M0** | Robust cross-country |

### Core Equation

```
P = Max(R, N, S)
```

Where:
- **P** = Protocol price
- **R** = Redemption utility (≈ 0 for fiat/crypto)
- **N** = Network utility (dominant in stable regimes)
- **S** = Speculative utility

### Equilibrium Price Formula (Supply-Adjusted)

For reward-based protocols, naive static-supply projections overstate price by up to **83×**. The corrected equilibrium:

```
Price_eq = Utility per Node / Issuance per Node
```

At baseline assumptions:
- Utility per node: **$3,500**
- Average issuance per node: **223 SLR** (residential-weighted)
- **Equilibrium price: $15.68** — independent of network size

---

## SolarCoin Network (January 2026)

| Metric | Value |
|--------|-------|
| Registered Installations | 30,910 nodes |
| Countries | 170 |
| Nameplate Capacity | 3.47 GW |
| Circulating Supply | 54.4M SLR |
| Current Price | ~$0.04–$0.06 |
| Current Utility/Node | ~$87 (pre-critical mass) |
| SLR Contract (EWC) | `0x26E4991a72728b1a9B1044345e5bF9293E0A1434` |
| SLR Contract (ETH) | `0x4E9e4Ab99Cfc14B852f552f5Fb3Aa68617825B6c` |
| SLR Contract (zkSync Era) | `0xE027D939f7dE6F521675907Cf086F59E4D75B876` |

---

## Supply-Adjusted Network Projections ($3,500/node utility)

| Scenario | Nodes | New Issuance | Total Supply | Market Cap | Price (Adjusted) | Price (Naive) |
|----------|-------|-------------|-------------|-----------|-----------------|---------------|
| Current | 30,910 | — | 54.4M | $0.11B | $1.99 | $1.99 |
| 0.5% Penetration | 100,000 | 15.4M | 69.8M | $0.35B | **$5.01** | $6.43 |
| 1% Penetration | 200,000 | 37.7M | 92.1M | $0.70B | **$7.60** | $12.87 |
| 5% Penetration | 1,000,000 | 216.3M | 270.7M | $3.50B | **$12.93** | $64.34 |
| 10% Penetration | 2,000,000 | 439.5M | 493.9M | $7.00B | **$14.17** | $128.68 |
| 25% Penetration | 5,000,000 | 1,109M | 1,164M | $17.50B | **$15.04** | $321.69 |
| 100% Penetration | 20,000,000 | 4,457M | 4,512M | $70.00B | **$15.52** | $1,286.76 |

> The correction factor grows with network size. At full penetration, naive projections overstate price by **83×**.

---

## Equilibrium Price Sensitivity

| Utility per Node | Equilibrium Price | % of $43 LCOE | Solarity Status |
|-----------------|------------------|--------------|----------------|
| $500 (Conservative) | $2.24 | 5% | Minimal offset |
| $3,500 (Baseline) | **$15.68** | 36% | Significant offset |
| $7,500 (Optimistic) | **$33.60** | 78% | Near-Solarity |
| $15,000 (Maximum) | **$67.20** | 156% | **Full Solarity** |

---

## The Solarity Threshold

Solarity is achieved when: **Price_SLR ≥ LCOE ($/MWh)**

Since SolarCoin issues 1 SLR per MWh of verified production, the comparison is direct.

| Solar Segment | LCOE | @$3.5K/node | @$7.5K/node | @$15K/node | Status |
|--------------|------|------------|------------|-----------|--------|
| Best Utility (MENA/Chile) | $12 | 131% | 280% | 560% | ✅ Solarity at baseline |
| China/India Utility | $35 | 45% | 96% | 192% | ✅ Solarity at $15K |
| Global Avg Utility | $43 | 36% | 78% | 156% | ✅ Solarity at $15K |
| US Utility-Scale | $58 | 27% | 58% | 116% | ✅ Solarity at $15K |
| Commercial Rooftop | $50 | 31% | 67% | 134% | ✅ Solarity at $15K |
| Residential (Good) | $60 | 26% | 56% | 112% | ✅ Solarity at $15K |
| Residential (Average) | $85 | 18% | 40% | 79% | ⚠️ Max 79% offset |

---

## Facility Distribution Model

SolarCoin registrations flow primarily through monitoring platforms (Enphase, SMA Sunny Portal, SolarEdge), which are 85–92% residential.

| Facility Type | Share | Avg kW | CF | Annual SLR | Initial (5yr) |
|--------------|-------|--------|-----|-----------|---------------|
| Residential | 92% | 8 | 15% | 10.5 | 53 |
| Small Commercial | 7% | 35 | 16% | 49.1 | 245 |
| Community Solar (≤5MW) | 1% | 2,000 | 18% | 3,154 | 15,768 |
| **Weighted Average** | 100% | 29.8 | — | **44.6** | **223** |

### 5MW Exclusion Policy Rationale

Facilities >5MW operate under sophisticated revenue stacking (PPAs, ITC, RECs, tax equity) and do not require marginal incentives. A single 100MW project would claim ~109,500 SLR — more than 2,000 residential installations combined. The 5MW cap:
- Prevents supply dilution from mega-projects
- Focuses rewards on distributed solar where marginal incentives influence adoption
- Aligns with monitoring platform registration reality (already <5% large utility)
- Maintains equilibrium price stability

---

## Cross-Asset Network Capital Comparison

| Asset Class | Total Value | Est. Nodes | Avg Utility/Node |
|------------|-------------|-----------|------------------|
| Fiat Currencies (90) | $20.8T | 7.14B | $4,168 |
| Cryptocurrencies (50) | $2.93T | 321.4M | $10,403 |
| Gold (Total) | $30.2T | 2B | $15,100 |
| Gold (Investment only) | $7.8T | 150M | $52,000 |
| Bitcoin | $1,799B | 106M | $16,972 |
| Ethereum | $365B | 30M | $12,176 |
| **SolarCoin (Current)** | **$2.7M** | **31K** | **$87** |
| **SolarCoin (Projected)** | **$70B** | **20M** | **$3,500** |

---

## Papers in This Repository

### 1. [The Solarity: Network Capital Theory, Token Supply Dynamics, and the Threshold of Free Solar Energy](papers/solarity-network-capital-theory.md)
*SolarCoin Foundation Working Paper v2.2 — January 2026*

Full empirical analysis of 84 fiat currencies establishing the Network Capital framework, with explicit supply dynamics correction and Solarity threshold analysis. Published to SSRN.

**Key contributions:**
- Empirical validation of Network Capital theory (r=0.869, n=84)
- Supply dynamics model correcting naive projections by up to 83×
- Equilibrium price formula for reward-based protocols
- Protocol design implications of the 5MW exclusion policy

### 2. [Network Capital: The Emergence of Monetary Value](papers/network-capital-analysis.md)
*Network Capital Research — January 21, 2026*

Comprehensive cross-asset analysis covering 90 fiat currencies, 30 cryptocurrencies, and gold. Provides empirical support for proportional (linear) value scaling, contradicting Metcalfe's Law for currency networks.

### 3. [Appendix C: Currency Data Tables](data/appendix-c-currency-data.md)
*90 Fiat Currencies, 50 Cryptocurrencies, and Gold — January 2026*

Full data tables used in the empirical analysis. Includes M0 monetary base, population, GDP per capita, utility/node for all 90 countries, top 50 cryptocurrencies, and gold.

### 4. [Token Economics Reference](docs/token-economics.md)
Key formulas, supply dynamics methodology, and issuance model documentation.

### 5. [Solarity Threshold Analysis](docs/solarity-threshold.md)
Detailed analysis of Solarity achievement conditions by solar market segment and geography.

---

## References

1. Gogerty, N. & Zitoli, J. (2018). *Network Capital: Value of Currency Protocols — Bitcoin & SolarCoin Cases in Context.* SSRN. https://ssrn.com/abstract=3281845
2. IRENA (2025). *Renewable Power Generation Costs in 2024.*
3. Lawrence Berkeley National Laboratory (2024). *Utility-Scale Solar, 2024 Edition.*
4. Wiki-Solar (2025). *Global Utility-Scale Solar Database.* February 2025 Release.
5. IEA PVPS (2025). *Snapshot of Global PV Markets 2025.*
6. Global Energy Monitor (2025). *Global Solar Power Tracker.*
7. Lazard (2025). *Levelized Cost of Energy Analysis, Version 18.0.*
8. IMF (2025). *World Economic Outlook Database, October 2025.*
9. BloombergNEF (2025). *New Energy Outlook 2025.*
10. NREL (2025). *Annual Technology Baseline 2025.*

---

## License

CC0 1.0 Universal — Public Domain Dedication. All research and data in this repository is released into the public domain.

---

*SolarCoin Foundation · [solarcoin.org](https://solarcoin.org) · [@SolarCoin_SLR](https://twitter.com/SolarCoin_SLR)*
