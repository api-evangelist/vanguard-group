# The Vanguard Group (vanguard-group)

The Vanguard Group is an American investor-owned asset manager headquartered in Malvern, Pennsylvania, and is "the largest provider of mutual funds in the world" and the second-largest exchange-traded fund (ETF) provider after BlackRock's iShares. Vanguard manages approximately **$12 trillion** in assets as of 2025 and employs roughly **20,000 people** (the "crew") as of December 31, 2024. The firm was founded on **May 1, 1975** by **John C. ("Jack") Bogle** and is structured as a mutual: "Vanguard is owned by the funds managed by the company and is therefore owned by its customers." **Salim Ramji** was appointed Chief Executive Officer in **July 2024**.

**URL:** [https://investor.vanguard.com](https://investor.vanguard.com)

**Corporate site:** [https://corporate.vanguard.com](https://corporate.vanguard.com)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Active Management, Advisor Services, Asset Management, Brokerage, ETFs, Finance, Financial Services, Fixed Income, Index Investing, Institutional Investment, Investment Management, Money Management, Mutual Funds, Personal Advice, Recordkeeping, Retirement, Wealth Management

## Business Lines

- **Index Mutual Funds** — Vanguard pioneered the retail index mutual fund with the launch of the First Index Investment Trust (now the Vanguard 500 Index Fund) in 1976. Index funds remain the foundation of Vanguard's low-cost, passive identity.
- **Active Mutual Funds** — Active equity and fixed-income mutual funds managed in-house and by sub-advisors, including long-running flagships such as Vanguard Wellington and Vanguard Wellesley Income.
- **ETFs** — Second-largest ETF provider globally, after BlackRock's iShares. Core total-market ETFs (**VTI, VXUS, BND, BNDX**), the Vanguard **S&P 500 ETF (VOO)**, ESG ETFs, short-term ETFs, sector and factor strategies, and active ETFs.
- **Personal Advisor** — Hybrid robo + human-advisor offering across tiered services (Vanguard Digital Advisor, Vanguard Personal Advisor, Vanguard Personal Advisor Select, Vanguard Personal Advisor Wealth Management).
- **Retirement Plan Services** — Defined-contribution recordkeeping for plan sponsors (401(k), 403(b), 457, DB administration), plus IRAs and rollover support.
- **Institutional Asset Management** — Mandates for corporate pensions, endowments, foundations, healthcare systems, insurance general accounts, and sovereigns served through institutional.vanguard.com.
- **Fixed Income** — Large in-house fixed-income franchise spanning municipal bonds, taxable bonds, money market funds, and bond ETFs (BND, BNDX, BSV, BIV, VCIT, VCSH, VTEB).
- **Brokerage and Trading** — Self-directed brokerage account for stocks, ETFs (including non-Vanguard ETFs), mutual funds, options, and fixed income.
- **Financial Advisor Services (FAS)** — Authenticated portal at advisors.vanguard.com for independent and broker-dealer-affiliated financial advisors allocating client assets to Vanguard funds and ETFs.

## Leadership

- **Salim Ramji** — Chief Executive Officer (appointed July 2024)
- **John C. ("Jack") Bogle** — Founder (1929–2019); founded Vanguard May 1, 1975

## Global Presence

- **Americas:** Canada, United States, Mexico, US Offshore, South America
- **Europe:** Austria, Belgium, Denmark, Finland, France, Germany, Iceland, Ireland, Italy, Liechtenstein, Luxembourg, Netherlands, Norway, Poland, Portugal, Spain, Sweden, Switzerland, United Kingdom
- **Asia Pacific:** Australia

## Investor and Advisor Channels

- [Retail Investor Portal](https://investor.vanguard.com)
- [Financial Advisor Services (FAS)](https://advisors.vanguard.com)
- [Institutional Portal](https://institutional.vanguard.com)
- [Global Site](https://global.vanguard.com)
- [Corporate Site](https://corporate.vanguard.com)
- [Newsroom](https://corporate.vanguard.com/content/corporatesite/us/en/corp/news-and-newsroom.html)
- [Research & Commentary](https://corporate.vanguard.com/content/corporatesite/us/en/corp/research-and-commentary.html)
- [ETFs](https://investor.vanguard.com/investment-products/etfs)
- [Mutual Funds](https://investor.vanguard.com/investment-products/mutual-funds)
- [Personal Advisor](https://investor.vanguard.com/advice)

## Scale Snapshot

- Assets Under Management: **~$12 trillion** (as of 2025)
- Employees ("Crew"): **~20,000** (as of December 31, 2024)
- Founded: **May 1, 1975**
- Headquarters: **Malvern, Pennsylvania, U.S.**
- Structure: **Investor-owned mutual** — owned by the Vanguard funds and therefore by fund shareholders
- ETF Rank: **#2 globally** (after BlackRock's iShares)
- Mutual Fund Rank: **#1 globally**

## API Surface

Vanguard does **not** publish a public developer API program. There are no OpenAPI specifications, no SDKs, no CLI, no public webhooks, and no Vanguard-published public RSS feeds. There is no `developer.vanguard.com` / `api.vanguard.com` developer portal.

Investor, advisor, recordkeeping, and distribution-platform integrations are delivered through:

- Authentication-gated portals: investor.vanguard.com (retail), advisors.vanguard.com (financial advisors), institutional.vanguard.com (plan sponsors and institutional clients)
- Industry fund-trading rails: NSCC Fund/SERV, DTCC clearing and settlement, ACATS for transfers
- SEC EDGAR filings (13F-HR, N-PORT, N-CSR, N-CEN, N-PX, prospectuses)
- PDF reports (annual, semi-annual, summary prospectus, statement of additional information)
- Fund-administrator data feeds (private)
- Email / in-portal messaging (no public webhook surface)

The `github.com/Vanguard-Group` organization was created on **2026-03-25** but currently exposes **zero public repositories** and **zero public members**.

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
