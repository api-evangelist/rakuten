# Rakuten (rakuten)

Rakuten Group is a Japan-headquartered internet conglomerate
spanning e-commerce (Rakuten Ichiba), fintech (Rakuten Bank,
Rakuten Card, Rakuten Securities), digital content (Rakuten
Books, Kobo, Viki), travel (Rakuten Travel), telecom (Rakuten
Mobile, Rakuten Symphony), and advertising (Rakuten Advertising).
Rakuten exposes a long-standing public developer platform —
Rakuten Web Services (webservice.rakuten.co.jp) — that offers
REST/JSON APIs for searching Ichiba items and genres, books,
CDs, DVDs, games, software, magazines, Kobo eBooks, Rakuten
Travel hotels (simple, detail, vacant, keyword), Rakuten Recipe,
and Rakuten GORA golf courses. All RWS APIs use a Rakuten
application ID for authentication and are read-only. Rakuten
separately operates merchant-facing RMS (Rakuten Merchant Server)
APIs and Rakuten Pay merchant APIs, which are partner-gated.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/rakuten/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/rakuten/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Provider
- **Access:** Public

## Tags

- E-commerce
- Travel
- Books
- Recipes
- Golf
- Japan
- Fintech
- Telecom
- Rakuten Web Services

## Timestamps

- **Created:** 2026-05-23
- **Modified:** 2026-05-23

## APIs

### Rakuten Ichiba Item Search API

Keyword and parameter search across all Rakuten Ichiba
marketplace items, returning item titles, prices, images,
shop information, and ranking signals.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/ichiba-item-search](https://webservice.rakuten.co.jp/documentation/ichiba-item-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- E-commerce
- Items
- Search
- Ichiba

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/ichiba-item-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Ichiba Genre Search API

Returns the hierarchical genre tree used to categorize items
across Rakuten Ichiba, enabling category navigation and
browse-based product discovery.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/ichiba-genre-search](https://webservice.rakuten.co.jp/documentation/ichiba-genre-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Genres
- Categories
- Ichiba

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/ichiba-genre-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Ichiba Tag Search API

Returns tags associated with a genre, supporting faceted
navigation and refinement of Ichiba item browse.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/ichiba-tag-search](https://webservice.rakuten.co.jp/documentation/ichiba-tag-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Tags
- Facets
- Ichiba

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/ichiba-tag-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Ichiba Ranking API

Returns top-ranked items across Rakuten Ichiba by genre, age,
and gender, used for trend and bestseller displays.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/ichiba-item-ranking](https://webservice.rakuten.co.jp/documentation/ichiba-item-ranking)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Ranking
- Bestsellers
- Ichiba

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/ichiba-item-ranking)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Item Price Navi API

