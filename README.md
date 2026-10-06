# Hugo

**Portugal (remote)** · Attribution and measurement engineer · Founder of [Vizuh](https://vizuh.com)

I build first-party attribution tools that connect ad clicks to the leads, bookings and sales they produce.

Most marketing data breaks somewhere between the ad, the landing page, the consent banner, the form and the CRM. I work on that gap: ads, websites, forms, bookings, and the data between them.

> **Open to:** consulting and contract work on attribution, GA4, GTM (including server-side) and BigQuery · senior or lead roles in measurement or analytics engineering · founding or early roles at startups in martech, adtech or analytics · agencies and SaaS teams that want first-party attribution built in.
>
> **Reach me:** [hugo@vizuh.com](mailto:hugo@vizuh.com)

**Measurement:**
![Google Ads](https://img.shields.io/badge/-Google%20Ads-2b2b2b?style=flat-square&logo=googleads&logoColor=4285F4)
![GA4](https://img.shields.io/badge/-GA4-2b2b2b?style=flat-square&logo=googleanalytics&logoColor=E37400)
![GTM server-side](https://img.shields.io/badge/-GTM%20(server--side)-2b2b2b?style=flat-square&logo=googletagmanager&logoColor=8AB4F8)
![BigQuery](https://img.shields.io/badge/-BigQuery-2b2b2b?style=flat-square&logo=googlebigquery&logoColor=6699FF)

**Engineering:**
![PHP](https://img.shields.io/badge/-PHP-2b2b2b?style=flat-square&logo=php&logoColor=777BB4)
![WordPress](https://img.shields.io/badge/-WordPress-2b2b2b?style=flat-square&logo=wordpress&logoColor=21759B)
![Laravel / Filament](https://img.shields.io/badge/-Laravel%20%2F%20Filament-2b2b2b?style=flat-square&logo=laravel&logoColor=FF2D20)
![Twig](https://img.shields.io/badge/-Twig-2b2b2b?style=flat-square)
![TypeScript](https://img.shields.io/badge/-TypeScript-2b2b2b?style=flat-square&logo=typescript&logoColor=3178C6)
![Python](https://img.shields.io/badge/-Python-2b2b2b?style=flat-square&logo=python&logoColor=3776AB)
![MCP](https://img.shields.io/badge/-MCP-2b2b2b?style=flat-square)

[clicktrail](#clicktrail) · [also building](#also-building) · [why attribution](#why-attribution) · [find me](#find-me)

## clicktrail

**[ClickTrail](https://wordpress.org/plugins/click-trail-handler/)** answers one question: *where did this customer come from?*

It keeps the source of each visit (UTMs, ad click IDs, referrer, channel) attached to the visitor across cached pages, forms, bookings and WooCommerce orders, records first and last touch, and only does it when consent allows. Data can stay in WordPress or go on to GTM or a server-side setup. ([Product Hunt](https://www.producthunt.com/products/clicktrail))

It started as a WordPress plugin and is now a small toolchain:

| Repo | What it does |
|---|---|
| **[click-trail-handler](https://github.com/vizuh/click-trail-handler)** | The WordPress plugin. Attaches campaign source to form submissions and WooCommerce orders, with consent and delivery controls. |
| **[clicktrail-php](https://github.com/vizuh/clicktrail-php)** | The core engine for any PHP app. Works out first and last touch for each lead and produces one consistent event. |
| **[clicktrail-filament](https://github.com/vizuh/clicktrail-filament)** | Laravel admin panels: settings, attribution records, why an event was suppressed, and event mapping. |
| **[clicktrail-twig](https://github.com/vizuh/clicktrail-twig)** | Twig helpers that add the loader tag, hidden source fields and consent attributes to templates. |
| **[clicktrail-gtm-attribution-variable](https://github.com/vizuh/clicktrail-gtm-attribution-variable)** | A GTM variable that gives any tag the visitor's source plus stored first and last touch. |
| **[clicktrail-verify](https://github.com/vizuh/clicktrail-verify)** | Checks in a real browser that attribution data actually reaches the form, with consent respected. |
| **[clicktrail-mcp](https://github.com/vizuh/clicktrail-mcp)** | Lets AI assistants inspect an attribution setup: diagnostics, coverage, integration code and conversion reconciliation. |

## also building

- **[TokenScout](https://github.com/Atroci/tokenscout)**: point it at a live website and get a redesign baseline backed by evidence: design tokens, computed styles, assets, motion, page structure and screenshots. ([Product Hunt](https://www.producthunt.com/products/tokenscout))
- I also run **[Apointoo](https://apointoo.com)** (online booking for local businesses), **[PlugnRank](https://plugnrank.com)** (SEO automation) and **[FunnelSheet](https://funnelsheet.com)** (GA4, Google Ads, Meta, server-side GTM and BigQuery implementation).

## why attribution

> [!IMPORTANT]
> A click is only useful if its context survives long enough to connect to a lead, booking or
> sale. That means handling the messy handoffs between landing pages, consent, forms, booking
> flows and reporting. The hard part is rarely capturing the data. It's reconciling it.

## activity

![GitHub Contribution Graph](https://ghchart.rshah.org/Atroci)

## find me

[![Email](https://img.shields.io/badge/-hugo@vizuh.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:hugo@vizuh.com)
[![Website](https://img.shields.io/badge/-vizuh.com-2b2b2b?style=flat-square&logo=google-chrome&logoColor=white)](https://vizuh.com)
[![LinkedIn](https://img.shields.io/badge/-Hugo%20Carvalho-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/hugocarvalho28/)
[![GitHub](https://img.shields.io/badge/-Atroci-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Atroci)
[![Product Hunt](https://img.shields.io/badge/-ClickTrail-DA552F?style=flat-square&logo=producthunt&logoColor=white)](https://www.producthunt.com/products/clicktrail)
