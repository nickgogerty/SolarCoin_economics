# The Solarity: Network Capital Theory, Token Supply Dynamics, and the Threshold of Free Solar Energy

**Empirical Analysis of 84 Fiat Currencies with Issuance-Adjusted Projections and Protocol Design Considerations**

**SolarCoin Foundation**  
January 2026 · Working Paper — Version 2.2 Complete

---

## Abstract

This paper develops a theoretical and empirical framework for cryptocurrency protocol value, with application to renewable energy incentivization. Analyzing 84 fiat currencies representing 95% of global M0 monetary base, we find strong correlation (r = 0.869, R² = 0.755) between network participation and protocol value, with utility converging to approximately $125 per $1,000 GDP per capita. 

We introduce a critical correction to naive Network Capital projections: **token supply dynamics**. As a reward-based protocol, SolarCoin’s circulating supply expands proportionally with network growth. Using industry data from Wiki-Solar, LBNL, and IEA PVPS, we model facility distribution reflecting monitoring platform registrations (92% residential) and derive the equilibrium price formula:

**Price_eq = Utility per Node / Issuance per Node**

At baseline assumptions ($3,500/node utility, 223 SLR average issuance), equilibrium price converges to **$15.68** regardless of network size — correcting naive projections by a factor of 83. We further analyze protocol design implications, including a 5MW registration exclusion policy to prevent supply dilution. Under this framework, **Solarity** — the threshold where rewards exceed production costs — becomes achievable for utility-scale solar in optimal locations at baseline utility assumptions, and for most segments at higher utility levels.

---

## 1. Introduction

### 1.1 The Energy Transition Challenge
The global weighted average levelized cost of electricity (LCOE) of solar PV reached $43/MWh in 2024. However, adoption pace remains insufficient to meet climate targets. This paper examines whether a purpose-designed currency protocol can create a global, borderless incentive layer for solar production.

### 1.2 The Supply Dynamics Problem
Previous analyses often assumed static token supply. For reward-based protocols, circulating supply expands with network growth, creating dilution that offsets network utility gains.

---

## 2. Network Capital Theory

### 2.1 Core Equation
The value of a currency protocol can be expressed as:
**P = Max(R, N, S)**

Where:
- **P**: Price
- **R**: Redemption utility (floor)
- **N**: Network utility (intersubjective emergent value)
- **S**: Speculative utility

### 2.2 Network Utility and Market Capitalization
Total protocol value scales with network participation:
**Market Cap = Nodes × Utility per Node**

Empirical analysis of fiat currencies suggests this value converges to **$500–$15,000** per participant when normalized for economic output.

---

## 4. Empirical Results: Fiat Currency Analysis

### 4.1 Correlation Analysis
Correlation between GDP per capita and Network Utility per Node across 84 currencies:
- **Pearson r**: 0.869
- **R-squared**: 0.755
- **Elasticity**: 1.047 (Indicates proportional/linear scaling)

### 4.2 Summary Statistics (n=84)

| Statistic | Value |
|-----------|-------|
| Mean Normalized Utility | $125.21 per $1,000 GDP/capita |
| Convergence Range | $500–$15,000 absolute utility/node |
| Elasticity coefficient | 1.0474 |

---

## 5. Token Supply Dynamics Model

### 5.1 The Dilution Problem
Naive projections at 20 million nodes imply $1,287/SLR. This ignores issuance to new participants.

### 5.2 SolarCoin Registration Model (Based on Monitoring Platforms)

| Facility Type | Share | Avg kW | CF | Annual SLR | Initial (5yr) |
|---------------|-------|--------|----|------------|---------------|
| Residential | 92% | 8 | 15% | 10.5 | 53 |
| Small Commercial | 7% | 35 | 16% | 49.1 | 245 |
| Community Solar (≤5MW) | 1% | 2,000 | 18% | 3,154 | 15,768 |
| **WEIGHTED AVERAGE** | **100%** | **29.8** | — | **44.6** | **223** |

---

## 8. The Solarity Threshold of Free Solar Energy

**Solarity Condition: Price_SLR ≥ LCOE ($/MWh)**

### Solarity Achievement Analysis

| Solar Segment | LCOE | $3.5K/node | $7.5K/node | $15K/node |
|---------------|------|------------|------------|-----------|
| Best Utility (MENA/Chile) | $12 | **131%** | **280%** | **560%** |
| Global Avg Utility | $43 | 36% | 78% | **156%** |
| Residential Average | $85 | 18% | 40% | 79% |

---

## 10. Conclusion

Protocol utility — not merely network size — determines price appreciation. The corrected model reveals an equilibrium price determined by the ratio of network utility to issuance:

**Price_eq = Utility per Node / Issuance per Node**

For SolarCoin with residential-heavy registration (223 SLR average initial issuance), equilibrium price ranges from **$2.24** (conservative) to **$67.20** (maximum). At the baseline $3,500 assumption, equilibrium of **$15.68** provides a 36% offset of global average LCOE. Solarity is achievable for utility-scale solar in optimal locations at baseline assumptions.

---

*(Full paper available in Solarity_SSRN_v2.2_Complete.docx)*