Price Navi (Product Search) returns aggregated product
records with multi-shop price comparisons, ratings, and
review metadata for Ichiba.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/ichiba-product-search](https://webservice.rakuten.co.jp/documentation/ichiba-product-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Products
- Price Comparison
- Reviews

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/ichiba-product-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Total Search API

Unified search across all Rakuten Books catalogs (books, CDs,
DVDs, games, software, magazines), returning normalized
product records and Rakuten Books shop information.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-total-search](https://webservice.rakuten.co.jp/documentation/books-total-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Books
- Media
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-total-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Book Search API

Search Rakuten Books for Japanese-language and translated
books by title, author, ISBN, publisher, and other metadata.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-book-search](https://webservice.rakuten.co.jp/documentation/books-book-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Books
- Search
- ISBN

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-book-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books CD Search API

Search Rakuten Books CD catalog by title, artist, label, and
release date.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-cd-search](https://webservice.rakuten.co.jp/documentation/books-cd-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Music
- CDs
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-cd-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books DVD / Blu-ray Search API

Search Rakuten Books DVD and Blu-ray catalog including
movies, TV, anime, and live performances.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-dvd-search](https://webservice.rakuten.co.jp/documentation/books-dvd-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Video
- DVD
- Blu-ray

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-dvd-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Foreign Book Search API

Search Rakuten Books foreign-language books catalog (mostly
English-language).

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-foreign-search](https://webservice.rakuten.co.jp/documentation/books-foreign-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Books
- Foreign
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-foreign-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Magazine Search API

Search Rakuten Books magazine catalog by title, publisher,
and issue date.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-magazine-search](https://webservice.rakuten.co.jp/documentation/books-magazine-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Magazines
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-magazine-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Game Search API

Search Rakuten Books video game catalog across major consoles
and platforms.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-game-search](https://webservice.rakuten.co.jp/documentation/books-game-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Games
- Consoles
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-game-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Software Search API

Search Rakuten Books PC software catalog.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-software-search](https://webservice.rakuten.co.jp/documentation/books-software-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Software
- PC
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-software-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Books Genre Search API

Returns the genre tree for Rakuten Books, used for browse and
navigation across the unified Books catalog.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/books-genre-search](https://webservice.rakuten.co.jp/documentation/books-genre-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Genres
- Categories
- Books

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/books-genre-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Kobo eBook Search API

Search Rakuten Kobo's eBook catalog for digital reading
content across Japanese and international titles.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/kobo-ebook-search](https://webservice.rakuten.co.jp/documentation/kobo-ebook-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- eBooks
- Kobo
- Search

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/kobo-ebook-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Kobo Genre Search API

Returns the Kobo eBook genre hierarchy for browse and filter.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/kobo-genre-search](https://webservice.rakuten.co.jp/documentation/kobo-genre-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Genres
- eBooks
- Kobo

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/kobo-genre-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Simple Hotel Search API

Lightweight keyword and area search over Rakuten Travel's
Japanese hotel inventory, returning hotel name, location,
and basic descriptors.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/simple-hotel-search](https://webservice.rakuten.co.jp/documentation/simple-hotel-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Hotels
- Search
- Japan

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/simple-hotel-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Hotel Detail Search API

Returns full hotel detail records including amenities,
addresses, images, and access information for one or more
Rakuten Travel hotels by hotel number.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/hotel-detail-search](https://webservice.rakuten.co.jp/documentation/hotel-detail-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Hotels
- Details

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/hotel-detail-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Vacant Hotel Search API

Searches for hotels with vacancy for given check-in and
check-out dates, party composition, and budget filters.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/vacant-hotel-search](https://webservice.rakuten.co.jp/documentation/vacant-hotel-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Hotels
- Availability
- Booking

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/vacant-hotel-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Area Class API

Returns Rakuten Travel's hierarchical Japanese area
classification (prefecture / region / detail), used to scope
hotel searches and build location filters.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/get-area-class](https://webservice.rakuten.co.jp/documentation/get-area-class)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Areas
- Japan

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/get-area-class)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Keyword Hotel Search API

Full-text keyword search across Rakuten Travel hotel
inventory, with filters for area, price, and rating.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/keyword-hotel-search](https://webservice.rakuten.co.jp/documentation/keyword-hotel-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Hotels
- Keyword

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/keyword-hotel-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Hotel Chain List API

Returns the list of hotel chains available on Rakuten Travel,
used to scope searches to a specific brand.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/get-hotel-chain-list](https://webservice.rakuten.co.jp/documentation/get-hotel-chain-list)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Chains
- Brands

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/get-hotel-chain-list)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Travel Hotel Ranking API

Returns top-ranked Rakuten Travel hotels by area and category
for trend, bestseller, and recommendation displays.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/hotel-ranking](https://webservice.rakuten.co.jp/documentation/hotel-ranking)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Travel
- Hotels
- Ranking

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/hotel-ranking)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Recipe Category List API

