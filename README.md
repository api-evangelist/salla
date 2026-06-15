# Salla (salla)

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
