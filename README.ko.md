<div align="center">

# koaus shop

### Discover Korean lifestyle goods before everyone else.
### 누구보다 먼저 한국의 라이프스타일 제품을 발견하세요.

**A consumer-first shopping experience for global customers — and a live storefront concept for Korean brands exploring overseas sales.**

**해외 소비자를 위해 설계된 쇼핑 경험이자, 한국 브랜드가 자사 제품의 글로벌 판매 모습을 미리 확인할 수 있는 쇼케이스입니다.**

[English](#english) · [한국어](#한국어) · [Project Structure](#project-structure) · [Run Locally](#run-locally)

</div>

---

## English

### What is koaus shop?

**koaus shop is a consumer-facing discovery and shopping platform for international customers interested in Korean lifestyle products.**

The experience is designed primarily for shoppers in the United States and other English-speaking markets. It curates Korean stationery, desk accessories, small gifts, beauty-adjacent lifestyle goods, and emerging independent brands in a format that feels natural to global consumers.

At the same time, koaus shop also works as a **visual market-entry showcase for Korean brands**. A brand can look at the storefront and immediately imagine:

- how its product could be presented to overseas customers,
- how English product storytelling could be structured,
- how UGC, editorial content, and commerce can work together,
- and how consumer interest could be tested before a full international launch.

> **Consumer first. Brand useful.**
>
> The storefront is built for overseas shoppers, while giving Korean brands a concrete view of how their products may be positioned, discovered, saved, and purchased abroad.

### Core value

| For global consumers | For Korean brands |
|---|---|
| Discover distinctive Korean products before they become widely available overseas | See how a product may look and feel in a global storefront |
| Browse in English with familiar commerce patterns | Preview English copy, pricing, imagery, and content structure |
| Save products and express purchase interest | Observe early signals such as saves, votes, and content response |
| Explore products through editorial visuals and short-form video | Test market potential before investing heavily in inventory and logistics |

### Primary audience

- International consumers aged 20–35 interested in K-culture, stationery, desk styling, small gifts, and Korean lifestyle products
- Korean independent brands that want to understand how their products could be presented and validated in the U.S. market

### Experience concept

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

## 한국어

### koaus shop은 무엇인가요?

**koaus shop은 한국 라이프스타일 제품에 관심 있는 해외 소비자를 위한 발견형 쇼핑 플랫폼입니다.**

미국을 포함한 영어권 소비자가 한국 문구, 데스크 용품, 소형 선물, 라이프스타일 제품과 독립 브랜드를 자연스럽게 발견하고 탐색할 수 있도록 설계했습니다.

동시에 이 사이트는 한국 브랜드에게도 의미가 있습니다. 단순한 브랜드 소개 페이지가 아니라, **우리 제품이 실제 해외 소비자용 쇼핑몰에서 어떤 모습으로 판매될 수 있는지 보여주는 글로벌 판매 쇼케이스**이기 때문입니다.

한국 브랜드는 koaus shop을 통해 다음을 구체적으로 확인할 수 있습니다.

- 자사 제품이 해외 소비자에게 어떤 이미지와 문구로 소개될 수 있는지
- 영문 상품 설명과 가격 구조를 어떻게 구성할 수 있는지
- 숏폼 영상과 UGC를 상품 판매에 어떻게 연결할 수 있는지
- 대규모 재고와 물류 투자 전에 소비자 반응을 어떻게 검증할 수 있는지

> **해외 소비자가 먼저 사용하는 쇼핑몰, 한국 브랜드가 해외 판매의 미래를 확인하는 쇼케이스.**

### 핵심 가치

| 해외 소비자에게 | 한국 브랜드에게 |
|---|---|
| 아직 해외에 널리 알려지지 않은 한국 제품을 먼저 발견 | 자사 제품의 글로벌 쇼핑몰 노출 모습을 미리 확인 |
| 영어 중심의 익숙한 쇼핑 경험 | 영문 카피, 가격, 이미지, 콘텐츠 구조 참고 |
| 제품 저장, 투표, 출시 알림 참여 | 저장·투표·콘텐츠 반응을 통한 초기 수요 검증 |
| 에디토리얼 이미지와 숏폼 영상으로 제품 탐색 | 재고·물류 투자 전 해외 시장 가능성 테스트 |

### 주요 사용자

1. K-컬처, 다이어리 꾸미기, 데스크테리어, 소형 선물, 한국 라이프스타일 제품에 관심 있는 미국 및 영어권 20~35세 소비자
2. 본격적인 미국 진출 전에 자사 제품이 글로벌 소비자에게 어떻게 보일지 확인하고 싶은 한국의 독립 브랜드

### 핵심 메시지

- **Consumer message:** Discover Korean lifestyle goods before everyone else.
- **소비자 메시지:** 누구보다 먼저 한국의 라이프스타일 제품을 발견하세요.
- **Brand message:** See how your product could live in a global storefront.
- **브랜드 메시지:** 우리 제품이 글로벌 쇼핑몰에서 판매되는 모습을 확인하세요.

---

## Product Experience

### Main flow

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

### Implemented features

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

## Project Structure

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

## Run Locally

No build process or package installation is required.

```bash
python3 -m http.server 8000
```

Open:

```text
http://localhost:8000
```

---

## Deployment

This project can be deployed as a static site on Vercel.

1. Import the GitHub repository into Vercel.
2. Set **Framework Preset** to `Other`.
3. Leave **Build Command** empty.
4. Use the project root as the output directory.

---

## MVP Notes

This repository is currently a front-end MVP.

- Product saves, votes, launch-list submissions, and brand inquiries are stored in the visitor's browser.
- No production database or email delivery service is connected yet.
- Sample products and pricing are used for educational and market-validation purposes.
- Product names, images, and trademarks remain the property of their respective brands and sellers.
- Sample product cards link to original retailer pages and do not imply that koaus currently owns inventory or official resale rights.
- Current short-form videos are rights-cleared stock assets for MVP validation and should be replaced with licensed brand or creator UGC before commercial launch.

---

<div align="center">

### Built for global shoppers. Designed to show Korean brands what overseas commerce can look like.
### 해외 소비자를 위해 만들고, 한국 브랜드의 글로벌 판매 가능성을 보여줍니다.

</div>
