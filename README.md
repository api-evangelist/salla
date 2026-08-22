# Salla (salla)

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

Salla is a Saudi Arabia-based e-commerce platform — often called the Shopify of the Middle East — that lets merchants launch, operate, and grow Arabic-first online stores without code. Founded in 2016 in Makkah by Nawaf Hariri and Salman Butt, Salla now powers more than 80,000 active stores. The platform exposes a Merchant REST API (https://api.salla.dev/admin/v2), an OAuth 2.0 Partners authorization service, signed webhooks for the full storefront lifecycle, a Shipping and Fulfillment app contract, the Twilight theme engine and JavaScript SDK, the Salla CLI, and official starter kits for PHP/Laravel and Node.js/Express. Backed by Sanabil (PIF), STV, Investcorp, Vision Ventures, and Raed Ventures, Salla raised a $130M pre-IPO round in 2024.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/salla/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/salla/refs/heads/main/apis.yml)

## Scope

- **Position:** Producing
- **Access:** 3rd-Party

## Tags

- Arabic
- E-Commerce
- GCC
- Headless Commerce
- Merchant
- MENA
- Online Stores
- Retail
- Saudi Arabia
- SMB
- Storefront

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Salla Merchant API

RESTful endpoints purpose-built for secure, fast, and easy access to Merchant data. Covers products, orders, customers, branches, brands, categories, coupons, currencies, languages, taxes, shipping zones, shipments, abandoned carts, marketing, and store configuration. All requests use the base URL https://api.salla.dev/admin/v2 and are authenticated with an OAuth 2.0 bearer token issued via Salla Partners.

- **Human URL:** [https://docs.salla.dev/421117m0](https://docs.salla.dev/421117m0)
- **Base URL:** `https://api.salla.dev/admin/v2`

#### Tags

- E-Commerce
- Merchant
- Orders
- Products
- Customers

#### Properties

- [Documentation](https://docs.salla.dev/421117m0)
- [Documentation](https://docs.salla.dev/5394168e0)
- [Documentation](https://docs.salla.dev/5394147e0)
- [OpenAPI](openapi/salla-merchant-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salla-merchant-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-merchant-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/salla-product-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salla-order-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/salla-customer-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [J S O N- L D](json-ld/salla-context.jsonld)
- [Example](examples/salla-list-products-example.json)
- [Example](examples/salla-create-order-example.json)

### Salla Apps API

Manages app settings, OAuth 2.0 authorization flow, access and refresh tokens, merchant user info, subscription lifecycle, and app event handling for apps installed from the Salla Partners Portal. OAuth endpoints live at https://accounts.salla.sa/oauth2/{auth,token,user/info}.

- **Human URL:** [https://docs.salla.dev/421118m0](https://docs.salla.dev/421118m0)
- **Base URL:** `https://accounts.salla.sa`

#### Tags

- Apps
- E-Commerce
- OAuth
- Subscriptions

#### Properties

- [Documentation](https://docs.salla.dev/421118m0)
- [OpenAPI](openapi/salla-apps-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salla-apps-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-apps-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salla Shipping and Fulfillment API

Enables shipping companies and fulfillment partners to manage and track shipments, shipping zones, pickup branches, and courier integrations for Salla merchant stores. Implements the Shipping App contract that Salla calls into when a merchant creates or cancels a shipment.

- **Human URL:** [https://docs.salla.dev/5394234e0](https://docs.salla.dev/5394234e0)
- **Base URL:** `https://api.salla.dev/admin/v2`

#### Tags

- E-Commerce
- Fulfillment
- Shipping
- Shipments

#### Properties

- [Documentation](https://docs.salla.dev/5394234e0)
- [Documentation](https://docs.salla.dev/5394248e0)
- [OpenAPI](openapi/salla-shipping-fulfillment-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/salla-shipping-fulfillment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-shipping-fulfillment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salla Webhooks

Server-to-server event delivery covering order, product, customer, shipping, shipment, store branch, category, brand, abandoned cart, coupon, invoice, special offer, and review lifecycle events. Payloads are signed via HMAC SHA-256 — X-Salla-Security-Strategy and X-Salla-Signature headers (or token strategy with Authorization header) — and developers can attach conditional rules per subscription.

- **Human URL:** [https://docs.salla.dev/421119m0](https://docs.salla.dev/421119m0)

#### Tags

- E-Commerce
- Events
- Webhooks

#### Properties

- [Documentation](https://docs.salla.dev/421119m0)
- [Documentation](https://docs.salla.dev/433804m0)
- [AsyncAPI](openapi/salla-webhooks-asyncapi.yml) — [AsyncAPI Specification](https://www.asyncapi.com/docs/reference/specification/latest)
- [Postman Collection](collections/salla-apps-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-apps-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salla-merchant-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-merchant-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salla-shipping-fulfillment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-shipping-fulfillment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Salla Twilight SDK

JavaScript SDK and Twig-based theme engine for the storefront. Provides helper methods and REST proxies that let merchant themes and embedded components communicate with the Salla backend, plus a library of pre-built web components (login, search, product display, cart, checkout).

- **Human URL:** [https://docs.salla.dev/twilight](https://docs.salla.dev/twilight)

#### Tags

- E-Commerce
- Storefront
- SDK
- Themes

#### Properties

- [Documentation](https://docs.salla.dev/twilight)
- [SDK](https://github.com/SallaApp/theme-raed)
- [Postman Collection](collections/salla-apps-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-apps-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salla-merchant-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-merchant-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/salla-shipping-fulfillment-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/salla-shipping-fulfillment-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Arazzo Workflows](arazzo/) — [Arazzo Specification](https://spec.openapis.org/arazzo/latest.html)
- [Portal](https://salla.com)
- [Documentation](https://salla.dev)
- [Documentation](https://docs.salla.dev/)
- [Getting Started](https://docs.salla.dev/421117m0)
- [Sign Up](https://salla.partners/login)
- [Console](https://salla.partners)
- [Pricing](https://salla.com/pricing)
- [Terms of Service](https://salla.com/terms)
- [Privacy Policy](https://salla.com/privacy)
- [Blog](https://salla.com/blog)
- [Status Page](https://status.salla.sa/)
- [Support](mailto:support@salla.dev)
- [Changelog](https://docs.salla.dev/421127m0)
- [GitHub Organization](https://github.com/SallaApp)
- [Documentation](https://www.postman.com/salla-app/salla-e-commerce-platform/overview)
- [Documentation](https://www.postman.com/salla-app/salla-e-commerce-platform/collection/a2rh372/merchant-apis-v2-6-7)
- [YouTube](https://www.youtube.com/@sallaapp)
- [Twitter](https://twitter.com/sallaApp)
- [LinkedIn](https://www.linkedin.com/company/salla-app)
- [C L I](https://github.com/SallaApp/Salla-CLI)
- [SDK](https://github.com/SallaApp/laravel-starter-kit)
- [SDK](https://github.com/SallaApp/express-starter-kit)
- [SDK](https://github.com/SallaApp/oauth2-merchant)
- [SDK](https://github.com/SallaApp/passport-strategy)
- [SDK](https://github.com/SallaApp/webhook-actions-js)
- [SDK](https://github.com/SallaApp/ZATCA)
- [Tools](https://github.com/SallaApp/theme-raed)
- [Tools](https://github.com/SallaApp/twilight-vscode-extension)
- [Tools](https://github.com/SallaApp/embedded-sdk-playground)
- [Tools](https://github.com/SallaApp/store-events-tracker-starter-kit)
- [Forum](https://t.me/sallaDevelopers)
- [Spectral Rules](rules/salla-rules.yml)
- [Vocabulary](vocabulary/salla-vocabulary.yml)
- [Plans](plans/salla-plans-pricing.yml)
- [Rate Limits](rate-limits/salla-rate-limits.yml)
- [Fin Ops](finops/salla-finops.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [Solutions](undefined)

## Maintainers

**FN:** Kin Lane
**Email:** info@apievangelist.com
**URL:** https://apievangelist.com