Returns the Rakuten Recipe category hierarchy (large, medium,
small) used for browse navigation of user-submitted Japanese
recipes.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/recipe-category-list](https://webservice.rakuten.co.jp/documentation/recipe-category-list)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Recipes
- Categories
- Food

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/recipe-category-list)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Recipe Category Ranking API

Returns top-ranked recipes within a Rakuten Recipe category,
with images, ingredients, and recipe URLs.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/recipe-category-ranking](https://webservice.rakuten.co.jp/documentation/recipe-category-ranking)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Recipes
- Ranking
- Food

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/recipe-category-ranking)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten GORA Golf Course Search API

Search Rakuten GORA Japanese golf courses by name, area, and
facility attributes.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/gora-golf-course-search](https://webservice.rakuten.co.jp/documentation/gora-golf-course-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Golf
- GORA
- Japan

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/gora-golf-course-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten GORA Golf Course Detail API

Returns full golf course detail records on Rakuten GORA
including holes, yardage, fees, access, and amenities.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/gora-golf-course-detail](https://webservice.rakuten.co.jp/documentation/gora-golf-course-detail)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Golf
- GORA
- Course Details

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/gora-golf-course-detail)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten GORA Golf Plan Search API

Search Rakuten GORA tee-time plans by course, date, party
size, and budget — used to surface bookable golf rounds.

- **Human URL:** [https://webservice.rakuten.co.jp/documentation/gora-plan-search](https://webservice.rakuten.co.jp/documentation/gora-plan-search)
- **Base URL:** `https://app.rakuten.co.jp`

#### Tags

- Golf
- GORA
- Tee Times

#### Properties

- [Documentation](https://webservice.rakuten.co.jp/documentation/gora-plan-search)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten Pay Merchant API

Rakuten Pay is Rakuten's e-money / QR payment service for
Japan, integrated by merchants directly or via PSPs. The
merchant API handles order creation, payment authorization,
capture, refunds, and reconciliation for in-store QR and
online checkout flows.

- **Human URL:** [https://pay.rakuten.co.jp/business/](https://pay.rakuten.co.jp/business/)
- **Base URL:** `https://api.rakuten.co.jp`

#### Tags

- Payments
- QR
- Japan
- Merchant

#### Properties

- [Product Page](https://pay.rakuten.co.jp/business/)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Rakuten RMS (Merchant Server) API

RMS (Rakuten Merchant Server) is the operational API for
Rakuten Ichiba sellers, covering item management, order
management, shipping, inventory, and customer messaging.
Access is restricted to approved Ichiba shop owners and
partner ERP / OMS vendors.

- **Human URL:** [https://webservice.rms.rakuten.co.jp/](https://webservice.rms.rakuten.co.jp/)
- **Base URL:** `https://api.rms.rakuten.co.jp`

#### Tags

- Merchant
- Ichiba
- Orders
- Inventory
- ERP

#### Properties

- [Product Page](https://webservice.rms.rakuten.co.jp/)
- [Postman Collection](collections/rakuten.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/rakuten.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Corporate Website](https://global.rakuten.com/corp/)
- [Consumer Website](https://www.rakuten.co.jp/)
- [Developer Portal](https://webservice.rakuten.co.jp/)
- [Documentation](https://webservice.rakuten.co.jp/documentation)
- [A P I List](https://webservice.rakuten.co.jp/documentation)
- [Sign Up](https://webservice.rakuten.co.jp/app/create)
- [R M S](https://webservice.rms.rakuten.co.jp/)
- [Rakuten Pay](https://pay.rakuten.co.jp/business/)
- [Investor Relations](https://global.rakuten.com/corp/investors/)
- [News](https://global.rakuten.com/corp/news/)
- [Sustainability](https://global.rakuten.com/corp/sustainability/)
- [Careers](https://global.rakuten.com/corp/careers/)
- [Git Hub](https://github.com/rakutentech)
- [Tech Blog](https://engineering.rakuten.today/)
- [LinkedIn](https://www.linkedin.com/company/rakuten/)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
