<!--
  Awesome-Promotion-Management
  Curated list of open-source and SaaS platforms for promotion management, loyalty programs,
  coupons, vouchers, gift cards, incentives, referrals, and personalized offers.
  Keywords: promotion management, loyalty platform, coupon engine, voucher system, referral program,
  trade promotion, open source loyalty, SaaS promotion software, discounts, customer incentives
-->

<div align="center">
  <img src="assets/banner.svg" alt="Awesome-Promotion-Management banner — promotions, loyalty, coupons, vouchers, incentives and offers" width="100%" />
</div>

# 🎉 Awesome-Promotion-Management

> A curated, continuously updated list of the best **promotion management platforms**, **loyalty programs**, **coupon & voucher engines**, **gift cards**, **referral programs**, **incentives**, and **personalized offers** — with a primary focus on **open-source software**.

## 📚 Table of Contents

- [Top Promotion Management Platforms](#top-promotion-management-platforms)
- [SaaS / Hosted Platforms](#saas--hosted-platforms)
- [Open-Source Softwares](#open-source-softwares)
- [Quick Start Recommendations](#quick-start-recommendations)
- [Contributing](#contributing)

## 🏆 Top Promotion Management Platforms

A curated list of leading platforms for promotion management, loyalty programs, vouchers, coupons, incentives, and personalized offers.  
**Primary focus: open-source software.**

Commercial / hosted platforms are listed separately for completeness. Open-source alternatives and community tools are emphasized throughout.

---

## 💼 SaaS / Hosted Platforms

*Sorted by company size (annual revenue / ARR) — descending.*

| Platform | Pricing (Starting Tier) | Free Tier / Free Trial | Company Size (Revenue / Valuation) | Description | Key Focus |
|----------|-------------------------|------------------------|-----------------------------------|-------------|-----------|
| **[Salesforce Promotion Management](https://www.salesforce.com/)** (Consumer Goods Cloud / Trade Promotion Management) | $275/user/mo (billed annually) | Free trial: 30 days (no credit card) | **$41.5B** revenue (FY2026) | Trade promotion planning, execution, and monitoring within Salesforce. Templates, tactics, product inclusion, spend planning, and calendar views for CPG and retail. | Trade promotions & account planning |
| **[Comarch Loyalty](https://www.comarch.com/)** | Custom — est. from ~€420/mo | None — no free tier or trial | **~$430M** revenue (PLN 1.71B, 2024) | Complete loyalty management suite with rules engine, promotions, AI personalization, receipt scanning, and multi-channel support. Long track record in retail and multi-industry programs. | Full-stack loyalty management |
| **[Capillary Technologies](https://www.capillarytech.com/)** | Custom — ~$3K–$30K+/mo (~$100K+/yr baseline) | None — 7-day trial available via Shopify app | **~$88–95M** revenue (FY25/26); IPO 2025, prior valuation ~$287M | AI-powered engagement and experiential loyalty platform. Points, tiers, gamification, predictive engagement, and omnichannel programs. Powers many large global loyalty schemes. | Enterprise loyalty + engagement |
| **[Talon.One](https://www.talon.one/)** | Custom — from ~€1,500/mo baseline (typical annual deals ~$49K) | None — no free tier or trial; PoC/demo via sales | **~€60M** ARR (est. 2025/26); $135M raised (2025) | Powerful incentives engine that unifies loyalty, promotions, and gamification. Real-time decisioning, personalized offers, bundles, referrals, and enterprise-scale rule execution (sub-50ms). | Omnichannel promotions + loyalty at scale |
| **[Eagle Eye](https://eagleeye.com/)** | Custom (enterprise) | None — no public free tier or trial; demo via sales | **£46.7M** revenue / £44.5M ARR (FY2026); LSE: EYE | Highly scalable, API-first loyalty and personalization platform. Real-time offer execution, wallets, promotion budgets, and omnichannel rewards. Trusted by major retailers. | Enterprise retail loyalty & personalization |
| **[Annex Cloud](https://www.annexcloud.com/)** | Custom — $50K–$250K+/yr | None — no free tier; sandbox/trial on request | **~$41M** ARR (acq. by Edited Capital, 2025) | Enterprise Loyalty Experience Platform with gamification, badges, referrals, advanced segmentation, omnichannel experiences, and progressive profiling. | Enterprise loyalty experience |
| **[SessionM](https://www.sessionm.com/)** (Capillary) | Custom — est. $200K+/yr | None — no free tier or trial | **~$35M** ARR; acq. by Mastercard ~$215M (2019), sold to Capillary (2026) | Points, tiers, incentives, and lifecycle loyalty management. Strong rules engine, status management, and integration with CRM for personalized rewards. | Points/tiers & behavioral loyalty |
| **[Antavo](https://antavo.com/)** | Custom — from ~$30K/yr | None — no free tier or trial | **~$18M** ARR (est.); ~$12M total funding | Advanced AI-powered loyalty and incentives platform. Custom currencies, visual tier builders, gamification, challenges, referrals, and promotions beyond discounts. | Flexible modern loyalty programs |
| **[Voucherify](https://www.voucherify.io/)** | €169/mo (Startup plan) | Free tier: €0 with up to 1,000 API calls/mo · 60-day free trial | **~$9.6M** ARR (est.); bootstrapped | API-first promotion and loyalty engine for coupons, cart promotions, gift vouchers, referrals, and loyalty campaigns. Strong validation rules, tiers, and distribution capabilities. | Flexible discount & loyalty campaigns |
| **[Open Loyalty](https://www.openloyalty.io/)** | Custom — platform fee + per-MAU allowance | None — no free tier or trial | Small — part of OEX Group (group revenue €277M) | Headless, API-first loyalty engine with gamification, campaigns, multi-tenancy, and enterprise features. Strong for building custom loyalty experiences. | Headless loyalty platform |

---

## 🧩 Open-Source Softwares

Fully production-grade open-source promotion and loyalty engines comparable to enterprise platforms are limited, but several solid self-hostable options, engines, and accelerators exist. Many teams combine these with e-commerce platforms or custom rule engines.

### ⚙️ Core Frameworks & Loyalty / Promotion Engines

*Sorted by GitHub stars — descending.*

| Project | Description | License | Notes |
|---------|-------------|---------|-------|
| **[zwpro/coupons](https://github.com/zwpro/coupons)** [![GitHub Stars](https://img.shields.io/github/stars/zwpro/coupons?style=social&color=white)](https://github.com/zwpro/coupons/stargazers) | Complete food-delivery coupon sharing platform for Meituan / Ele.me (WeChat mini-program + admin backend, CPS commission model). | Apache-2.0 | Coupon distribution app, strong community adoption |
| **[fuint](https://github.com/fushengqian/fuint)** [![GitHub Stars](https://img.shields.io/github/stars/fushengqian/fuint?style=social&color=white)](https://github.com/fushengqian/fuint/stargazers) | Open-source member marketing system with coupons, stored-value cards, points, tiers, and online/offline integration. Spring Boot + UniApp. Suitable for retail stores. | Open source | Store membership + marketing suite |
| **[VoucherVault](https://github.com/l4rm4nd/VoucherVault)** [![GitHub Stars](https://img.shields.io/github/stars/l4rm4nd/VoucherVault?style=social&color=white)](https://github.com/l4rm4nd/VoucherVault/stargazers) | Django web app to store and manage vouchers, coupons, loyalty cards, and gift cards digitally. PWA, offline support, expiry notifications, QR/barcodes, multi-user. | Open source | Personal/business voucher & loyalty card manager |
| **[refref](https://github.com/amicalhq/refref)** [![GitHub Stars](https://img.shields.io/github/stars/amicalhq/refref?style=social&color=white)](https://github.com/amicalhq/refref/stargazers) | Open-source referral & affiliate marketing platform. Launch a self-hosted referral program in minutes — campaigns, links, rewards, and analytics. | AGPL-3.0 | Referral programs without a SaaS dependency |
| **[OfferKit](https://github.com/offerkit/offerkit)** [![GitHub Stars](https://img.shields.io/github/stars/offerkit/offerkit?style=social&color=white)](https://github.com/offerkit/offerkit/stargazers) | Agent-first, self-hostable open-source promotion engine for coupons, loyalty, gift cards, referrals, and customer segments. Discount engine, stackable redemptions, points ledger, and JSON Logic rules. | MIT | Strong modern promotion/loyalty engine |
| **[Stampee](https://github.com/danlim26/stampee)** [![GitHub Stars](https://img.shields.io/github/stars/danlim26/stampee?style=social&color=white)](https://github.com/danlim26/stampee/stargazers) | Free, open-source, self-hostable digital loyalty / stamp card platform for small businesses (cafés, salons, local shops). Owner dashboard, campaigns, staff accounts. | MIT | Lightweight digital stamp cards |
| **[Open Loyalty (Community / older editions)](https://github.com/)** | Originally open-source headless loyalty platform (PHP/Symfony). Features members, campaigns, points, tiers, and gamification. Current commercial version is hosted; older community code remains available for self-hosting/forking. | Open source (older versions) | Historical open core; check current status |
| **[Voucherify Open Source Loyalty Accelerator](https://www.voucherify.io/)** | Open-source Next.js loyalty app + POS simulator that integrates with Voucherify (and optionally CDPs/CEPs). Useful reference implementation for omnichannel loyalty. | Open source (frontend) | Accelerator requiring Voucherify backend |

### 🛠️ Specialized Libraries & Related Tools

| Project | Description | Focus Area |
|---------|-------------|---------|
| **[zgabievi/laravel-promocodes](https://github.com/zgabievi/laravel-promocodes)** [![GitHub Stars](https://img.shields.io/github/stars/zgabievi/laravel-promocodes?style=social&color=white)](https://github.com/zgabievi/laravel-promocodes/stargazers) | Coupons and promotional codes generator for Laravel with redemption, validation, and multi-use support. | Laravel promo-code engine |
| **[voucherifyio/voucher-code-generator-js](https://github.com/voucherifyio/voucher-code-generator-js)** [![GitHub Stars](https://img.shields.io/github/stars/voucherifyio/voucher-code-generator-js?style=social&color=white)](https://github.com/voucherifyio/voucher-code-generator-js/stargazers) | Customisable promo code / coupon / voucher generator (JS) — online coupons, prepaid vouchers, in-app promo codes. | Voucher code generation |
| **[Coupon Store / similar self-hosted](https://github.com/metikular/coupon-store)** [![GitHub Stars](https://img.shields.io/github/stars/metikular/coupon-store?style=social&color=white)](https://github.com/metikular/coupon-store/stargazers) | Self-hostable home for coupons, loyalty cards, and gift cards with barcode/QR support and expiry notifications. | Personal coupon & loyalty card storage |
| **iDempiere / ADempiere / ERPNext promotions modules** | Open-source ERP platforms with built-in or extensible promotion, campaign, and loyalty-like features (points as currency, promotion tabs, etc.). | ERP-integrated promotions |
| **Custom rule engines** (e.g., JSON Logic, Drools community, or simple Node/Python engines) | Frequently used to build lightweight promotion validation and discount engines on top of e-commerce platforms. | Custom promotion logic |
| **Web3 / on-chain loyalty experiments** (e.g., ERC-1155 based loyalty protocols) | Emerging open-source dApps for points, loyalty cards, and gift exchanges on blockchain. | Experimental / Web3 loyalty |
| **Odoo / ERPNext loyalty & coupon modules** | Community and enterprise modules for points, coupons, and promotional campaigns within open-source ERP. | ERP + loyalty |

### 📦 Additional Notable Open-Source Tools

- **E-commerce platform native tools** — Magento, Shopify (apps), WooCommerce, Saleor, Medusa, and Bagisto all have open or community coupon/promotion modules that can be extended.
- **General open-source CRM / engagement** (SuiteCRM, EspoCRM, Mautic) — Can be customized for campaign and incentive tracking.
- **Gamification libraries** — Various open-source badge, points, and challenge frameworks that can be wired into custom loyalty systems.
- **Self-hosted stamp / punch-card apps** — Multiple small open-source projects exist for simple digital loyalty cards.
- **Custom builds** on Laravel, Django, NestJS, or Spring — Very common when teams need full control over complex promotion rules and fraud prevention.

**Note:** High-scale, real-time, multi-tenant promotion engines with advanced fraud protection, budget controls, and sub-50ms decisioning are predominantly commercial. Open-source options excel at coupons, basic loyalty points/tiers, stamp cards, and self-hosted voucher management. For enterprise needs, many organizations start with OfferKit or ERP modules and extend them, or use commercial engines with open-source frontends/accelerators.

---

## 🚀 Quick Start Recommendations

| Goal | Recommended Starting Point |
|------|---------------------------|
| Self-hostable modern promotion + loyalty engine | **OfferKit** |
| Simple digital stamp / loyalty cards for SMBs | **Stampee** |
| Voucher, coupon & gift card management | **VoucherVault** or **Coupon Store** |
| Full member marketing for retail stores | **fuint** |
| Headless / API-first loyalty (commercial + open roots) | **Open Loyalty** or **Voucherify** |
| Enterprise real-time promotions & loyalty | **Talon.One** or **Eagle Eye** |
| Trade promotions (CPG) | **Salesforce Promotion Management** |
| Flexible modern loyalty programs | **Antavo** or **Annex Cloud** |
| ERP-integrated promotions | **Odoo / ERPNext / iDempiere** modules |
| Omnichannel retail loyalty accelerator | **Voucherify Loyalty Accelerator** (open frontend) |

---

## 🤝 Contributing

Contributions, corrections, and new open-source projects are welcome.  
Please open an issue or pull request.

---

**Last updated:** August 2026  
Emphasizing open-source tools while documenting the major commercial platforms for context. Production-grade open-source promotion engines are growing but still lag commercial platforms in scale, real-time decisioning, and enterprise fraud/budget controls.
