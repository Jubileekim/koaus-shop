# koaus shop

### Discover Korean lifestyle goods before everyone else.

[English](README.md) | [한국어](README.ko.md)

**A consumer-first shopping experience for global customers — and a live storefront concept for Korean brands exploring overseas sales.**

koaus shop is designed primarily for shoppers in the United States and other English-speaking markets. It curates Korean stationery, desk accessories, small gifts, beauty-adjacent lifestyle goods, and emerging independent brands in a format that feels natural to global consumers.

At the same time, the storefront also serves as a **visual market-entry showcase for Korean brands**. It helps brands imagine how their products could be positioned, discovered, saved, and purchased in an overseas shopping environment.

> **Consumer first. Brand useful.**
>
> Built for global shoppers, while giving Korean brands a concrete view of what overseas commerce could look like.

---

## What is koaus shop?

koaus shop is a consumer-facing discovery and shopping platform for international customers interested in Korean lifestyle products.

For global shoppers, it provides an English-first storefront with editorial product presentation, short-form video, product saving, voting, and purchase-interest interactions.

For Korean brands, it provides a practical preview of:

- how products could be presented to overseas customers,
- how English product storytelling could be structured,
- how pricing, imagery, UGC, and commerce can work together,
- and how early consumer interest could be tested before a full international launch.

---

## Core value

| For global consumers | For Korean brands |
|---|---|
| Discover distinctive Korean products before they become widely available overseas | See how a product may look and feel in a global storefront |
| Browse in English with familiar commerce patterns | Preview English copy, pricing, imagery, and content structure |
| Save products and express purchase interest | Observe early signals such as saves, votes, and content response |
| Explore products through editorial visuals and short-form video | Test market potential before investing heavily in inventory and logistics |

---

## Primary audience

1. U.S. and English-speaking consumers aged 20–35 interested in K-culture, stationery, desk styling, small gifts, and Korean lifestyle products
2. Independent Korean brands that want to understand how their products could be presented and validated in the U.S. market

---

## Core message

- **Consumer message:** Discover Korean lifestyle goods before everyone else.
- **Brand message:** See how your product could live in a global storefront.
- **Buyer CTA:** Join the Launch List
- **Brand CTA:** Request a Product Check

---

## Experience concept

```text
DISCOVER
Curated Korean products for overseas consumers
        ↓
EXPLORE
Editorial images, product stories, and short-form UGC
        ↓
SAVE & REACT
Wishlist, voting, and launch-interest signals
        ↓
SHOP
A global-facing storefront experience
        ↓
VALIDATE
Early market signals for future brand launches
```

---

## Product experience

```text
HOME
Hero → Categories → Product Discovery → Shop Preview
→ UGC / Short-form Video → Editorial Lookbook → Final CTA

SHOP
Filter → Search → Sort → Save → Product Detail

PRODUCT
Product Story → Price → Source → Save → Purchase Interest

ABOUT
Consumer Value → Brand Value → How It Works → Launch Fit
```

---

## Implemented features

- Editorial homepage with curated Korean lifestyle products
- Consumer-first English shopping experience
- Korean and English language switching
- Category filtering, real-time search, sorting, and saved-product view
- Responsive shop and product detail pages
- Wishlist and product voting stored with `localStorage`
- Inline short-form video with autoplay, loop, mute, and sound controls
- Product-detail storytelling, source disclosure, and purchase-interest feedback
- Launch-list modal and brand product-check prototype
- Separate `about.html` explaining the platform, process, and Launch Fit concept
- Keyboard focus management and Escape-key closing behavior
- Reduced-motion support and Intersection Observer animations

---

## Project structure

```text
.
├── index.html
├── about.html
├── shop.html
├── product.html
├── css/
│   ├── style.css
│   ├── about.css
│   └── store.css
├── js/
│   ├── catalog.js
│   ├── i18n.js
│   ├── main.js
│   ├── about.js
│   ├── shop.js
│   └── product.js
├── images/
├── videos/
├── README.md
├── README.ko.md
└── DESIGN.md
```

---

## Run locally

No build process or package installation is required.

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## Static deployment

This project can be deployed directly to Vercel as a static site.

1. Import the GitHub repository into Vercel.
2. Set **Framework Preset** to `Other`.
3. Leave **Build Command** empty.
4. Use the project root as the output directory.

---

## MVP notes

This repository is currently a front-end MVP.

- Product saves, votes, launch-list submissions, and brand inquiries are stored in the visitor's browser.
- No production database or email delivery service is connected yet.
- Sample products and pricing are used for educational and market-validation purposes.
- Product names, images, and trademarks remain the property of their respective brands and sellers.
- Sample product cards link to original retailer pages and do not imply that koaus currently owns inventory or official resale rights.
- Current short-form videos are rights-cleared stock assets for MVP validation and should be replaced with licensed brand or creator UGC before commercial launch.

---

### Built for global shoppers. Designed to show Korean brands what overseas commerce can look like.
