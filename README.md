# CRS Credit API (crs-credit-api)

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

CRS Credit API delivers credit data-as-a-service for fast, compliant financial decisioning. The platform aggregates consumer and business credit, identity, fraud, and public records data from major bureaus (Equifax, Experian, TransUnion, LexisNexis, CIC, PitchPoint) through a single contract and developer interface.

**APIs.yml URL:** https://raw.githubusercontent.com/api-evangelist/crs-credit-api/refs/heads/main/apis.yml

## Scope

- **Type:** Contract
- **Position:** Consuming
- **Access:** 3rd-Party

## Tags

Credit, Consumer Credit, Business Credit, Identity, Fraud, Data

## APIs

### CRS Credit Data API

Single-contract API providing access to consumer and business credit reports across major bureaus (Equifax, Experian, TransUnion). Supports soft and hard credit pulls, FICO and Vantage scoring models, and public record data.

- Documentation: https://crscreditapi.redoc.ly/
- Sandbox base: https://api-sandbox.stitchcredit.com

### CRS Credit Monitoring API

API powering the eCredit Monitoring service for continuous consumer credit monitoring including alerts on credit profile changes.

- Documentation: https://crsecreditmonitoringapi.redoc.ly/

### CRS Data Furnishing API

API for furnishing consumer or business data back to credit bureaus.

- Documentation: https://crscreditapi.redoc.ly/developer-portal/data-furnishing/

## Features

- Multi-bureau coverage (Equifax, Experian, TransUnion, LexisNexis, CIC, PitchPoint)
- Soft and hard credit pulls
- FICO and Vantage credit score models
- Identity verification and fraud signals
- Public records (bankruptcies, liens, judgments)
- JSON, XML, HTML5, and PDF response formats
- Bearer token authentication over HTTPS
- SDK examples in Ruby, Python, JavaScript, Java, Node.js, Go, PHP, .NET, and cURL

## Use Cases

- Loan underwriting and credit decisioning
- Tenant screening and rental applications
- B2B business credit and trade-line decisioning
- KYC and identity verification at onboarding
- Consumer credit monitoring and alerts

## Maintainers

- Kin Lane (kin@apievangelist.com)
