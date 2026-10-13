# Once More - Cafe & Store | Scraped Dataset & Official Website

> **Live Website on GitHub Pages:** [https://hunter-420.github.io/once_more_cafe/](https://hunter-420.github.io/once_more_cafe/)

This repository contains the complete dataset, high-resolution original photography, verified customer reviews, categorized menus, local SEO schema, and an ultra-responsive, accessible website for **Once More - Cafe & Store** (scraped directly from [Google Maps](https://maps.app.goo.gl/sYgYipkAPVMcbTCM9)).

---

## Directory Structure & File Map

```text
once_more_cafe/
│
├── index.html                          # Semantic HTML5 website (OpenGraph, Schema.org, SVG icons)
├── styles.css                          # Modern CSS with mobile navigation drawer & fluid design
├── README.md                           # Master documentation, data index & guide
│
├── .github/
│   └── workflows/
│       └── pages.yml                   # Automated GitHub Actions Pages deployment workflow
│
├── data/                               # Structured datasets for development & database seeding
│   ├── business_details.json           # Business info, contact, GPS, hours, Place ID & amenities
│   ├── reviews.json                    # Customer reviews, ratings, dates, aspects & photo links
│   ├── review_sentiment_topics.json    # Sentiment metrics, Google mention chips & theme quotes
│   ├── menu_and_offerings.json         # Categorized menu items, descriptions & NZD prices
│   └── images_metadata.json            # Photo metadata, dimensions, hashes & source URLs
│
├── images/                             # 21 uncompressed original photos (41+ MB)
│   ├── gallery_01.jpg                  # Front entrance & street view (4032x3024)
│   ├── gallery_02.jpg                  # Signature iced dirty latte & mango dessert (3024x4032)
│   ├── gallery_03.jpg                  # Specialty latte art heart in ceramic cup (2650x2136)
│   ├── gallery_04.jpg                  # Espresso counter bar & full interior (2991x1911)
│   ├── review_photo_05.jpg to 19.jpg   # Teas, savouries, cabinet food, ceramics
│   ├── image_21.jpg                    # Full exterior perspective
│   ├── streetview_storefront.jpg       # Google Street View facade capture
│   ├── business_avatar.jpg             # Google profile avatar
│   └── avatars/                        # Reviewer profile photos for testimonials
│       ├── avatar_01_iyo.jpg           # Reviewer "이요"
│       ├── avatar_02_anatoly.jpg       # Reviewer "Anatoly"
│       ├── avatar_03_adam_park.jpg     # Reviewer "Adam Park"
│       ├── avatar_04_teddy.jpg         # Reviewer "Teddy"
│       └── avatar_05_royal_reed.jpg    # Reviewer "Royal Reed"
│
├── website_assets/                     # Developer copy, wireframes & SEO markup
│   ├── schema_local_business.json      # Valid Schema.org JSON-LD (CafeOrCoffeeShop)
│   └── website_copy_and_wireframe.md   # Copywriting, brand palette, wireframe & SEO specs
│
└── website_preview/                    # Dedicated website preview standalone directory
    ├── index.html                      # Standalone preview HTML
    └── styles.css                      # Standalone preview CSS
```

---

## Business Summary

| Attribute | Details |
| :--- | :--- |
| **Business Name** | Once More - Cafe & Store |
| **Category** | Specialty Coffee / Organic Estate Tea / Daily Bakery / Spanish Homeware |
| **Overall Rating** | **4.7 / 5.0** (89 verified Google reviews, 88.8% 5-star rating) |
| **Street Address** | 182 Symonds Street, Eden Terrace, Auckland 1010, New Zealand |
| **Coordinates** | Latitude `-36.863458`, Longitude `174.7613921` |
| **Plus Code** | `4QP6+JH Auckland` |
| **Phone** | `0210 849 8991` (International: `+64 210 849 8991`) |
| **Instagram** | [@once_more_nz](https://www.instagram.com/once_more_nz/) |
| **Google Maps Link** | [maps.app.goo.gl/sYgYipkAPVMcbTCM9](https://maps.app.goo.gl/sYgYipkAPVMcbTCM9) |
| **Google Place ID** | `ChIJDxiuQlhHDW0RI8mLwDLveNA` |
| **Google CID** | `15022067756910627107` |
| **Price Tier** | `$` ($1 – $10 NZD per person) |
| **Atmosphere** | Very quiet, cozy vintage decor, fine porcelain teaware, remote-work friendly |

---

## Operating Hours

- **Monday:** 7:30 AM – 3:00 PM
- **Tuesday:** 7:30 AM – 3:00 PM
- **Wednesday:** 7:30 AM – 3:00 PM
- **Thursday:** 7:30 AM – 3:00 PM
- **Friday:** 7:30 AM – 3:00 PM
- **Saturday:** Closed
- **Sunday:** Closed

---

## Key Website Features

- **Vector Iconography:** 100% SVG vector icons for pin, phone, clock, espresso, teas, stars, and external links (zero emoji dependencies).
- **Mobile Navigation Drawer:** Responsive slide-in drawer with accessible hamburger toggle on tablets and mobile devices.
- **Interactive Menu Filtering:** Category filter buttons for Coffee, Signatures, Teas, Savouries, Sweets, and Ceramics.
- **Dynamic Operating Hours:** Automatically detects today's day of the week and highlights current hours.
- **Deep Technical SEO:** Schema.org JSON-LD graph, OpenGraph tags, Twitter cards, local NZ geotagging, and semantic HTML landmarks.
- **Ultra-Responsive:** Tested and optimized for mobile ($320\text{px}$–$480\text{px}$), tablet ($481\text{px}$–$1024\text{px}$), and desktop ($1024\text{px}+$ and $1440\text{px}+$).
