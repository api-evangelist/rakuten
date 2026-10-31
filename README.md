# Rakuten

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

Rakuten Group is a Japan-headquartered internet conglomerate spanning e-commerce (Rakuten Ichiba), fintech (Rakuten Bank, Rakuten Card, Rakuten Securities), digital content (Rakuten Books, Kobo, Viki), travel (Rakuten Travel), telecom (Rakuten Mobile, Rakuten Symphony), and advertising (Rakuten Advertising). Rakuten exposes a long-standing public developer platform — Rakuten Web Services (webservice.rakuten.co.jp) — that offers REST/JSON APIs for searching Ichiba items and genres, books, CDs, DVDs, games, software, magazines, Kobo eBooks, Rakuten Travel hotels (simple, detail, vacant, keyword), Rakuten Recipe, and Rakuten GORA golf courses. All RWS APIs use a Rakuten application ID for authentication and are read-only. Rakuten separately operates merchant-facing RMS (Rakuten Merchant Server) APIs and Rakuten Pay merchant APIs, which are partner-gated.

**Areas:** E-Commerce · Travel · Books · Recipes · Golf · Japan · Fintech · Telecommunications · Rakuten Web Services

## Rakuten on APIs.io

Everything profiled for Rakuten is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/rakuten/](https://apis.io/providers/rakuten/)** — or go straight to one of the APIs or properties below.

### APIs (33)

- [Rakuten Ichiba Item Search API](https://apis.io/apis/rakuten/ichiba-item-search/) — Keyword and parameter search across all Rakuten Ichiba marketplace items, returning item titles, prices, images, shop information, and ranking signals.
- [Rakuten Ichiba Genre Search API](https://apis.io/apis/rakuten/ichiba-genre-search/) — Returns the hierarchical genre tree used to categorize items across Rakuten Ichiba, enabling category navigation and browse-based product discovery.
- [Rakuten Ichiba Tag Search API](https://apis.io/apis/rakuten/ichiba-tag-search/) — Returns tags associated with a genre, supporting faceted navigation and refinement of Ichiba item browse.
- [Rakuten Ichiba Ranking API](https://apis.io/apis/rakuten/ichiba-item-ranking/) — Returns top-ranked items across Rakuten Ichiba by genre, age, and gender, used for trend and bestseller displays.
- [Rakuten Item Price Navi API](https://apis.io/apis/rakuten/ichiba-product-search/) — Price Navi (Product Search) returns aggregated product records with multi-shop price comparisons, ratings, and review metadata for Ichiba.
- [Rakuten Books Total Search API](https://apis.io/apis/rakuten/books-total-search/) — Unified search across all Rakuten Books catalogs (books, CDs, DVDs, games, software, magazines), returning normalized product records and Rakuten Books shop…
- [Rakuten Books Book Search API](https://apis.io/apis/rakuten/books-book-search/) — Search Rakuten Books for Japanese-language and translated books by title, author, ISBN, publisher, and other metadata.
- [Rakuten Books CD Search API](https://apis.io/apis/rakuten/books-cd-search/) — Search Rakuten Books CD catalog by title, artist, label, and release date.
- [Rakuten Books DVD / Blu-ray Search API](https://apis.io/apis/rakuten/books-dvd-search/) — Search Rakuten Books DVD and Blu-ray catalog including movies, TV, anime, and live performances.
- [Rakuten Books Foreign Book Search API](https://apis.io/apis/rakuten/books-foreign-search/) — Search Rakuten Books foreign-language books catalog (mostly English-language).
- [Rakuten Books Magazine Search API](https://apis.io/apis/rakuten/books-magazine-search/) — Search Rakuten Books magazine catalog by title, publisher, and issue date.
- [Rakuten Books Game Search API](https://apis.io/apis/rakuten/books-game-search/) — Search Rakuten Books video game catalog across major consoles and platforms.
- [Rakuten Books Software Search API](https://apis.io/apis/rakuten/books-software-search/) — Search Rakuten Books PC software catalog.
- [Rakuten Books Genre Search API](https://apis.io/apis/rakuten/books-genre-search/) — Returns the genre tree for Rakuten Books, used for browse and navigation across the unified Books catalog.
- [Rakuten Kobo eBook Search API](https://apis.io/apis/rakuten/kobo-ebook-search/) — Search Rakuten Kobo's eBook catalog for digital reading content across Japanese and international titles.
- [Rakuten Kobo Genre Search API](https://apis.io/apis/rakuten/kobo-genre-search/) — Returns the Kobo eBook genre hierarchy for browse and filter.
- [Rakuten Travel Simple Hotel Search API](https://apis.io/apis/rakuten/travel-simple-hotel-search/) — Lightweight keyword and area search over Rakuten Travel's Japanese hotel inventory, returning hotel name, location, and basic descriptors.
- [Rakuten Travel Hotel Detail Search API](https://apis.io/apis/rakuten/travel-hotel-detail-search/) — Returns full hotel detail records including amenities, addresses, images, and access information for one or more Rakuten Travel hotels by hotel number.
- [Rakuten Travel Vacant Hotel Search API](https://apis.io/apis/rakuten/travel-vacant-hotel-search/) — Searches for hotels with vacancy for given check-in and check-out dates, party composition, and budget filters.
- [Rakuten Travel Area Class API](https://apis.io/apis/rakuten/travel-get-area-class/) — Returns Rakuten Travel's hierarchical Japanese area classification (prefecture / region / detail), used to scope hotel searches and build location filters.
- [Rakuten Travel Keyword Hotel Search API](https://apis.io/apis/rakuten/travel-keyword-hotel-search/) — Full-text keyword search across Rakuten Travel hotel inventory, with filters for area, price, and rating.
- [Rakuten Travel Hotel Chain List API](https://apis.io/apis/rakuten/travel-hotel-chain-list/) — Returns the list of hotel chains available on Rakuten Travel, used to scope searches to a specific brand.
- [Rakuten Travel Hotel Ranking API](https://apis.io/apis/rakuten/travel-hotel-ranking/) — Returns top-ranked Rakuten Travel hotels by area and category for trend, bestseller, and recommendation displays.
- [Rakuten Recipe Category List API](https://apis.io/apis/rakuten/recipe-category-list/) — Returns the Rakuten Recipe category hierarchy (large, medium, small) used for browse navigation of user-submitted Japanese recipes.
- [Rakuten Recipe Category Ranking API](https://apis.io/apis/rakuten/recipe-category-ranking/) — Returns top-ranked recipes within a Rakuten Recipe category, with images, ingredients, and recipe URLs.
- [Rakuten GORA Golf Course Search API](https://apis.io/apis/rakuten/gora-golf-course-search/) — Search Rakuten GORA Japanese golf courses by name, area, and facility attributes.
- [Rakuten GORA Golf Course Detail API](https://apis.io/apis/rakuten/gora-golf-course-detail/) — Returns full golf course detail records on Rakuten GORA including holes, yardage, fees, access, and amenities.
- [Rakuten GORA Golf Plan Search API](https://apis.io/apis/rakuten/gora-plan-search/) — Search Rakuten GORA tee-time plans by course, date, party size, and budget — used to surface bookable golf rounds.
- [Rakuten Pay Merchant API](https://apis.io/apis/rakuten/rakuten-pay/) — Rakuten Pay is Rakuten's e-money / QR payment service for Japan, integrated by merchants directly or via PSPs. The merchant API handles order creation,…
- [Rakuten RMS (Merchant Server) API](https://apis.io/apis/rakuten/rms/) — RMS (Rakuten Merchant Server) is the operational API for Rakuten Ichiba sellers, covering item management, order management, shipping, inventory, and…
- [Rakuten Ichibagt API](https://apis.io/apis/rakuten/rakuten-ichibagt-api/) — The Ichibagt API from Rakuten — 1 operation(s) for ichibagt.
- [Rakuten Ichibams API](https://apis.io/apis/rakuten/rakuten-ichibams-api/) — The Ichibams API from Rakuten — 1 operation(s) for ichibams.
- [Rakuten Ichibaranking API](https://apis.io/apis/rakuten/rakuten-ichibaranking-api/) — The Ichibaranking API from Rakuten — 1 operation(s) for ichibaranking.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Rakuten Agentic Access](https://apis.io/agentic-access/rakuten/rakuten-agentic-access/)

#### Collections (4)

Postman and Open Collection request collections.

- [Rakuten Web Services API](https://apis.io/collections/rakuten/open-rakuten/)
- [Rakuten Web Services Ichibagt API](https://apis.io/collections/rakuten/open-rakuten-ichibagt-api/)
- [Rakuten Web Services Ichibagt Ichibams API](https://apis.io/collections/rakuten/open-rakuten-ichibams-api/)
- [Rakuten Web Services Ichibagt Ichibaranking API](https://apis.io/collections/rakuten/open-rakuten-ichibaranking-api/)

#### Security (2)

Authentication, trust centre, and vulnerability disclosure.

- [Rakuten Authentication](https://apis.io/security/rakuten/rakuten-authentication/)
- [Rakuten Domain Security](https://apis.io/security/rakuten/rakuten-domain-security/)

#### Plans and pricing (1)

Published plans, tiers and prices.

- [Rakuten Plans Pricing](https://apis.io/plans/rakuten/rakuten-plans-pricing/)

#### Rate limits (1)

Published request limits.

- [Rakuten Rate Limits](https://apis.io/rate-limits/rakuten/rakuten-rate-limits/)

#### FinOps (1)

What the API costs to run, by operation.

- [Rakuten Finops](https://apis.io/finops/rakuten/rakuten-finops/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://global.rakuten.com/corp/)
- [Documentation](https://webservice.rakuten.co.jp/documentation)

## API Evangelist rating

**Kin Score 28.2** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 67.0 |
| Contract quality | 47.1 |
| Contract governance | 0.0 |
| Operational transparency | 10.5 |
| Developer ergonomics | 31.0 |
| Access clarity | 18.4 |

**Agent readiness 20.7** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | — |
| Rate Limit Signal | derived (partial credit) |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 10.0** — Telecommunications

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/rakuten/](https://apis.io/providers/rakuten/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Rakuten: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/rakuten/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
