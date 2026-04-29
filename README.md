# CRS Credit API (crs-credit-api)

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
