# Axos Bank (axos-bank)

Axos Bank is a branchless, digital-first federal savings bank chartered and regulated by the U.S. Office of the Comptroller of the Currency (OCC) and a member of the FDIC. Founded in 2000 as Bank of Internet USA and rebranded Axos in 2018, it is the primary banking subsidiary of Axos Financial, Inc. (NYSE: AX), a Delaware financial holding company headquartered in San Diego, California with roughly $29 billion in consolidated assets. Axos serves consumer and commercial customers online, and runs a first-party developer / Banking-as-a-Service program.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/axos-bank/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/axos-bank/refs/heads/main/apis.yml)

## Open-Finance / API Posture

Axos operates a real first-party developer program (the "API Store") at [www.axosbank.com/developer](https://www.axosbank.com/developer), with a public API catalog describing four API product families. However, the program is **partner-gated**, not self-serve:

- Access requires contacting the Axos API team, who then grant sandbox/test credentials and later production credentials.
- Authentication is **OAuth 2.0** token-based, with API keys issued through a per-user developer dashboard.
- **No publicly downloadable OpenAPI/Swagger specification** is published; endpoint and schema documentation is provided only after onboarding.
- No documented first-party **FDX (Financial Data Exchange)** participation and no published **CFPB Section 1033** data-access posture were found. Consumer-permissioned data sharing, where it exists, is understood to run through third-party aggregators rather than a documented first-party open-banking API.

The dedicated `developer.axosbank.com` subdomain was returning HTTP 522 (Cloudflare origin timeout) at review time; the canonical, live mirror of the same content is served under `www.axosbank.com/developer` (HTTP 200).

## Tags

- Financial Services
- Banking
- United States
- Banking-as-a-Service
- Open Finance
- Payments
- Digital Bank

## Timestamps

- **Created:** 2026-07-23
- **Modified:** 2026-07-23

## APIs

### Axos Account Enrollment API

Submit new account applications and open new Axos deposit and commercial accounts programmatically.

- **Human URL:** [https://www.axosbank.com/developer/api-catalog](https://www.axosbank.com/developer/api-catalog)

#### Properties

- [Documentation](https://www.axosbank.com/developer)
- [API Reference](https://www.axosbank.com/developer/api-catalog)

### Axos Account Maintenance API

Check balances, manage stop payments, update account information, close accounts, and move funds between deposit and commercial accounts.

- **Human URL:** [https://www.axosbank.com/developer/api-catalog](https://www.axosbank.com/developer/api-catalog)

#### Properties

- [Documentation](https://www.axosbank.com/developer)
- [API Reference](https://www.axosbank.com/developer/api-catalog)

### Axos Payment Solutions API

Enable fund transfers between Axos accounts and track payment status, including domestic wire origination.

- **Human URL:** [https://www.axosbank.com/developer/api-catalog](https://www.axosbank.com/developer/api-catalog)

#### Properties

- [Documentation](https://www.axosbank.com/developer)
- [API Reference](https://www.axosbank.com/developer/api-catalog)

### Axos Account Reporting API

Access transaction reports, query company data, and identify client accounts for data-driven reporting.

- **Human URL:** [https://www.axosbank.com/developer/api-catalog](https://www.axosbank.com/developer/api-catalog)

#### Properties

- [Documentation](https://www.axosbank.com/developer)
- [API Reference](https://www.axosbank.com/developer/api-catalog)

## Common Properties

- [Website](https://www.axosbank.com/)
- [Developer Portal](https://www.axosbank.com/developer)
- [Documentation](https://www.axosbank.com/developer/api-catalog)
- [Support](https://www.axosbank.com/developer/contact)
- [LinkedIn](https://www.linkedin.com/company/axosbank)
- [Privacy Policy](https://www.axosbank.com/legal/privacy)
- [Terms of Service](https://www.axosbank.com/legal)
- [Security Center](https://www.axosbank.com/legal/security-center)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
