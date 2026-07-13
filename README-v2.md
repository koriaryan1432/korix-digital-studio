# KoriX Digital Studio — v2 Redesign

> **Premium digital agency website** — fully animated, motion-rich, world-class.

🌐 **Live Site:** https://static.teamily.ai/sites/5670f04f-e01a-4c3f-95dc-9323e8253179/webpages/korix-digital-studio-v2/index.html

---

## 🎨 Design

- **Aesthetic:** Dark, premium, editorial — high-end creative agency
- **Color Palette:** Deep black/charcoal base + electric gold accent
- **Typography:** Syne (display/headings) + Space Grotesk (body)
- **Feel:** Motion-first — every section is alive with intentional animation

---

## ⚡ Animation Stack

| Library | Usage |
|---|---|
| **Three.js** | 800-particle gold WebGL field in hero, mouse-reactive parallax |
| **Anime.js** | Hero text stagger reveal, pricing keyframes, process timeline stagger, counter animation, SVG morphing |
| **Vanta.js** | NET effect animated background on CTA section (lazy-init via IntersectionObserver) |
| **Vanilla-Tilt** | Parallax tilt + glare on all service, bundle, and portfolio cards |
| **Zdog** | 4 pseudo-3D spinning decorative icons (diamond, cube, star, ring) |

---

## 🏗️ Page Sections

1. **Nav** — Sticky, blur-on-scroll, animated gold pulse logo dot, CTA button
2. **Hero** — Full-viewport Three.js particle field + Anime.js staggered headline reveal + SVG morph decoration
3. **Marquee Strip** — Infinite CSS marquee with 12 service/tech items, pauses on hover
4. **Services** — 4 Bento-style cards with Vanilla-Tilt (glare), CSS spotlight follow, Anime.js pricing tier reveal
5. **Bundles** — 3 package cards with Vanilla-Tilt, spotlight, animated conic-gradient border on featured card
6. **Portfolio** — 3 blur-fade reveal cards with Vanilla-Tilt, coming-soon badges
7. **Zdog Strip** — 4 pseudo-3D animated icons spinning continuously
8. **Process** — 4-step timeline with Anime.js stagger animation on scroll
9. **Stats** — Anime.js counter animation (48h, 4 services, 100%, 24/7) triggered on scroll
10. **CTA + Form** — Vanta.js NET effect background, full contact form with shimmer submit button
11. **Footer** — Clean 4-column layout with social links

---

## 📦 Services & Pricing

### Core Services
| Service | Starter | Growth | Pro |
|---|---|---|---|
| Website Design | $499 | $999 | $1,999 |
| Branding | $299 | $599 | $999 |
| E-Commerce | $799 | $1,499 | $2,999 |
| AI Services | $499 | $799 | $1,999 |

### Bundle Packages
| Bundle | Price |
|---|---|
| Startup Launch Pack (Website + Branding + AI Chat) | $1,799 |
| Restaurant Digital Pack (Website + Menu + Booking + Branding) | $1,299 |
| Full Stack Business (All 4 services, fully integrated) | $5,999 |

---

## 🔧 Technical

- **Single HTML file** — all JS/CSS inline or via CDN. Zero build step.
- **CDN imports:** Three.js r160, Anime.js 3.2.2, Vanta.js 0.5.24, Vanilla-Tilt 1.8.1, Zdog 1.x
- **Fonts:** Google Fonts — Syne (display) + Space Grotesk (body)
- **Performance:** Lazy-init Three.js + Vanta.js via IntersectionObserver, requestAnimationFrame loops
- **Responsive:** Mobile-first, animations degrade gracefully on small screens
- **File size:** ~59KB

---

## 🚀 Deploy

This is a static single-file site. To deploy:

```bash
# Switch to v2 branch
git checkout v2

# Open locally
open index.html

# Or serve with any static host (Netlify, Vercel, GitHub Pages, etc.)
# On Vercel: Framework Preset = Other, Build Command = empty, Output Directory = empty
```

---

## 📫 Contact

**KoriX Digital Studio** — We Build Digital Experiences That Convert.

- ✦ Now Accepting International Clients
- 48h Avg Response · 4 Core Services · AI Powered · 🌍 International Clients