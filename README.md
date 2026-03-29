# 🏪 Salla Premium Perfume Theme

A high-converting, mobile-first, Arabic-first Salla theme designed for premium perfume e-commerce stores targeting the Saudi Arabian market.

## ✨ Features

- **Mobile-First Design** — Sticky add-to-cart, 44px+ tap targets, thumb-friendly layout
- **Arabic-First RTL** — Full RTL support with Arabic typography (Tajawal font)
- **Luxury Black & Gold** — Premium feel with sophisticated color palette
- **High Conversion** — Trust badges, urgency, social proof, upsell bundles
- **CRO Optimized** — Every section designed to maximize conversion rate

## 📁 Theme Structure

```
src/
├── assets/
│   ├── styles/
│   │   └── app.css              # Main stylesheet (mobile-first, RTL)
│   └── images/                  # Theme images
├── locales/
│   ├── ar.json                  # Arabic translations
│   └── en.json                  # English translations
└── views/
    ├── layouts/
    │   └── master.twig          # Master layout (base HTML)
    ├── pages/
    │   ├── index.twig           # Homepage
    │   └── product/
    │       └── single.twig      # Single product page
    └── components/
        ├── header/
        │   └── header.twig      # Sticky header
        ├── footer/
        │   └── footer.twig      # Footer
        └── home/
            ├── hero.twig        # Hero section (above the fold)
            ├── best-sellers.twig # Best selling products grid
            ├── trust.twig       # Trust badges (COD, shipping, etc.)
            ├── upsell.twig      # Bundle/upsell offers
            ├── testimonials.twig # Customer reviews
            └── urgency.twig     # Countdown timer & urgency
```

## 🎯 Homepage Sections

1. **Hero** — Luxury branding, headline, CTA, trust badges
2. **Best Sellers** — Product grid with ratings & quick add-to-cart
3. **Trust Block** — COD, fast shipping, return guarantee, 5000+ customers
4. **Upsell Bundle** — Buy 2 get discount, visual price comparison
5. **Testimonials** — Arabic reviews emphasizing longevity & compliments
6. **Urgency** — Countdown timer, scarcity messaging

## 🛍️ Product Page

- Image gallery with thumbnails
- Sticky add-to-cart (mobile)
- Benefit bullets (longevity, occasions, natural, authentic)
- Trust badges inline
- Related products upsell
- Customer reviews section

## 🚀 Installation

1. Install Salla CLI: `npm install -g @salla.sa/twilight`
2. Copy theme files to your Salla theme project
3. Run `salla theme serve` to preview
4. Customize colors via CSS variables in `master.twig`
5. Update dummy content with real products
6. Deploy with `salla theme push`

## 🎨 Customization

### Colors
Edit CSS variables in `master.twig`:
```css
--color-primary: #c8a45c;      /* Gold */
--color-bg: #0a0a0a;           /* Black */
--color-bg-card: #1a1a1a;      /* Card background */
```

### Typography
Default: Tajawal (Google Fonts). Change by modifying the font link in `master.twig`.

## 📱 Mobile Optimization

- All buttons ≥ 44px height (tap target compliance)
- Sticky cart button on product pages
- Floating WhatsApp button
- Optimized DOM for 3G performance
- Lazy loading on all non-critical images

## 🧠 CRO Psychology Used

- **Social Proof**: Customer count, ratings, testimonials
- **Urgency**: Countdown timer, "limited quantity" messaging
- **Scarcity**: "Only X remaining" on product pages
- **Trust**: COD, return guarantee, shipping badges
- **Anchoring**: Single vs bundle price comparison
- **Loss Aversion**: "Offer ends today" messaging
