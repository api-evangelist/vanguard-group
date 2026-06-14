# Vanguard Group GraphQL

## Description

The Vanguard Group does not publish a native public GraphQL API. All investor, advisor, recordkeeping, and institutional integrations are delivered through authentication-gated portals (investor.vanguard.com, advisors.vanguard.com, institutional.vanguard.com), PDF reporting, brokerage and custodian rails, fund-administrator data feeds, and industry recordkeeping interfaces (NSCC Fund/SERV, DTCC).

This schema is a conceptual GraphQL data model derived from Vanguard's publicly documented product surface — mutual funds, ETFs, brokerage accounts, retirement plan services, personal advisor services, and institutional asset management. It is intended to represent how Vanguard's investment data domain could be expressed as a GraphQL API if one were ever made public.

## Endpoint

No public GraphQL endpoint exists. If a private or partner GraphQL layer exists, it would be accessible only through authenticated advisor or institutional integrations under:

- https://advisors.vanguard.com (Financial Advisor Services)
- https://institutional.vanguard.com (Institutional Asset Management / Retirement Plan Services)

## Documentation

- Investor Portal: https://investor.vanguard.com
- Advisor Portal: https://advisors.vanguard.com
- Institutional Portal: https://institutional.vanguard.com
- Corporate Site: https://corporate.vanguard.com
- SEC EDGAR Filings: https://www.sec.gov/cgi-bin/browse-edgar?action=getcompany&CIK=0000102909

## Notes on GraphQL Support

Vanguard has no documented public GraphQL API as of 2026. The Vanguard GitHub organization (github.com/Vanguard-Group) contains zero public repositories. There is no developer.vanguard.com portal and no published OpenAPI or GraphQL schema. The conceptual schema in vanguard-group-schema.graphql models the fund and investment data domain based on:

- Vanguard's public fund product catalog (mutual funds, ETFs, money market funds)
- Publicly disclosed account types (brokerage, IRA, 401k, 403b)
- Advisor and institutional services documentation
- SEC regulatory filing data (13F-HR, N-PORT, N-CSR) which exposes fund holdings structures
- Standard investment industry data models (NSCC, DTCC, XBRL taxonomy)
