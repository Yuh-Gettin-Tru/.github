# Yuh Gettin' Tru

<p align="center">
  <img src="https://raw.githubusercontent.com/Yuh-Gettin-Tru/.github/main/profile/images/ygt_logo_fish_combined_lightbg.png" alt="Yuh Gettin' Tru" width="400">
</p>

**Yuh Gettin' Tru?** is a Barbados-built search engine for local products and services.

People search once and find what is available locally across retailer websites, Instagram-based vendors, service providers, and other local business sources.

The goal is simple: make Barbadian commerce easier to discover.

## What We Are Building

Caribbean consumers often have to search store by store, message Instagram pages, ask in WhatsApp groups, or drive around to find out whether something is available locally. Many businesses are online, but their products and services are not structured, searchable, or comparable.

Yuh Gettin' Tru is building the discovery layer for that market.

Current focus areas:

- Product and service search for Barbados
- Retailer and vendor discovery
- Instagram vendor visibility
- Search and click analytics
- Merchant reporting and demand intelligence
- Local commerce research with FutureBARBADOS interns

## Active Repositories

The platform has been split from the original monorepo into service-specific repositories:

| Repository | CI | Purpose |
|---|---|---|
| [`ygt-site`](https://github.com/Yuh-Gettin-Tru/ygt-site) | [![CI](https://github.com/Yuh-Gettin-Tru/ygt-site/actions/workflows/ci.yml/badge.svg)](https://github.com/Yuh-Gettin-Tru/ygt-site/actions/workflows/ci.yml) | Public gateway and server-rendered site (FastAPI, templates, static assets) |
| [`ygt-search`](https://github.com/Yuh-Gettin-Tru/ygt-search) | [![CI](https://github.com/Yuh-Gettin-Tru/ygt-search/actions/workflows/ci.yml/badge.svg)](https://github.com/Yuh-Gettin-Tru/ygt-search/actions/workflows/ci.yml) | Federated search backends: products, vendors, property, and vendor-catalog |
| [`ygt-pipeline`](https://github.com/Yuh-Gettin-Tru/ygt-pipeline) | — | Crawl/extract pipeline and product CLI |
| [`ygt-ads`](https://github.com/Yuh-Gettin-Tru/ygt-ads) | [![CI](https://github.com/Yuh-Gettin-Tru/ygt-ads/actions/workflows/ci.yml/badge.svg)](https://github.com/Yuh-Gettin-Tru/ygt-ads/actions/workflows/ci.yml) | Self-service advertising portal, Stripe billing, and ad serving |
| [`ygt-common`](https://github.com/Yuh-Gettin-Tru/ygt-common) | [![CI](https://github.com/Yuh-Gettin-Tru/ygt-common/actions/workflows/ci.yml/badge.svg)](https://github.com/Yuh-Gettin-Tru/ygt-common/actions/workflows/ci.yml) | Shared packages: `federation-protocol`, `ssrf-policy`, `ygt-db`, `embeddings` |
| [`ygt-infra`](https://github.com/Yuh-Gettin-Tru/ygt-infra) | [![Backup](https://github.com/Yuh-Gettin-Tru/ygt-infra/actions/workflows/backup.yml/badge.svg)](https://github.com/Yuh-Gettin-Tru/ygt-infra/actions/workflows/backup.yml) | Shared infrastructure, routing, backups, and deployment tooling |

### Deprecated / Archived

| Repository | Status |
|---|---|
| [`yuhgettintru`](https://github.com/Yuh-Gettin-Tru/yuhgettintru) | **Deprecated.** The original monorepo — archived and no longer actively maintained. All code has been split into the repositories above. |
| [`ygt-embeddings`](https://github.com/Yuh-Gettin-Tru/ygt-embeddings) | **Archived.** Merged into `ygt-common` as the `embeddings/` subdirectory package. |

### FutureBARBADOS Intern Repositories

These repositories are used by the Future Barbados Interns programme and are separate from the production codebase:

| Repository | Purpose |
|---|---|
| [`yuhgettintru-interns`](https://github.com/Yuh-Gettin-Tru/yuhgettintru-interns) | FutureBARBADOS internship task tracker and project workspace |
| [`yuhgettintru-intelligence`](https://github.com/Yuh-Gettin-Tru/yuhgettintru-intelligence) | Staging intelligence and data-access workspace for approved intern analysis |

Most repositories are private while the platform is under active development.

## FutureBARBADOS Internship Sprint

The internship project gives students practical work on a live Barbados commerce platform. Intern work is organised around five buckets:

1. Vendor discovery and validation
2. Customer and merchant discovery
3. Data and market analysis
4. Product and reporting work
5. Go-to-market thinking

The work is intentionally practical: validate real businesses, analyse real search behaviour, prototype useful reporting, and turn findings into clear recommendations.

## Working Principles

- Use evidence, not guesses.
- Keep business, research, and production code clearly separated.
- Do not add data to production without review.
- Document sources, dates, assumptions, and limitations.
- Prefer useful, measurable outputs over vague activity.

## Contact

Project lead: Matt Hamilton, Dharach Pte. Ltd.
