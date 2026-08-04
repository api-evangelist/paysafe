# Paysafe (paysafe)

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

Paysafe is an integrated payment platform providing businesses with REST APIs for online payments, digital wallets, prepaid cards, pay-by-cash processing, and merchant account management. The platform supports a broad range of payment methods including credit and debit cards, ACH/SEPA direct debit, alternative payment methods, PaysafeCash, PaysafeCard vouchers, and embedded digital wallet solutions. Paysafe specializes in high-risk and regulated industries and offers white-label merchant onboarding, 3D Secure authentication, recurring payment scheduling, and FX rates for global commerce.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/paysafe/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/paysafe/refs/heads/main/apis.yml)

## Tags

- Payments
- Digital Wallets
- Prepaid Cards
- Financial Services
- Fintech
- High-Risk Payments

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Paysafe Payments API

The core REST API to process payments from customers across multiple payment methods including credit and debit cards, bank transfers (BLIK, EPS, iDEAL, Interac e-Transfer, ACH, SEPA), cash vouchers (PaysafeCash, PaysafeCard, Openbucks), digital wallets (Apple Pay, Google Pay, PayPal, Skrill, Neteller, Venmo), and crypto. A single integration provides access to all supported methods with resource-oriented URLs, JSON-encoded responses, and standard HTTP status codes.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/payments-api/overview/](https://developer.paysafe.com/en/api-docs/payments-api/overview/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- Payments
- Cards
- ACH
- Direct Debit
- Wallets
- Alternative Payments

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/payments-api/overview/)
- [API Reference](https://developer.paysafe.com/en/api-docs/payments-api/api-reference/)
- [Getting Started](https://developer.paysafe.com/en/payments-api/)

### Paysafe 3D Secure API

The 3D Secure v2 API provides strong customer authentication (SCA) for card transactions in line with PSD2 mandates. Merchants can initiate device fingerprinting and authentication flows, look up authentication status by ID, and receive authentication results to include in downstream payment requests. Base path: /threedsecure/v2/accounts/{account_id}.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/3ds/using-the-api/api-endpoints/](https://developer.paysafe.com/en/api-docs/3ds/using-the-api/api-endpoints/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- 3D Secure
- Authentication
- Fraud Prevention
- Cards

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/3ds/using-the-api/api-endpoints/)
- [API Reference](https://developer.paysafe.com/en/api-docs/3ds/)

### Paysafe Payment Scheduler API

A REST API for creating and managing recurring payment plans and customer subscriptions. Merchants define billing plans (interval, amount, currency) and subscribe customers to them. Supports full CRUD for plans and subscriptions with JSON request/response format. Base path: /subscriptionsplans/v1/.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/payment-scheduler/overview/](https://developer.paysafe.com/en/api-docs/payment-scheduler/overview/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- Subscriptions
- Recurring Payments
- Plans
- Billing

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/payment-scheduler/overview/)
- [API Reference](https://developer.paysafe.com/en/api-docs/payment-scheduler/using-the-api/api-endpoints/)

### Paysafe Applications API

A REST API that allows platforms and payment facilitators to create white-labelled merchant onboarding experiences. Supports creating, updating, and submitting merchant applications, uploading supporting documents, retrieving terms and conditions, and receiving webhook notifications on status changes. Base path: /merchant/v1/applications. Supports batch onboarding for multiple merchants.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/applications-api/overview/](https://developer.paysafe.com/en/api-docs/applications-api/overview/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- Merchant Onboarding
- Applications
- Platforms
- PayFac

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/applications-api/overview/)
- [API Reference](https://developer.paysafe.com/en/applications-api/)

### Paysafe Embedded Wallets API

A REST API enabling platforms to embed digital wallet functionality directly into their products. Customers can add funds, spend, withdraw, and manage virtual and physical prepaid cards. Supports card creation and management, card tokenization for Google Pay, Apple Pay, and Samsung Pay, and crypto on-ramp for purchasing cryptocurrencies with fiat via Skrill. Bearer JWT authentication required. Base path: /digitalwallets/v1/profile.

- **Human URL:** [https://docs.paysafe.com/docs/embedded-wallets](https://docs.paysafe.com/docs/embedded-wallets)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- Digital Wallets
- Embedded Finance
- Prepaid
- Crypto

#### Properties

- [Documentation](https://docs.paysafe.com/docs/embedded-wallets)
- [API Reference](https://docs.paysafe.com/docs/embedded-wallets/prepaid-cards/overview)

### PaysafeCard REST API

The PaysafeCard REST API enables online merchants to accept PaysafeCard prepaid voucher payments, payouts, and refunds. PaysafeCard is a global prepaid payment method available in 43+ countries, using a 16-digit PIN system. The API also provides settlement report data for financial reconciliation. Documented in API Blueprint format with English and German specifications.

- **Human URL:** [https://www.paysafecard.com/fileadmin/api/](https://www.paysafecard.com/fileadmin/api/)
- **Base URL:** `https://api.paysafecard.com`

#### Tags

- Prepaid
- Vouchers
- Pay-by-Cash
- PaysafeCard

#### Properties

- [Documentation](https://www.paysafecard.com/fileadmin/api/)
- [GitHub Repository](https://github.com/paysafecard/api-documentation)

### Paysafe PayFac Sub-merchant API

A REST API for payment facilitators to onboard sub-merchants for payment processing capabilities. Enables platforms acting as PayFacs to manage sub-merchant accounts under their master merchant account, controlling payment processing features and limits for each sub-merchant.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/](https://developer.paysafe.com/en/api-docs/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- PayFac
- Sub-merchants
- Onboarding
- Platforms

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/)

### Paysafe Merchant Termination Inquiry API

A compliance API that screens prospective sub-merchants against the Mastercard MATCH Pro and Visa terminated merchant databases before onboarding. Helps payment facilitators identify high-risk merchants and comply with card network requirements for sub-merchant due diligence.

- **Human URL:** [https://developer.paysafe.com/en/api-docs/](https://developer.paysafe.com/en/api-docs/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- Risk
- Compliance
- Sub-merchants
- MATCH
- Visa

#### Properties

- [Documentation](https://developer.paysafe.com/en/api-docs/)

### Paysafe FX Rates API

A value-added REST API providing foreign exchange rate data to support multi-currency payment processing and dynamic currency conversion. Used in conjunction with the Payments API to present pricing to customers in their local currency.

- **Human URL:** [https://developer.paysafe.com/en/fx-rates-api/](https://developer.paysafe.com/en/fx-rates-api/)
- **Base URL:** `https://api.paysafe.com`

#### Tags

- FX
- Currency
- Exchange Rates
- International

#### Properties

- [Documentation](https://developer.paysafe.com/en/fx-rates-api/)

## Common Properties

- [Website](https://www.paysafe.com)
- [Portal](https://developer.paysafe.com/en/)
- [Documentation](https://developer.paysafe.com/en/api-docs/)
- [Documentation](https://docs.paysafe.com/)
- [Changelog](https://developer.paysafe.com/en/support/reference-information/documentation-changelog/)
- [Authentication](https://developer.paysafe.com/en/support/reference-information/rest-api-architecture/)
- [Dashboard](https://merchant.paysafe.com/portal)
- [Sandbox](https://merchant.test.paysafe.com/portal/login)
- [Privacy Policy](https://www.paysafe.com/en/paysafegroup/comprehensive-privacy-policy/)
- [Contact](https://www.paysafe.com/en/information/contact/)
- [GitHub Organization](https://github.com/paysafegroup)
- [GitHub Organization](https://github.com/paysafecard)
- [GitHub Repository](https://github.com/paysafecard/api-documentation)
- [Plans](plans/paysafe-plans-pricing.yml)
- [Rate Limits](rate-limits/paysafe-rate-limits.yml)
- [Fin Ops](finops/paysafe-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)

## Maintainers

**FN:** API Evangelist
**Email:** info@apievangelist.com
**URL:** http://apievangelist.com
