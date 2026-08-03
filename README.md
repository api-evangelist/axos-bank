# Axos Bank (axos-bank)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
