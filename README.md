# Awesome-Customer-Billing-Self-Service-Portal

## Top Customer Billing Self-Service Portal Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**  
*Focused on Subscription Management, Invoice Payment & Customer-Facing Billing Controls*  
**Last updated: March 2026**

This repository tracks notable **SaaS platforms** and **open-source projects** for **Customer Billing Self-Service Portals**. These tools give end customers a branded interface to manage their own billing—updating payment methods, viewing invoices, changing plans, and canceling subscriptions—reducing support burden while giving finance teams control over what customers can and cannot modify.

**Examples** include Stripe Customer Portal, Chargebee Customer Portal, Recurly Subscriber Portal, Maxio Customer Portal, Rebilly Customer Portal, and open-source alternatives like FOSSBilling and Invoice Ninja (the category leaders).

**Open-source emphasis**: This section highlights every major active project for self-hosted billing portals, open-source client management systems, and community-driven subscription portals—ideal for organizations seeking data sovereignty and predictable costs over percentage-of-revenue SaaS pricing. The open-source billing portal landscape is functional but bifurcated: hosting-focused tools like FOSSBilling offer complete client portals, while SaaS-focused platforms like Lago require more assembly.

Contributions welcome! Open an PR to add/update entries. Keep descriptions factual and link to official sites.

## Table of Contents
- [SaaS/Hosted Platforms](#saas-products)
- [Open-Source GitHub Projects](#open-source-github-projects)
- [How to Contribute](#how-to-contribute)
- [Disclaimer](#disclaimer)

## SaaS/Hosted Platforms

| Product | Description | Pricing (Starting) | Free Tier / Trial Limits |
|---------|-------------|-------------------|--------------------------|
| **[Stripe Customer Portal](https://stripe.com/)** | Hosted portal for customers to update payment methods, manage invoices, and view payment history. **Available only to paid Billing users**; you can test it in test mode before paying. Rates start at **0.7% of Billing volume** and **0.4% for one-time invoices** [citation:2][citation:10]. | 0.7% of Billing volume | No free tier for portal access; test mode available |
| **[Chargebee Customer Portal](https://www.chargebee.com/)** | Self-service portal within Chargebee's subscription platform. **Important limitation: prices of plans and add-ons cannot be overridden via Hosted pages or Customer portal**—price overrides only work in the admin dashboard [citation:1][citation:9]. | Included with Chargebee subscription (Flow PAYG from 0.80% of invoicing) | No free tier; trial via Chargebee signup |
| **[Recurly Subscriber Portal](https://recurly.com/)** | **Hosted subscriber portal with passwordless login** included in All-Access tier. Starter tier ($249/month + 0.9% of billing volume) covers core subscription billing but the self-serve portal features are positioned under All-Access [citation:3][citation:11]. | Starter: $249/month + 0.9% of billing volume | No free tier; trial via sales |
| **[Maxio Customer Portal](https://www.maxio.com/)** | Customer portal included in the **Grow tier ($599/month)**. Unlimited users at no additional charge. Transparent pricing bands with add-ons and modules customized to company needs [citation:5]. | Grow: $599/month | No free tier; trial via sales |
| **[Rebilly Customer Portal](https://www.rebilly.com/)** | Portal included in both Basic ($15/month) and Pro ($125/month) plans, with **unlimited team members** and **1% revenue fee**. 30-day free trial with no credit card required. Pricing is volume-based—lower rates at higher volume [citation:7]. | Basic: $15/month + 1% revenue fee; Pro: $125/month + 1% | **30-day free trial** (full product, no credit card) |

## Open-Source GitHub Projects

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[FOSSBilling](https://github.com/FOSSBilling/FOSSBilling)** | [![Stars](https://img.shields.io/github/stars/FOSSBilling/FOSSBilling?style=social&color=white)](https://github.com/FOSSBilling/FOSSBilling/stargazers) | **The most complete open-source billing client portal for hosting and service providers.** Free, open-source billing and client management with automated billing cycles, multi-currency support, and multiple payment gateways (PayPal, Stripe, others). The **client self-service portal** lets customers manage services, view and pay invoices, submit support tickets, and access account information 24/7. No licensing fees or per-client charges [citation:8][citation:18]. |
| **[Invoice Ninja](https://github.com/invoiceninja/invoiceninja)** | [![Stars](https://img.shields.io/github/stars/invoiceninja/invoiceninja?style=social&color=white)](https://github.com/invoiceninja/invoiceninja/stargazers) | Open-source invoicing platform with a **client portal** where customers can view and pay invoices directly. Supports **Single Sign-On (SSO) for the client portal** via a WordPress shortcode (`[invoiceninja_client_portal sso="true"]`), eliminating password entry. Includes quotes, recurring invoices, and payment tracking [citation:17][citation:23]. |
| **[Lago](https://github.com/getlago/lago)** | [![Stars](https://img.shields.io/github/stars/getlago/lago?style=social&color=white)](https://github.com/getlago/lago/stargazers) | Open-source metered billing and usage-based pricing platform with a **comprehensive customer portal** including usage analytics, invoice history, and subscription management. Supports real-time usage tracking, prepaid credits, graduated pricing, and multi-currency. The portal gives customers visibility into consumption-based billing—critical for usage-heavy SaaS [citation:22]. |

### Additional Strong Open-Source Options

| Project | Star Badge | Description |
|---------|------------|-------------|
| **[Cbox Billing](https://github.com/cboxdk/cbox-billing)** | [![Stars](https://img.shields.io/github/stars/cboxdk/cbox-billing?style=social&color=white)](https://github.com/cboxdk/cbox-billing/stargazers) | Self-hostable billing, metering, and entitlement platform with **self-service customer portal** and provider console. Laravel 13/PHP 8.4+. Features real-time usage metering with hard-limit enforcement, credit wallets, tax-aware invoicing, dunning, and hosted checkout/portal sessions. Includes Stripe and Mollie gateway adapters. All production dependencies permissively licensed . |
| **[PNLCS](https://github.com/Panelica/pnlcs)** | [![Stars](https://img.shields.io/github/stars/Panelica/pnlcs?style=social&color=white)](https://github.com/Panelica/pnlcs/stargazers) | Open-source WHMCS alternative (Laravel 13) for hosting billing with **full client portal** including hosting management (files, mail, databases, FTP, subdomains, DNS, cron, backups). Stripe, PayPal, and Authorize.Net gateways. 30 languages, 15 themes. Docker one-command deploy [citation:21]. |
| **[ITFlow](https://github.com/itflow-org/itflow)** | [![Stars](https://img.shields.io/github/stars/itflow-org/itflow?style=social&color=white)](https://github.com/itflow-org/itflow/stargazers) | Open-source PSA for MSPs with **client portal** for self-service quote/invoice/ticket management. Includes accounting, billing, finance dashboard, and documentation. Free alternative to ITGlue and Hudu [citation:24]. |
| **[itsm-modular](https://github.com/huanbv/itsm-modular)** | [![Stars](https://img.shields.io/github/stars/huanbv/itsm-modular?style=social&color=white)](https://github.com/huanbv/itsm-modular/stargazers) | Laravel 12 modular monolith with a dedicated **`Modules/CustomerPortal`** for self-service. Includes billing, invoices, payments, recurring billing, and CRM modules. Docker deployment with MySQL/PostgreSQL [citation:16][citation:28]. |

**Frameworks for building custom systems**: Combine **FOSSBilling** for a turnkey hosting client portal with payment gateways, **Invoice Ninja** for invoicing-centric portals with SSO, and **Lago** for usage-based billing visibility—all deployable via Docker without per-client or percentage-of-revenue fees. For SaaS-specific needs, **Cbox Billing** provides metering plus portal in a single self-hosted stack.

## How to Contribute

1. Fork the repo.
2. Add/edit entries in `README.md` (follow existing format).
3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.
4. Submit PR with a short explanation.

Star the repo if you find it useful!

## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.
- Customer billing portals handle payment credentials and financial data; enforce PCI DSS compliance (or use tokenized gateways), strong authentication, and audit logging for all self-service actions.
- **Self-service portal capabilities vary dramatically even within the same platform.** Stripe's portal is **paid-Billing-only**—legacy free users cannot access it [citation:2]. Chargebee explicitly **does not allow price overrides through the customer portal**; price changes require admin intervention [citation:1]. Recurly's passwordless portal is positioned under All-Access, not Starter [citation:3]. Maxio includes the portal only from the $599/month Grow tier [citation:5]. Open-source alternatives like **FOSSBilling** provide genuine client portals without per-client fees, but require self-hosting effort and lack the polish of commercial platforms. Always verify portal feature availability against your specific plan tier before committing.

---

**Made for billing administrators, subscription finance teams, and developers building self-service payment infrastructure.**  
Let's make customer billing portals more open, transparent, and customer-friendly.
