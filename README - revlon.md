# Revlon SEO & SEA Performance Report

A full technical & content SEO audit + SEA (Google Ads) review of revlon.com — delivered as both a detailed Word report and a presentation deck.

## Team

- Harini Umashankar
- Roshini Sureshkumar
- Venkata Sai Rishi

## Repo Contents

- `revlon_seo_report_docx.pdf` — full written report (13 sections, screenshot-by-screenshot analysis)
- `revlon_seo_analysis_ppt.pdf` — presentation deck summarizing the same audit for stakeholder review

## Scope

- **Pages audited:** Homepage, Hair Category (`/collections/hair`), Lips Sub-category (`/lips`), Lipstick Product (`/lips/lipstick`), Face Category (`/face`)
- **Tools used:** Google PageSpeed Insights / CrUX, Web Developer extension (heading & meta outline), Google Rich Results Test, site crawler, SSL certificate viewer, Ahrefs Free Backlink Checker, Social Blade
- **KPIs tracked:** title & meta tag coverage, image alt-text coverage, structured data (schema), Core Web Vitals (LCP / INP / CLS), HTTPS, crawlability (sitemap/robots), broken links & redirects, content depth vs. competitors, social reach

## Key Findings

**Strengths**
- HTTPS active on all pages (Let's Encrypt SSL, valid through Aug 2026)
- Clean, logical URL hierarchy (Home → Category → Sub-category → Product)
- Organization schema present on homepage; FAQPage schema on Lips and Face categories
- sitemap.xml and robots.txt both correctly configured, admin/checkout properly disallowed
- Strong domain authority (DR 72/100, 130K backlinks, 7.9K linking domains, 91% dofollow)
- LinkedIn is an active, well-used channel (454K+ followers)

**Weaknesses**
- Meta descriptions missing on every audited page (Google auto-generates low-quality snippets instead)
- Title tags frequently omit the brand name; H1s missing on 3 of 5 category pages
- Many images have empty/`null` alt attributes
- Core Web Vitals fail on every page — CLS (layout shift) is above the 0.1 threshold site-wide
- No Product or BreadcrumbList schema on product/category pages (no star ratings/price shown in Google)
- 1 broken outbound link (404) + 137 broken inbound links + redirect chains diluting link equity
- Thin content strategy vs. competitors — no blog/tutorial hub; weakest of L'Oréal, Maybelline, NYX, Revlon
- No sitemap link visible in site footer
- Pinterest presence near-zero (~1K followers, no global brand account); YouTube underperforming (117K subs, ~600 views/day)

## Core Web Vitals Snapshot

| Page Type | LCP | INP | CLS | Assessment |
|---|---|---|---|---|
| Homepage | 2.4s | 81ms | 0.17 | Failed |
| Hair Category | 1.5s | 84ms | 0.11 | Failed |
| Lips Sub-category | 1.6s | 121ms | 0.11 | Failed |
| Lipstick Product | 1.6s | 121ms | 0.11 | Failed |
| Face Category | 1.6s | 121ms | 0.11 | Failed |

Targets: LCP < 2.5s, INP < 200ms, CLS < 0.1. LCP and INP largely pass; CLS fails everywhere due to layout jumps from unoptimised images and fonts loading.

## Social Media Ecosystem

| Platform | Followers | Status |
|---|---|---|
| Facebook | Largest | Strong branded-search presence |
| Instagram | Second largest | Strong branded-search presence |
| LinkedIn | 454K+ | Most professionally active platform |
| YouTube | ~117K subs | Low growth (~600 views/day), underperforming vs. rivals' millions |
| Pinterest | ~1K (Hair Tools sub-account only) | No global brand account — major missed opportunity |

## SWOT Summary

- **Strengths:** HTTPS, clear site structure, homepage schema, strong lipstick title tag, 90+ year brand heritage, solid LinkedIn presence
- **Weaknesses:** missing meta descriptions & brand names in titles, empty alt text, failing CLS, no content hub, weak YouTube & Pinterest
- **Opportunities:** beauty content hub for how-to keywords, full schema coverage, Pinterest (high purchase intent), revived YouTube, hair-care content gap
- **Threats:** L'Oréal & Maybelline dominate content SEO, NYX winning TikTok/creator audience, competitors have full alt-text coverage, slow speed vs. mobile-first indexing

## Prioritised Action Plan

**Quick wins (1–2 weeks)** — High impact, low effort
- Write meta descriptions for all pages
- Fix missing image alt text
- Add brand name to title tags

**Medium priority (1–4 weeks)**
- Add Product schema (star ratings, price, availability)
- Fix broken links & collapse redirect chains
- Resubmit sitemap to Google Search Console

**Strategic (1–3 months)**
- Build a "Revlon Beauty Edit" content hub targeting high-volume how-to keywords (est. +30–50% organic traffic in 6–12 months)
- Fix Core Web Vitals (CLS) site-wide via image compression, lazy-loading, reserved image space, reduced render-blocking JS
- Launch a Pinterest Business Account and revive YouTube with regular tutorial content
- Optimise the existing Google Ads search campaign (currently "Good" ad strength) with more headlines, sitelinks, and callouts

## SEA (Google Ads) Snapshot

- Search campaign targeting "revlon hair products", ad strength rated "Good"
- Opportunities: add unique headlines & popular keywords, benefit-led descriptions, sitelinks/callouts, align copy with high-intent product terms
