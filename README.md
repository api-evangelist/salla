# Salla (salla)

Salla is a Saudi Arabia-based e-commerce platform — often called the Shopify of the Middle East — that lets merchants launch, operate, and grow Arabic-first online stores without code. Founded in 2016 in Makkah by Nawaf Hariri and Salman Butt, Salla now powers more than 80,000 active stores. The platform exposes a Merchant REST API (`https://api.salla.dev/admin/v2`), an OAuth 2.0 Partners authorization service, signed webhooks for the full storefront lifecycle, a Shipping and Fulfillment app contract, the Twilight theme engine and JavaScript SDK, the Salla CLI, and official starter kits for PHP/Laravel and Node.js/Express. Backed by Sanabil (PIF), STV, Investcorp, Vision Ventures, and Raed Ventures, Salla raised a $130M pre-IPO round in 2024.

**URL:** [Visit APIs.json](https://raw.githubusercontent.com/api-evangelist/salla/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags

Arabic, E-Commerce, GCC, Headless Commerce, Merchant, MENA, Online Stores, Retail, Saudi Arabia, SMB, Storefront

## Timestamps

- **Created:** 2026-05-24
- **Modified:** 2026-05-24

## APIs

### Salla Merchant API
RESTful endpoints for products, orders, customers, branches, brands, categories, coupons, currencies, languages, taxes, shipping zones, shipments, abandoned carts, marketing, and store configuration. Base URL `https://api.salla.dev/admin/v2`. OAuth 2.0 bearer authentication.

**Human URL:** [https://docs.salla.dev/421117m0](https://docs.salla.dev/421117m0)

- [Documentation](https://docs.salla.dev/421117m0)
- [OpenAPI](openapi/salla-merchant-api-openapi.yml)
- [JSON Schema — Product](json-schema/salla-product-schema.json)
- [JSON Schema — Order](json-schema/salla-order-schema.json)
- [JSON Schema — Customer](json-schema/salla-customer-schema.json)
- [JSON-LD Context](json-ld/salla-context.jsonld)
- [Example — List Products](examples/salla-list-products-example.json)
- [Example — Create Order](examples/salla-create-order-example.json)
- [Naftiko Capability — Products](capabilities/merchant-products.yaml)
- [Naftiko Capability — Orders](capabilities/merchant-orders.yaml)
- [Naftiko Capability — Customers](capabilities/merchant-customers.yaml)
- [Naftiko Capability — Categories](capabilities/merchant-categories.yaml)
- [Naftiko Capability — Brands](capabilities/merchant-brands.yaml)
- [Naftiko Capability — Shipping](capabilities/merchant-shipping.yaml)

### Salla Apps API
OAuth 2.0 authorization server at `https://accounts.salla.sa` — handles the merchant consent flow, access and refresh token exchange (14-day access, 1-month refresh window), and merchant user info lookup for apps installed from the Salla Partners Portal.

**Human URL:** [https://docs.salla.dev/421118m0](https://docs.salla.dev/421118m0)

- [Documentation](https://docs.salla.dev/421118m0)
- [OpenAPI](openapi/salla-apps-api-openapi.yml)
- [Naftiko Capability — OAuth](capabilities/apps-oauth.yaml)
- [Naftiko Capability — Subscriptions](capabilities/apps-subscriptions.yaml)

### Salla Shipping and Fulfillment API
REST contract that logistics providers implement to plug a courier into the Salla shipment flow — list and update zones, companies, and shipments; receive `shipment.creating` / `shipment.created` / `shipment.cancelled` webhooks.

**Human URL:** [https://docs.salla.dev/5394234e0](https://docs.salla.dev/5394234e0)

- [OpenAPI](openapi/salla-shipping-fulfillment-api-openapi.yml)
- [Naftiko Capability — Shipments](capabilities/shipping-shipments.yaml)
- [Naftiko Capability — Zones](capabilities/shipping-zones.yaml)

### Salla Webhooks
Server-to-server event delivery covering order, product, customer, shipping, shipment, store branch, category, brand, abandoned cart, coupon, invoice, special offer, and review lifecycle events. HMAC SHA-256 signed via `X-Salla-Security-Strategy` / `X-Salla-Signature` headers (or token strategy with `Authorization`). Supports per-subscription conditional rules.

**Human URL:** [https://docs.salla.dev/421119m0](https://docs.salla.dev/421119m0)

- [Documentation](https://docs.salla.dev/421119m0)
- [AsyncAPI](openapi/salla-webhooks-asyncapi.yml)

### Salla Twilight SDK
JavaScript SDK and Twig-based theme engine for the storefront. Helper methods, REST proxies, and a library of pre-built web components (login, search, product display, cart, checkout) for merchant themes and embedded apps.

**Human URL:** [https://docs.salla.dev/twilight](https://docs.salla.dev/twilight)

## Common Resources

- [Portal](https://salla.com)
- [Developer Site](https://salla.dev)
- [Partners Documentation](https://docs.salla.dev/)
- [Getting Started](https://docs.salla.dev/421117m0)
- [Salla Partners Console](https://salla.partners)
- [Pricing](https://salla.com/pricing)
- [Status Page](https://status.salla.sa/)
- [Merchant API Changelog](https://docs.salla.dev/421127m0)
- [GitHub Organization](https://github.com/SallaApp)
- [Salla Postman Workspace](https://www.postman.com/salla-app/salla-e-commerce-platform/overview)
- [Merchant APIs v2.6.7 Postman Collection](https://www.postman.com/salla-app/salla-e-commerce-platform/collection/a2rh372/merchant-apis-v2-6-7)
- [Salla CLI](https://github.com/SallaApp/Salla-CLI)
- [Laravel Starter Kit](https://github.com/SallaApp/laravel-starter-kit)
- [Express.js Starter Kit](https://github.com/SallaApp/express-starter-kit)
- [OAuth2 Merchant Client (PHP)](https://github.com/SallaApp/oauth2-merchant)
- [Passport OAuth Strategy (Node.js)](https://github.com/SallaApp/passport-strategy)
- [ZATCA E-Invoicing QR (PHP)](https://github.com/SallaApp/ZATCA)
- [Spectral Rules](rules/salla-rules.yml)
- [Vocabulary](vocabulary/salla-vocabulary.yml)
- [Plans and Pricing](plans/salla-plans-pricing.yml)
- [Rate Limits](rate-limits/salla-rate-limits.yml)
- [FinOps Profile](finops/salla-finops.yml)

## Features

- Arabic-First No-Code Store Builder
- Salla Merchant API (`https://api.salla.dev/admin/v2`)
- OAuth 2.0 Partners Authorization with 14-day access tokens, 1-month refresh window
- HMAC SHA-256 signed webhooks with per-subscription conditional rules
- Twilight Theme Engine and JavaScript SDK
- Salla CLI for app and theme scaffolding and publishing
- Shipping App contract for courier integrations
- ZATCA Phase-1 / Phase-2 e-invoicing support
- Embedded SDK and the Salla App Store
- Native Saudi/GCC payments (mada, STC Pay, Apple Pay, Tabby, Tamara, STC Bank) and logistics (Aramex, SMSA, J&T, DHL)

## Use Cases

- Custom merchant apps published in the Salla App Store
- ERP, accounting, and CRM integrations
- Custom Twilight themes and headless storefronts
- Shipping provider onboarding
- Marketing and abandoned-cart automation
- AI shopping assistants and merchant copilots
- ZATCA compliance

## Solutions

- **Sellers** — merchants launching online stores with Arabic-first UX, regional payments, and built-in logistics
- **Partners** — developers and agencies building apps, themes, and integrations distributed through the Salla Partners Portal
- **Shipping Companies** — logistics providers reaching 80,000+ merchants by implementing the Salla Shipping App contract
- **Enterprise** — larger brands with custom themes, dedicated infrastructure, and bespoke commercial terms

## Maintainer

- **FN:** Kin Lane
- **Email:** info@apievangelist.com
- **X:** [@apievangelist](https://twitter.com/apievangelist)
- **URL:** https://apievangelist.com
