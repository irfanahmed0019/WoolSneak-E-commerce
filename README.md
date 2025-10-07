# 🐑 WoolSneak — Natural Wool Meets Urban Tech

**WoolSneak** is a minimalist e-commerce web app dedicated to selling premium wool sneakers that combine **natural comfort** with **urban performance**.  
The brand philosophy: *“Natural wool meets urban tech.”*  
Built for eco-conscious city dwellers who want sustainable, weather-resistant footwear without sacrificing style.

---

## 🌿 Core Concept

WoolSneak bridges **nature and innovation** — bringing responsibly sourced wool, advanced materials, and ergonomic design into a modern digital storefront.

- **Brand Tone:** Warm, minimal, and tactile.  
- **Color Palette:**  
  - `#F7F5F1` Warm White  
  - `#DCCDB6` Oat  
  - `#BFC7C2` Mist Grey  
  - `#37424A` Soft Charcoal (CTA)  
  - `#C9A08F` Muted Terracotta (accent)  
- **Typography:**  
  - Headlines — *Inter* (600–700)  
  - Body — *Source Sans Pro* (400–600)  
- **Imagery:** Low-saturation, soft-light lifestyle photos that highlight wool texture and city mood.

---

## 🛍️ Key Features

| Category | Features |
|-----------|-----------|
| **Core Storefront** | Homepage hero with brand story, dynamic product carousel |
| **Product Pages** | Detailed product info, zoomable images, sustainability badges |
| **Shopping Cart** | Persistent mini-cart drawer, quantity editing, promo codes |
| **Checkout** | Guest & registered checkout, order summary, multiple payment options |
| **Account System** | Saved sizes, past orders, wishlist |
| **SEO / Marketing** | Metadata, structured data, GA + Pixel tracking |
| **Performance** | Lighthouse > 90, TTI < 3s, lazy-loaded WebP images |

---

## 👣 Target Audience

- Urban professionals (22–40) who value comfort + sustainability  
- Commuters needing lightweight, all-weather footwear  
- Gift buyers seeking premium eco-friendly options

---

## 🧩 Architecture Overview

### Recommended Tech Stack

| Layer | Technology |
|-------|-------------|
| **Frontend** | [Next.js](https://nextjs.org/) or React (SSR/ISR for SEO) |
| **Styling** | [Tailwind CSS](https://tailwindcss.com/) for utility-first design |
| **Backend / eCommerce** | Shopify Storefront API **or** Headless Commerce (Medusa / Commerce Layer) |
| **Payments** | Stripe + regional methods (e.g., UPI, Razorpay) |
| **Hosting** | Vercel / Netlify (frontend) + managed backend |
| **Analytics** | Google Analytics, Meta Pixel |

---

## 🔧 Functional Requirements

### Product Module
- Product grid with filters (size, color, material)
- Product detail pages with:
  - High-resolution zoomable images
  - Material + care info
  - Sustainability badges
  - Variant selector and live stock status

### Cart & Checkout
- Add / remove / update quantity  
- Persistent cart across sessions  
- Address autocomplete and validation  
- Promo codes and order summary  
- Real-time shipping cost calculation  

### UX & Accessibility
- WCAG AA compliant  
- Keyboard navigable  
- ARIA labels for all interactive elements  
- Subtle 120–180 ms transitions  

---

## 🚀 Setup & Development

### 1️⃣ Installation
```bash
git clone https://github.com/yourusername/woolsneak.git
cd woolsneak
npm install
