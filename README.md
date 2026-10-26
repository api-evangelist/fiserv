# Fiserv (fiserv)

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
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Fiserv is a global provider of financial services technology solutions, offering a wide range of products and services to help clients in the banking, payments, and wealth management industries.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/fiserv/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Banking
- Financial
- Payments
- Wealth Management

## Timestamps

- **Created:** 2025-02-17
- **Modified:** 2026-05-19

## APIs

### Fiserv CommerceHub API

The Fiserv CommerceHub API provides a unified RESTful interface for processing payments, managing tokens, verifying payment sources, and handling 3-D Secure authentication. CommerceHub enables merchants to accept payments through multiple channels including online, mobile, and in-app, with support for charges, pre-authorizations, captures, refunds, cancellations, and tokenization of payment credentials.

- **Human URL:** [https://developer.fiserv.com/product/CommerceHub](https://developer.fiserv.com/product/CommerceHub)

#### Tags

- 3-D Secure
- Commerce
- Payments
- Tokenization

#### Properties

- [Documentation](https://developer.fiserv.com/product/CommerceHub/docs/?path=docs/Resources/API-Documents/Use-Our-APIs.md)
- [OpenAPI](openapi/fiserv-commercehub-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fiserv-commercehub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-commercehub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fiserv CardPointe Gateway API

The CardPointe Gateway API provides a RESTful interface for integrating secure tokenization, payment processing, and reporting features into applications and websites. The API supports authorization, capture, void, refund, and inquiry operations, as well as customer profile management for storing payment credentials securely.

- **Human URL:** [https://developer.fiserv.com/product/CardPointe](https://developer.fiserv.com/product/CardPointe)

#### Tags

- Gateway
- Payments
- Point of Sale
- Tokenization

#### Properties

- [Documentation](https://developer.fiserv.com/product/CardPointe/docs/?path=docs%2FAPIs%2FCardPointeGatewayAPI.md)
- [OpenAPI](openapi/fiserv-cardpointe-gateway-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fiserv-cardpointe-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-cardpointe-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fiserv BankingHub API

The Fiserv BankingHub API provides RESTful access to core banking operations including account management, transactions, transfers, payments, and party (customer) management. BankingHub enables financial institutions and fintech partners to integrate account opening, fund transfers, payment processing, and customer data management into their applications.

- **Human URL:** [https://developer.fiserv.com/product/BankingHub](https://developer.fiserv.com/product/BankingHub)

#### Tags

- Accounts
- Banking
- Payments
- Transfers

#### Properties

- [Documentation](https://developer.fiserv.com/product/BankingHub/docs/?path=docs/get-started.md)
- [OpenAPI](openapi/fiserv-bankinghub-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fiserv-bankinghub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-bankinghub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fiserv CardDeveloper API

The Fiserv CardDeveloper API enables financial institutions and cardholders to manage card and account information through various touchpoints. The API supports account creation, card management, authorization management, transaction inquiry, limit management, and statement retrieval for credit and debit card programs.

- **Human URL:** [https://developer.fiserv.com/product/CardDeveloper](https://developer.fiserv.com/product/CardDeveloper)

#### Tags

- Accounts
- Authorizations
- Cards
- Statements

#### Properties

- [Documentation](https://developer.fiserv.com/product/CardDeveloper/docs/?path=docs/gettingstarted/getting-started.md)
- [OpenAPI](openapi/fiserv-carddeveloper-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/fiserv-carddeveloper.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-carddeveloper.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Fiserv Payment Events

Fiserv provides webhook-based event notifications across the payments lifecycle. Merchants can subscribe to webhooks to receive real-time notifications for key events including transaction status changes, settlement updates, dispute notifications, and checkout completions.

- **Human URL:** [https://docs.fiserv.dev/public/docs/webhooks-and-status-updates-checkout](https://docs.fiserv.dev/public/docs/webhooks-and-status-updates-checkout)

#### Tags

- Disputes
- Events
- Payments
- Webhooks

#### Properties

- [Documentation](https://docs.fiserv.dev/public/docs/webhooks-and-status-updates-checkout)
- [AsyncAPI](asyncapi/fiserv-payment-events-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/fiserv-bankinghub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-bankinghub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fiserv-carddeveloper.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-carddeveloper.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fiserv-cardpointe-gateway.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-cardpointe-gateway.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/fiserv-commercehub.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/fiserv-commercehub.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/Fiserv)
- [LinkedIn](https://www.linkedin.com/company/fiserv)
- [Website](https://www.fiserv.com/)
- [Documentation](https://developer.fiserv.com/)
- [Sign Up](https://developer.fiserv.com/)
- [JSON-LD](json-ld/fiserv-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [JSON Schema](json-schema/fiserv-payment-transaction-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/fiserv-account-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [Features](undefined)
- [L L Ms Txt](https://docs.fiserv.dev/llms.txt)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
